import argparse


parser = argparse.ArgumentParser(description='Converts a list into a diceroller-formatted md table', prog='txt2dice')
parser.add_argument('input', help='The file to convert to markdown!')

parser.add_argument('--output', '-o', help='The name of the file to write to! Warning: This WILL overwrite any file that exists already.Default is txt2dice-output.md', default='txt2dice-output.md', required=False)
parser.add_argument('--title', '-t', help='The name of the table you will generate! It will also add it as a block id.', default='Table', required=False)

args = parser.parse_args()

listOfLines = []

mdTableBody = ""

mdTable = ""  

try:
  with open(f'{args.input}') as afile:
    listOfLines = afile.read().splitlines() 
except FileNotFoundError:
  print(f"Could not find {args.input}")

num = 1
for item in listOfLines:
  mdTableBody += f"\n|{num}|{item}|"
  num +=1

mdTableBody += f"\n^{args.title}\n"
mdtableHeader = f"""| dice: 1d{num-1} | {args.title}|
| --------- | ------------------- |"""

mdTable = mdtableHeader + mdTableBody

if args.output.endswith('.md'):
  text_file = open(f"tables/{args.output}", "w")
  text_file.write(mdTable)
  text_file.close()
else:
  text_file = open(f"table/{args.output}.md", "w")
  text_file.write(mdTable)
  text_file.close()

print(f"Converted and saved to {args.output}!")
