---
layout: default
---

## sequence variant


An allele that varies in its sequence from what is considered the reference allele at that locus.

URI: [http://bioentity.io/vocab/SequenceVariant](http://bioentity.io/vocab/SequenceVariant)


![img](http://yuml.me/diagram/nofunky/class/[genomic entity]^-[sequence variant], [sequence variant]-has gene >[gene], [gene or gene product]^-[gene], [gene]-in taxon >[organism taxon], [ontology class]^-[organism taxon], [sequence variant]-in taxon >[organism taxon])
## Mappings

 * [GENO:0000002](http://purl.obolibrary.org/obo/GENO_0000002)
 * [WD:Q15304597](http://purl.obolibrary.org/obo/WD_Q15304597)
 * [SIO:010277](http://semanticscience.org/resource/SIO_010277)
 * [VMC:Allele](http://purl.obolibrary.org/obo/VMC_Allele)

## Inheritance

 *  is_a: [genomic entity](GenomicEntity.html)

## Children


## Used in

 *  class: [genotype to variant association](GenotypeToVariantAssociation.html) references: [sequence variant](SequenceVariant.html)
 *  class: [variant to thing association](VariantToThingAssociation.html) references: [sequence variant](SequenceVariant.html)
 *  class: [variant to phenotypic feature association](VariantToPhenotypicFeatureAssociation.html) references: [sequence variant](SequenceVariant.html)
 *  class: [variant to disease association](VariantToDiseaseAssociation.html) references: [sequence variant](SequenceVariant.html)
 *  class: [gene has variant that contributes to disease association](GeneHasVariantThatContributesToDiseaseAssociation.html) references: [sequence variant](SequenceVariant.html)
 *  class: [sequence variant modulates treatment association](SequenceVariantModulatesTreatmentAssociation.html) references: [sequence variant](SequenceVariant.html)

## Fields

 * [has gene](has_gene.html)
    * _connects and entity to a single gene_
    * __range__: [gene](Gene.html)
    * __Local__
 * [has biological sequence](has_biological_sequence.html)
    * _connects a genomic feature to its sequence_
    * __range__: biological sequence
    * inherited from: [genomic entity](GenomicEntity.html)
 * [id](id.html)
    * __range__: identifier type
    * inherited from: [named thing](NamedThing.html)
 * [label](label.html)
    * _A human-readable name for a thing_
    * __range__: label type
    * inherited from: [named thing](NamedThing.html)
 * [in taxon](in_taxon.html)
    * _connects a thing to a class representing a taxon_
    * __range__: [organism taxon](OrganismTaxon.html)
    * inherited from: [thing with taxon](ThingWithTaxon.html)
