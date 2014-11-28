#README

1. Add the Amplicon_fast directory to your V3 recipes folder:

	C:\Illumina\MiSeq Control Software\Recipe\V3

2. Add the line 'Chemistry,Amplicon_fast' to the header section of your SampleSheet.csv.

	- This is how you specify the recipe directory to use, this one is for dual indexed libraries.
	- See example SampleSheet.csv provided.

3. Add the line 'PercentTilesToScan,0.5' to the data section of your SampleSheet.csv.

	- This specifies the fraction of tiles to image, 0.5 (50%) will image only a single surface.
