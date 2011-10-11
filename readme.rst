============================
Title
============================
Slide #1:  Data icon > Transformation > Visualization icon > Real world impact icon
Introductions and 13 favorite tools/languages
	Database and/or spreadsheet tool
	DSL and/or general programming language
	Visualization tools
Who has Javascript experience?


Slide #2: Browser poll?
	Chrome
	Firefox 3+
	IE9
	Safari
	Opera
	None of the above?


Slide #3: Installation
if you have developed in the browser**
	if git.installed
		git clone xxxxxxxxxxxxxx
		join github; fork; make pull requests;
	else dropbox.account 
		dropbox.com/adfasdfasdfasdf
	else
		thumbdrive
	end
else
	jsfiddle links 1n
end

** chrome might have funny behavior if you 
don't serve up d3 root as localhost


>>>>>>>>>>>>>  Everybody ready that wants to be ready? >>>>>>>>>>>>>>>>>>

Canonical test: go to hello world tutorial and see if you have d3 at the console
	you should see 
		> d3
			object

>>>>>>>>>>>>>  Everybody ready that wants to be ready? >>>>>>>>>>>>>>>>>>

Resources
	github 
		API
		Examples/Gallery
		source
	online tutorials
	google group
	twitter: @i3enhamin, @mbostock
	SVG specification: v1.1 -> 2.0 is being worked on


Tutorials
	Ok, if you're not here... I apologize, but I strongly encourage you to stay
	so that you can absorb the spirit and go play in your free time.

	Who has jQuery experience? D3 is similar, but can also target SVG -> xml-like image format
		- Long story short... they do some fancy functional programming
		  to make it possible for us to declaratively (and efficiently)
		  reach into the dom tree.

	Discuss the tutorials/topic outline

		 exercise-01 ... modify per our use
			 source d3 file 
			 unified d3 namepace
			 selector notation
				 supports css3 selector notation
					 element, class, id, attribute
					 descendant
					 etc**
				 d3.select("") ~ $("") ~ jQuery("")
			 cascading/callbacks
			 note that we are only manipulating html elements so far


		 exercise-03 
		 	- get rid of text
		 	- get rid of clever tranform
		    .append("svg:svg")  --> mention that he has other namespace**
	    	.attr("width", w)
	    	make a namespace variable for the svg canvas (not to be confused with the "other" <canvas>)
	    		it's highly likely that we will want to reuse it and traversing the dom tree
	    		to get here is 'expensive'


		 exercise-10 ... 
		 	identity function**
		 		- functional programming
		 	data binding
		 		update
		 		enter
		 		exit
		 			explain the misnomer nature, stage/venn diagram analogy
		 	g namespace
		 	clever transform

		 exercise-11 ... 
		 	2D array into html table
		 	scales

		 exercise-12 ... bar chart
		 	range bands**

		 finale: exercise 13 bar chart with axes elements
		 	ex

		 Extras
			 css-hover
			 d3 event-based transition
			 ease
			 tween
			 interpolate


Conclusion / summary

Checklist
	Ensure that 6 examples are as I want them
	5 + 6 slides


** Perhaps we should videotape it