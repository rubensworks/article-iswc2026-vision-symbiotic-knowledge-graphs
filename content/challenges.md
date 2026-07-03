## Scientific challenges
{:#challenges}

Write me
The Semantic Web has been successful at making knowledge interoperable among machines. The next big challenge is making semantic knowledge interoperable with human cognition itself!
Rq: can brain speak http/rdf?
{:.todo}

To augment human intelligence, we propose working towards an integration of human and artificial intelligence.
Concretely, we foresee the creation of *Symbiotic Knowledge Graphs* (SKGs),
which consist of the integration of human knowledge stored in the brain, and external knowledge stored on the Web.
To achieve this, the Semantic Web stack already offers important building blocks,
such as RDF to represent formal knowledge, and SPARQL to retrieve knowledge.
On the one hand, this allows humans to directly access external knowledge.
And on the other hand, this enables external processes or other humans to access knowledge of other humans.
Furthermore, this provides the basis for human cogniton to make use of symbolic reasoning over this integration.

Figure showing brain with augmentation and personal query engine with links to KGs (also incoming).
{:.todo}

This vision can be positioned within the research field of Human Cognitive Augmentation,
which focuses on using technology to enhance human mental capabilities (e.g. memory, focus, and decision-making).
While external devices (e.g. Apple's Vision Pro) could be used that provide actionable information when needed,
they still require indirectly interfacing through a sensory organ (e.g. eyes, skin, ...).
In contrast, *Brain-Computer Interfaces (BCIs)* (such as Neuralink) are more invasive and directly stimulate the brain through electrical or magnetic currents.
While BCIs are not as mature today, we believe they are more promising as they are not restricted by the bandwith limits of sensory organs.

Hereafter, we provide a high-level roadmap that spans several research fields to achieve this vision.
Concretely, there is first a need to represent SKGs in a way that they become an integration point of human and formal knowledge.
Next, we need bidirectional interfacing towards these SKGs.
Finally, we can work on augmenting human intelligence with SKGs.

### Representing Symbiotic Knowledge Graphs

[Human cognition is defined as the mental framework that is responsible for acquiring, storing, transforming, and using information](cite:cites cognitivepsychology).
Within [cognitive architectures](cite:cites actr,soar), this stored information is considered the foundation for intelligence.
As such, the ability to integrate external knowledge into human cognition forms is an important basis for augmenting human intelligence.

Cognitive Architectures: seek computational models of general intelligence that integrate perception, memory, reasoning and action within a unified framework
not limited to biological realism!
Architectures such as ACT-R, Soar and LIDA provide explicit models of declarative and procedural memory, symbolic reasoning and learning, and have been used extensively to model human cognition.
recent surveys emphasize increasing biological plausibility and integration with machine learning techniques.
paid relatively little attention to continuously interacting with large-scale external knowledge graphs or dynamically integrating formal Semantic Web knowledge into human cognition.
Open challenges:
- Biological plausibility
- Integration with large external knowledge bases
- Continuous learning
- Scalable symbolic reasoning
- Bridging cognitive architectures and BCIs
{:.todo}

### Interfacing with Symbiotic Knowledge Graphs

What should the device look like? Should it speak HTTP? Be a query engine? Is this a different section perhaps?
Also talk about ethical implications, such as privacy. I'm sure related work exists...
{:.todo}

In order to connect human knowledge with SKGs,
we need an interface that is able to encode and decode human knowledge, and represent it as formal knowledge (e.g. RDF).

The field of cognitive neuroscience studies how cognitive processes such as memory are implemented in the brain.
The current state of the art of cognitive neuroscience and BCIs are capable of encoding and decoding sensory-related information such as
[converting sound into electrical stimulation of auditory nerve](cite:cites cochlearimplants),
[attempted handwriting movements and converting them to text](cite:cites braintotext),
or [reconstructing visual images from measured brain activity](cite:cites imagereconstruction).
However, arbitrary memories or thoughts can not yet be encoded or decoded.
but [semantic features of story telling can be measured](cite:cites semanticmaps),
such as knowing whether or not something induces fear, or is related to food.

For interfacing human cognition with formal knowledge models such as RDF,
this means that immediate opportunities exist involving sensory-related information.
This includes making external knowledge directly audible to humans through electrical stimulation,
or movement-based manipulation of external knowledge.
Furthermore, there are opportunities for automatic human-specific sentiment extraction of external events.
But in order to extract complete memories, or make other knowledge availably as external memory,
more work is needed in the fields of cognitive neuroscience and BCIs.

In general, [the neural encoding of abstract concepts and complex knowledge relations is not well understood yet](cite:cites neurotechnologieshumancogaug),
which is a critical requirement before we can fully interface with formal knowledge.
Furthermore, current BCIs have a [very limited information bandwidth](cite:cites bcis,noninvacivebcireview).
They can capture things such as attention and intended movement,
but they can are unable to transmit more complex structures such as knowledge relations.

### Augmenting Intelligence with Symbiotic Knowledge Graphs

Neuro-symbolic AI: 
Combines symbolic knowledge representations with neural learning to exploit the complementary strengths of logical reasoning and statistical generalization
nearly all existing neuro-symbolic systems combine symbolic reasoning with artificial neural networks. The possibility of integrating symbolic knowledge directly with biological neural systems through brain-computer interfaces remains almost entirely unexplored.
Open challenges:
- Scalable hybrid reasoning
- Explainability
- Continual learning
- Commonsense reasoning
- Symbol grounding
- Integration of symbolic knowledge with biological cognition
{:.todo}
