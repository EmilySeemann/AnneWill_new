# Anne Will: Teilnehmer

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

# Edge-Attribute

**from**
- iniitierender Knoten, in diesem Fall: Teilnehmer oder Partei

**to**
- erhaltender Knoten, in diesem Fall: die Folge, in der ein Teilnehmer anwesend war beziehungsweise eine Person, die sich einer bestimmten Partei zuordnen lässt

**relationship**
- definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten, in diesem Fall: Handelt es sich um eine Beziehung zwsichen einer Person und einer Folge oder handelt es sich um eine Beziehung zwischen einer Person und einer Partei?

# Node-Attribute

**id**
- eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.

**name**
- Name oder Bezeichnung des Knotens

**type**
- relevant bei two-mode Netzwerken, in diesem Fall: Unterscheidet, ob es sich um eine Person, eine Partei oder eine Folge handelt

**party**
- gibt an, in welcher Partei sich ein Teilnehmer befindet

**sector**
- gibt an, in welchem Bereich sich die Tätigkeit des jeweiligen Teilnehmers einordnen lässt
  
**country**
- gibt an, in welchem Land der Teilnehmer momentan lebt 
