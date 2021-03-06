---
layout: default
---

## gene as a model of disease association


None

URI: [http://bioentity.io/vocab/GeneAsAModelOfDiseaseAssociation](http://bioentity.io/vocab/GeneAsAModelOfDiseaseAssociation)


![img](http://yuml.me/diagram/nofunky/class/[gene to disease association]^-[gene as a model of disease association], [gene as a model of disease association]-association type >[ontology class], [gene as a model of disease association]-subject >[gene or gene product], [genomic entity]^-[gene or gene product], [gene or gene product]-in taxon >[organism taxon], [ontology class]^-[organism taxon], [gene as a model of disease association]-relation >[relationship type], [gene as a model of disease association]-object >[disease], [disease or phenotypic feature]^-[disease], [disease]-in taxon >[organism taxon], [gene as a model of disease association]-qualifiers >[ontology class], [gene as a model of disease association]-publications >[publication], [information content entity]^-[publication], [gene as a model of disease association]-provided by >[provider], [administrative entity]^-[provider], [gene as a model of disease association]-frequency qualifier >[frequency value], [attribute]^-[frequency value], [gene as a model of disease association]-severity qualifier >[severity value], [attribute]^-[severity value], [gene as a model of disease association]-onset qualifier >[onset], [attribute]^-[onset])
## Mappings


## Inheritance

 *  is_a: [gene to disease association](GeneToDiseaseAssociation.html)
 *  mixin: [model to disease mixin](ModelToDiseaseMixin.html)
 *  mixin: [entity to disease association](EntityToDiseaseAssociation.html)

## Children



## Fields

 * [association type](association_type.html)
    * _connects an association to the type of association (e.g. gene to phenotype)_
    * __range__: [ontology class](OntologyClass.html)
    * inherited from: [association](Association.html)
 * [subject](subject.html)
    * _A gene that has a role in modeling the disease. This may be a model organism ortholog of a known disease gene, or it may be a gene whose mutants recapitulate core features of the disease.
  _
    * __range__: [gene or gene product](GeneOrGeneProduct.html) [required]
    * inherited from: [association](Association.html)
 * [negated](negated.html)
    * _if set to true, then the association is negated i.e. is not true_
    * __range__: xsd:boolean
    * inherited from: [association](Association.html)
 * [relation](relation.html)
    * _The relationship to the disease
  _
    * __range__: [relationship type](RelationshipType.html) [required]
    * subproperty_of: [RO:0003301](http://purl.obolibrary.org/obo/RO_0003301)
    * inherited from: [association](Association.html)
 * [object](object.html)
    * _connects an association to the object of the association. For example, in a gene-to-phenotype association, the gene is subject and phenotype is object._
    * __range__: [disease](Disease.html) [required]
    * inherited from: [association](Association.html)
 * [qualifiers](qualifiers.html)
    * _connects an association to qualifiers that modify or qualify the meaning of that association_
    * __range__: [ontology class](OntologyClass.html)*
    * inherited from: [association](Association.html)
 * [publications](publications.html)
    * _connects an association to publications supporting the association_
    * __range__: [publication](Publication.html)*
    * inherited from: [association](Association.html)
 * [provided by](provided_by.html)
    * _connects an association to the agent (person, organization or group) that provided it_
    * __range__: [provider](Provider.html)
    * inherited from: [association](Association.html)
 * [id](id.html)
    * __range__: identifier type
    * inherited from: [named thing](NamedThing.html)
 * [label](label.html)
    * _A human-readable name for a thing_
    * __range__: label type
    * inherited from: [named thing](NamedThing.html)
 * [frequency qualifier](frequency_qualifier.html)
    * _a qualifier used in a phenotypic association to state how frequent the phenotype is observed in the subject_
    * __range__: [frequency value](FrequencyValue.html)
    * inherited from: [entity to disease association](EntityToDiseaseAssociation.html)
 * [severity qualifier](severity_qualifier.html)
    * _a qualifier used in a phenotypic association to state how severe the phenotype is in the subject_
    * __range__: [severity value](SeverityValue.html)
    * inherited from: [entity to disease association](EntityToDiseaseAssociation.html)
 * [onset qualifier](onset_qualifier.html)
    * _a qualifier used in a phenotypic association to state when the phenotype appears is in the subject_
    * __range__: [onset](Onset.html)
    * inherited from: [entity to disease association](EntityToDiseaseAssociation.html)
