PROGRAM = Sequitur

JAVA = javac -O

SOURCES = Symbol.java Guard.java Terminal.java NonTerminal.java \
	  Rule.java Sequitur.java

CLASSFILES = $(SOURCES:.java=.class)

%.class : %.java
	$(JAVA) $< 

#-------------------------------------------------------------------------------#

clean : 
	$(RM) $(CLASSFILES) $(PROGRAM).class 

$(PROGRAM) : $(CLASSFILES) $(PROGRAM).class

