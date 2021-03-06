Conceptionary
==
If you want to learn more about "What is a __Conceptionary__ ?", then you can have a look <a href="https://github.com/iPlumb3r/BizApp-Spec-Methodo/tree/master/2_Deliverables/Conceptionary">here</a>   
* A short description of each __Concept__ is provided hereafter in this page. 
* For a more complete description of each __Concept__ just open its "ID Card" (Thanks to the link in the "Concept ID" column).

Key Concepts
-

<table>
    <thead>
        <tr>
            <th>Concept ID</th>
            <th>Prefered Label</th>
            <th>Description</th>      
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%230_topic.md">#0</a></td>
            <td>topic</td>
            <td>A particular thing.</td>
        </tr>
        <tr>
            <td><a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%230s_Things.md">#0s</a></td>
            <td>Things</td>
            <td>The set of ALL <a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%230_topic.md">#0</a> (topics).</td>
        </tr>
        <tr>
            <td><a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%231_tuple.md">#1</a></td>
            <td>tuple</td>
            <td>A link between 2 (or potentially several) <a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%230_topic.md">#0</a> (topics).</td>
        </tr>
        <tr>
            <td><a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%231s_Tuples">#1s</a></td>
            <td>Tuples</td>
            <td>The set of ALL <a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%231_tuple.md">#1</a> (tuples).</td>
        </tr>
        <tr>
            <td><a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%232_type.md">#2</a></td>
            <td>type</td>
            <td>A set of <a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%230_topic.md">#0</a> (topics) which are sharing commons characteristics.</td>           
        </tr>
        <tr>
            <td><a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%232s_Types.md">#2s</a></td>
            <td>Types</td>
            <td>The set of ALL <a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%232_type.md">#2</a> (types).</td>      
        </tr>
    </tbody>
</table>

__Illustration__   
![Concepts](https://github.com/iPlumb3r/KeQuarks/blob/master/images/KeQuarksConcepts_2020-03-16.png)

__Important Note 1__ :
* As a #1 is also a #0, the (Meta-)Model automatically provide a reification mechanism !

__Important Note 2__ :
* If #1 (tuple) arity is = 2, in order to provide a given semantic, an "orientation" is required (e.g. starts from / ends to)
* If #1 (tuple) arity is > 2, in order to provide a given semantic, there is a need for #RoleType (& #Role) concept(s)

Derived (Useful) Concepts
-
<table>
    <thead>
        <tr>
            <th>Concept ID</th>
            <th>Prefered Label</th>
            <th>Description</th>      
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%233_topicType.md">#3</a></td>
            <td>topic type</td>
            <td>A <a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%232_type.md">#2</a> (type) of <a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%230_topic.md">#0</a> (topics) = A - given - set of "similar" topic(s).</td>
        </tr>
        <tr>
            <td><a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%233s_TopicTypes.md">#3s</a></td>
            <td>Topic Types</td>
            <td>The set of ALL <a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%233_topicType.md">#3</a> (topic types).</td>
        </tr>
        <tr>
            <td><a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%234_tupleType.md">#4</a></td>
            <td>tuple type</td>
            <td>A <a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%232_type.md">#2</a> (type) of <a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%231_tuple.md">#1</a> (tuples) = A - given - set of "similar" tuple(s).</td>
        </tr>
        <tr>
            <td><a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%234s_TupleTypes.md">#4s</a></td>
            <td>Tuple Types</td>
            <td>The set of ALL <a href="https://github.com/iPlumb3r/KeQuarks/blob/master/1_Semantic/Conceptionary/%234_tupleType.md">#4</a> (tuple types).</td>
        </tr>
    </tbody>
</table>

__Illustration__   
![Sets](https://github.com/iPlumb3r/KeQuarks/blob/master/images/KeQuarksSets_2020-03-16.png)

__OWL Ontology__   
An OWL ontology of which implements this model is available <a href="http://hubject.net/iPlumb3r/Ontologies/KeQuarks_KL/index-en.html">here</a>

__Important Note__ : At this point it is important to distinguish :   
* Topic-based modeling paradims (Based on "Oriented 2-Ary Tuples") : e.g. BORO, RDF(S)-OWL, ...
* Role-based modeling paradims (Based on "Non Oriented N-Ary Tuples") : e.g. Topic Maps, Grakn,...

See a Use Case about those differents <a href="https://github.com/iPlumb3r/KeQuarks/blob/master/0_UseCases/kindOfModels.md">"kind of models"</a>


Tuple-Based Concepts (And Role-Based Concepts)
-

To Be Completed ...

In the process to build a ID Card for each concept of this page :   
https://github.com/iPlumb3r/KeQuarks/blob/master/Concepts/ReadMe.md
