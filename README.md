# Key References #

[Delphor Website](http://www.delphor.net/) 

[Delphor Wiki](https://github.com/delphornet/Cortextual/wiki) 

[Main Project README, including licensing and resources](https://github.com/delphornet/Cortextual/blob/master/README.md)

# Delphor/Enrich Project Managers #

Currently led by Rob Weiss (@3XPlo1t2) and John Eberhardt (@JohnSEberhardt3).

# Delphor/Enrich Project Roadmap #

The roadmap for this project is [here.](https://github.com/delphornet/Cortextual/wiki/Project-Roadmap#delphorenrich-repo-and-project-roadmap)

# Features, Functional Requirements, and Components in this Repo #

+	Feature DE1: Ability to consume inbound ingested streams from the socket
	+	Functional Requirement DE1A: ability to unpack the streams and load them into the enrichment topology
		+	Component DE1Ai: Apache Storm spout for reading in streams
			+	**Status: complete**
+	Feature DE2: Streaming framework for loading topologies
	+	Functional Requirement DE2A: Ability to develop and apply specific enrichment ontologies in Apache Storm/Streamparse
		+	Component DE2Ai: Streamparse
			+	**Status: complete**
+	Feature DE3: Basic statistical enrichment
	+	Functional Requirement DE3A: Apply basic statistical functions from the scipy library
		+	Component DE3Ai: Simple traffic counts
			+	**Status: complete**
		+	Component DE3Aii: Calculate the Proportions of Inbound vs. Outbound flows
			+	**Status: complete**
		+	Component DE3Aiii: Calculate skewness of the stream distribution
			+	**Status: complete**
		+	Component DE3Aiv: Calculate kurtosis of the stream distribution
			+	**Status: complete**

If you want to add to the roadmap, learn more [here.](https://github.com/delphornet/Cortextual/wiki/Feature-and-Release-Management)

# What's Here #

|**Package** | **What it Does** | **References** |
|-------------|----------|------------|
|configured instances of scipy describe | calculates skewness and curtosis and normalizes to 0 - 255|[scipy](http://www.scipy.org/)|
|python traffic counts|counts traffic for a node and normalizes to 0 - 255|www|
|python proportions calculator|calculates proportion of inbound v outbound traffic and normalizes to 0 - 255|www|
|-------|---------------|----------------|

# Contributors #

Rob Weiss (@3XPlo1t2)
