

([home](README.md))


# Codex Xolotl · Cite Architecture

A two-day workshop on the *Homer Multitext* and its CITE Architecture and how it might contribute to, collaborate with, and support work on the Codex Xolotl.

## Friday

### Morning Session

House A. 9:00–12:30

- Codex Xolotl work.
- *Homer Multitext* Show-and-Tell. What you can do with carefully constructed data in a single, **plain-text** file.

	- [HMT Facsimile](file:///Users/cblackwell/Dropbox/CITE/scala/codicography/facsimile_output/venA/urn_cite2_hmt_msA-v1_15v.html)
	- [HMT CiteApp](http://www.homermultitext.org/hmt-digital/index.html?urn=urn:cts:greekLit:tlg0012.tlg001.msA:1.1)
	- [Microservice](http://beta.hpcc.uh.edu/hmt/hmt-microservice/)
	- [Lexicon](http://folio2.furman.edu/lsj/)
	- [Reader’s Edition](http://folio2.furman.edu/ot/pages/index.html)
	- Some alignments:
		- [Verse alignment](file:///Users/cblackwell/Dropbox/Grants/NEHJune2019/demo_pages/textCart_site/alignment/demo1.html?urn=urn:cts:greekLit:tlg0012.tlg001.allen:1.1-1.6&urn=urn:cts:fufolio:pope.iliad.fu2019:1.1&urn=)
		- [Translation alignment](file:///Users/cblackwell/Dropbox/Grants/NEHJune2019/demo_pages/textCart_site/alignment/demo2.html?urn=urn:cts:greekLit:tlg0031.tlg003.kjv.token:2.1&urn=urn:cts:greekLit:tlg0031.tlg003.reina.token:2.1&urn=urn:cts:greekLit:tlg0031.tlg003.vulgate.token:2.1&urn=urn:cts:greekLit:tlg0031.tlg003.wh.token:2.1&urn=)
		- [Everything alignment](file:///Users/cblackwell/Dropbox/Grants/NEHJune2019/demo_pages/textCart_site/alignment/demo4.html?urn=urn:cts:fuMisc:basho.kawazu.fuEd.tok:1-3&urn=urn:cts:fuMisc:basho.kawazu.fuEdKana.tok:1-3&urn=urn:cts:fuMisc:basho.kawazu.fuEdRom.tok:1-3&urn=urn:cts:fuMisc:basho.kawazu.fuTransEng.tok:1-3&urn=urn:cts:fuMisc:basho.kawazu.saijiki:1-3&urn=)
- The **CITE Architecture** theoretical and practical overview:
	- Naming things.
	- Disk space is cheaper than CPU time.
	- It is always easier to **aggregate** than to **disaggregate**.
	- [presentation on URNs](file:///Users/cblackwell/Dropbox/Presentations/CTS-2018-Ireland/cts3.html). 

### Lunch

Main Building. 12:30–1:30

### Afternoon Session

House A. 2:00–exhaustion

- What CWB has done with the Codex Xolotl data, thus far.
	- [Images](images.md)
	- [Torquemada in CiteApp](file:///Users/cblackwell/Desktop/Codex_Xolotl/CITE%20App/cite-1.14.0.html)
- An idea of what is involved.

## Saturday

### Morning

House A: 9:30–12:30

- Update from CWB
	- Scaffolding for CollectionMaker
	- Demo Collection
- Concerns:
	- Learning curves:
		- `git` and [GitHub](https://github.com/Furman-Editions-In-Progress/xolotl)
		- [Markdown](https://www.markdowntutorial.com)
		- Basic POSIX (Unix/Linux, which includes MacOS) Command-line.
	- Irreducible Complexity
		- The existing app, in France
		- Obvious benefits
			- It works (on Windows)
			- You can do all kinds of crazy queries
		- Obvious costs and ignored costs
			- The data is… where?
			- You can only do queries that the author has thought of.
			- You can only get the outputs and visualizations that the author has thought of. And only on Windows. And in 10 years…?
		- See, by contrast, [this file](https://raw.githubusercontent.com/Furman-Editions-In-Progress/xolotl/master/cex/xolotl_all.cex)
			- No help.
			- No app.
			- But with a Text Editor, you could answer almost any question you could ask.
			- With a little scripting (in Scala, Python, Javascript, C++, whatever) you could answer any questions the data is capable of answering.
		- If I had pursued **CollectionMaker** all night…
			- You could make a new Collection for, *e.g.* comments on images.
			- You would have to:
				- Export it as CEX
				- Add to it, getting everything right
				- Load it into some app or service
				- Ultimatelly, get it online for others to use.
	- Why HMT works:
		- Student-editors have no preconceptions about how work "should" happen.
		- They are students, and are used to learning new ways of working.
		- We get them for 2 weeks in the summer.
		- They go on to amass a few years of experience.
		- They do not expect to type a thing and see it online, incorporated into a published dataset, immediately. They understand that this is unreasonable.
		- (Put another way) The editors and commentators do not expect that they are also the publishers.
- Solutions?
	- A long-term relationship.
	- A specific commitment to training
	- Funding for it.
	- Buy-in for the longer term.

### Mid-Day

A couple of hours to think and do stuff.

### Afternoon

Can we do something, realistically useful, by May? If so, what?

### Dinner

???

