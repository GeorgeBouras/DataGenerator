Realistic data generator

Output can be printed to screen, csv, json or xml files.

Quick usage


  gendata --version
  
  gendata --help
  
  gendata --config /tmp/opt.conf  --columns example_perlcode.conf
  
  gendata --config options.conf   --columns example_perlcode.conf --format xml
  
  gendata --columns /tmp/col.conf --format json --output /tmp/out.json
  
  gendata -f xml  -o output.xml
  
  gendata -f json -o output.json  

Command line switches. All of them are optional

--version Shows version

--help    Shows help screen

--config  Default Options file.    Default location is $script_dir/gendata.conf

--columns Column definition file . Default location is $script_dir/gendata.columns

--format  csv, xml, json.          Default is csv

--output  Output File.             Default is screen

George Bouras

george.mpouras@yandex.com

Athens/Greece, 7 Apr 2021
