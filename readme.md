vocab-trainer
-------------

Simple command-line flashcard tool to learn foreign vocabulary.

	usage: vocab-trainer [-h] [--rand] [-r] filename

	Command line application to practice foreign vocabulary or anything that you
	need to rote learn

	positional arguments:
	  filename    filename to read wordlist from; default is words.txt

	optional arguments:
	  -h, --help  show this help message and exit
	  --rand      set random mode on; RANDOM MODE just asks words randomly from
		      the file provided, until you had enough, without producing any
		      output file. By default the program asks every word in a file
		      only once, and quits after you have went through all of them. It
		      also writes out your errors into FILENAME.err so you can
		      practice the words which you missed
	  -r          quiz in reversed order (i.e. program writes out the first field
		      and asks for the second)
