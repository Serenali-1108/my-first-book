
## Installation

*These instructions assume you have an mdBook already set up. Unfamiliar with mdBook? Read the [mdBook guide!](https://rust-lang.github.io/mdBook/)*



## Brief intro to rustviz


General process of writing a new book (provided with visualizations): 
	1. Clone this repo and you will have an empty book
	2. Steps below to prepare the source code and svg files, etc for your own examples to be incorporated into narratives 
 	3. Adding features of your book with hover messages, etc



Steps to create an example of an event:

1. Write source code in Rust (Source.rs)

2. Annotate the source code according to the Table I. in the paper RustViz: Interactively Visualizing Ownership and Borrowing i.e  specify that event using DSL in comment (main.rs)

3. Supply the annotated file to DSL Processor to get the svg:  vis_code.svg and vis_timeline.svg, which is a section is the rustviz repo README (will have another section expanding on this)

4. Could save the input code that actually generate the svg files in a separate folder(annotated_source.rs ) 

5. Save the above files in corresponding separate folders and reference to these assets while writing book

**






