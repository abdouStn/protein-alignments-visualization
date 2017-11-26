# protein-alignments-visualization

Projection of protein sequence alignments on known 3D structures.

Development of procedures in Jmol scripting language.

this project falls within the course named "HMSN304 Structures de molécules", taught under Master 2 Bioinformatics at the Faculty of Science of the University of Montpellier.


* Requirement:
 
        JMOL IDE >= 14.6.4 

### How is it work ?


Aller dans la console JMOL puis: 

- open/move in working directory (cd path/to/wd)

- run

        script src/jmolGeneric.jmol

- choose using files: from ligne 265

    Note: the modele 1.1 is choosed by default.

- call functions in order

        initialization()
        
        numbering() // to define the new numbering 'property_seqresno' 
        
        alignment() //to define property_qresno and property_qsimil
        
        superpose() // to superpose 2 structures

        compare ()

### Supervisor

Stefano TRAPANI (CBS Centre de Biochimie Structurale de Montpellier - CNRS)

### Author

Abdoulaye Diallo

Audrey Passerieux

Younes Zahidi
