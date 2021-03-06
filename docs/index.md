None
ayout: default
---

## biolink model


Entity and association taxonomy and datamodel for life-sciences data

### Classes

 * [relationship type](RelationshipType.html)
 * [named thing](NamedThing.html)
    * [biological entity](BiologicalEntity.html)
       * [organismal entity](OrganismalEntity.html)
          * [individual organism](IndividualOrganism.html)
             * [case](Case.html)
          * [population of individual organisms](PopulationOfIndividualOrganisms.html)
          * [biosample](Biosample.html)
          * [anatomical entity](AnatomicalEntity.html)
             * [cellular component](CellularComponent.html)
             * [cell](Cell.html)
             * [gross anatomical structure](GrossAnatomicalStructure.html)
          * [life stage](LifeStage.html)
       * [disease or phenotypic feature](DiseaseOrPhenotypicFeature.html)
          * [disease](Disease.html)
          * [phenotypic feature](PhenotypicFeature.html)
       * [environment](Environment.html)
          * [drug exposure](DrugExposure.html)
          * [treatment](Treatment.html)
       * [molecular entity](MolecularEntity.html)
          * [chemical substance](ChemicalSubstance.html)
             * [drug](Drug.html)
          * [genomic entity](GenomicEntity.html)
             * [genome](Genome.html)
             * [transcript](Transcript.html)
             * [exon](Exon.html)
             * [coding sequence](CodingSequence.html)
             * [gene or gene product](GeneOrGeneProduct.html)
                * [gene](Gene.html)
                * [gene product](GeneProduct.html)
                   * [protein](Protein.html)
                      * [protein isoform](ProteinIsoform.html)
                   * [gene product isoform](GeneProductIsoform.html)
                   * [RNA product](RnaProduct.html)
                      * [RNA product isoform](RnaProductIsoform.html)
                      * [noncoding RNA product](NoncodingRnaProduct.html)
                         * [microRNA](Microrna.html)
             * [genotype](Genotype.html)
             * [haplotype](Haplotype.html)
             * [sequence variant](SequenceVariant.html)
          * [macromolecular complex](MacromolecularComplex.html)
          * [gene family](GeneFamily.html)
       * [molecular activity](MolecularActivity.html)
       * [biological process](BiologicalProcess.html)
          * [pathway](Pathway.html)
          * [physiology](Physiology.html)
    * [information content entity](InformationContentEntity.html)
       * [confidence level](ConfidenceLevel.html)
       * [evidence type](EvidenceType.html)
       * [publication](Publication.html)
       * [association](Association.html)
          * [genotype to genotype part association](GenotypeToGenotypePartAssociation.html)
          * [genotype to gene association](GenotypeToGeneAssociation.html)
          * [genotype to variant association](GenotypeToVariantAssociation.html)
          * [gene to gene association](GeneToGeneAssociation.html)
             * [gene to gene homology association](GeneToGeneHomologyAssociation.html)
             * [pairwise gene or protein interaction association](PairwiseGeneOrProteinInteractionAssociation.html)
          * [molecular interaction](MolecularInteraction.html)
          * [chemical to thing association](ChemicalToThingAssociation.html)
          * [case to thing association](CaseToThingAssociation.html)
          * [chemical to gene association](ChemicalToGeneAssociation.html)
          * [chemical to disease or phenotypic feature association](ChemicalToDiseaseOrPhenotypicFeatureAssociation.html)
          * [chemical to pathway association](ChemicalToPathwayAssociation.html)
          * [chemical to gene association](ChemicalToGeneAssociation.html)
          * [biosample to thing association](BiosampleToThingAssociation.html)
          * [biosample to disease or phenotypic feature association](BiosampleToDiseaseOrPhenotypicFeatureAssociation.html)
          * [entity to phenotypic feature association](EntityToPhenotypicFeatureAssociation.html)
          * [disease or phenotypic feature association to thing association](DiseaseOrPhenotypicFeatureAssociationToThingAssociation.html)
             * [disease or phenotypic feature association to location association](DiseaseOrPhenotypicFeatureAssociationToLocationAssociation.html)
          * [thing to disease or phenotypic feature association](ThingToDiseaseOrPhenotypicFeatureAssociation.html)
          * [disease to thing association](DiseaseToThingAssociation.html)
          * [genotype to phenotypic feature association](GenotypeToPhenotypicFeatureAssociation.html)
          * [environment to phenotypic feature association](EnvironmentToPhenotypicFeatureAssociation.html)
          * [disease to phenotypic feature association](DiseaseToPhenotypicFeatureAssociation.html)
          * [case to phenotypic feature association](CaseToPhenotypicFeatureAssociation.html)
          * [gene to thing association](GeneToThingAssociation.html)
          * [variant to thing association](VariantToThingAssociation.html)
          * [gene to phenotypic feature association](GeneToPhenotypicFeatureAssociation.html)
          * [gene to disease association](GeneToDiseaseAssociation.html)
             * [gene as a model of disease association](GeneAsAModelOfDiseaseAssociation.html)
             * [gene has variant that contributes to disease association](GeneHasVariantThatContributesToDiseaseAssociation.html)
          * [variant to phenotypic feature association](VariantToPhenotypicFeatureAssociation.html)
          * [variant to disease association](VariantToDiseaseAssociation.html)
          * [genotype to thing association](GenotypeToThingAssociation.html)
          * [gene to expression site association](GeneToExpressionSiteAssociation.html)
          * [sequence variant modulates treatment association](SequenceVariantModulatesTreatmentAssociation.html)
          * [gene to go term association](GeneToGoTermAssociation.html)
          * [genomic sequence localization](GenomicSequenceLocalization.html)
          * [sequence feature relationship](SequenceFeatureRelationship.html)
             * [transcript to gene relationship](TranscriptToGeneRelationship.html)
             * [gene to gene product relationship](GeneToGeneProductRelationship.html)
             * [exon to transcript relationship](ExonToTranscriptRelationship.html)
          * [gene regulatory relationship](GeneRegulatoryRelationship.html)
          * [anatomical entity to anatomical entity association](AnatomicalEntityToAnatomicalEntityAssociation.html)
             * [anatomical entity part of anatomical entity association](AnatomicalEntityPartOfAnatomicalEntityAssociation.html)
       * [association result set](AssociationResultSet.html)
    * [planetary entity](PlanetaryEntity.html)
       * [environmental process](EnvironmentalProcess.html)
       * [environmental feature](EnvironmentalFeature.html)
       * [geographic location](GeographicLocation.html)
       * [geographic location at time](GeographicLocationAtTime.html)
    * [clinical entity](ClinicalEntity.html)
       * [clinical trial](ClinicalTrial.html)
       * [clinical intervention](ClinicalIntervention.html)
    * [device](Device.html)
 * [administrative entity](AdministrativeEntity.html)
    * [provider](Provider.html)
 * [attribute](Attribute.html)
    * [biological sex](BiologicalSex.html)
       * [phenotypic sex](PhenotypicSex.html)
       * [genotypic sex](GenotypicSex.html)
    * [severity value](SeverityValue.html)
    * [frequency value](FrequencyValue.html)
    * [clinical modifier](ClinicalModifier.html)
    * [onset](Onset.html)
    * [zygosity](Zygosity.html)
 * [occurrent](Occurrent.html)
    * [activity and behavior](ActivityAndBehavior.html)
    * [procedure](Procedure.html)
    * [phenomenon](Phenomenon.html)

### Mixins

 * [ontology class](OntologyClass.html)
    * [gene ontology class](GeneOntologyClass.html)
    * [organism taxon](OrganismTaxon.html)
 * [thing with taxon](ThingWithTaxon.html)
 * [gene grouping](GeneGrouping.html)
 * [entity to disease association](EntityToDiseaseAssociation.html)
 * [model to disease mixin](ModelToDiseaseMixin.html)
