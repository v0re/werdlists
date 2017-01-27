[id]: https://raw.githubusercontent.com/decal/werdlists/master/werd.png ""

werdlists
=========

Text files consisting of word lists, whitespace delimited row-based data, CSV
(Comma Separated Values) and similar data collections that are useful in
manually crafting software test cases or developing an automated black-box
fuzzer. In particular, the data contained within these mostly text files is 
intended for programmatic information security (i.e. "penetration") testing 
purposes.. For anyone already familiar with repositories like
[The attack pattern dictionary](https://github.com/fuzzdb-project/fuzzdb/ "fuzzdb") and 
[The security tester's companion](https://github.com/danielmiessler/SecLists/ "SecLists"), 
then `werdlists` is similar as it's a centralized attack strings resource--just
with its own unique style, original contents, expanded concepts, etc.

The `scripts` folder consists of shell scripts used for maintenance and such. 
Other directories should be outlined in the `root-index.lst` file at tree top.
Furthermore, all files in each directory are detailed in their own `index.lst`
files.  Although the majority of files have the *.txt* extension, pay attention
because other file extensions have meaning as well (such as *.csv* or comma-
separated values, eXtended Markup Language for *.xml* and non-ASCII in *.bin*
files.)

