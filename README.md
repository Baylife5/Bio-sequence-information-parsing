# Bio---sequence-information-parsing
program parses sequence name information from a single line of a FASTQ formatted file.


asks for and collects the seqname line of a FASTQ file using input()
parses out each field of the run information from the string and displays each of them on a new line For example, if I enter the FASTQ seqname line: @EAS139:136:FC706VJ:2:2104:15343:197393 then the program will output:

Instrument = EAS139
Run ID = 136
Flow Cell ID = FC706VJ
Flow Cell Lane = 2
Tile Number = 2104
X-coord = 15343
Y-coord = 197393
