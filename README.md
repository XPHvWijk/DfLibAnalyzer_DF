# DfLibAnalyzer_DF
GUI tool which shows the results of Sonny Falk his Analyzer tool for DF 2026 

This is a GUI wrapper over the work of Sonny Falk. Gives you easy options to sort out what is possible wrong with you project. Read Sonny's analyze information what is different between DF 2026 and all other version. That is does compiles does not imply proper working. 

Most of us will use Libraries from other developers which have sources in it from others, By the different order you could now compile in a different version and by that without knowing have different outcome. Even a icon with the same name in a new lib can give a different result.

The gui wrapper allows you to sort this out.

It is build with a subclass layer. Some classes have some code which code be used in your own subclasses.

One note run in 32 bit compile there is one call (size of file) is not working under 64 bit. And those low calls are not my specialty.
