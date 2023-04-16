---
schema: default
title: Time Ontology
notes: >-
  This vocabulary defines temporal entities such as time intervals, their
  properties and relationships.
organization: DataScientia Foundation
resources:
  - name: TIME.UAN.owl
    url: >-
      http://git.knowdive.disi.unitn.it:8080/knowledge/LiveKnowledge/SREP/time/raw/master/TIME.UAN.owl
    format: owl
    description: >-
      This vocabulary defines temporal entities such as time intervals, their
      properties and relationships.
    license: Creative Commons
    status: Unannotated
    byteSize: '81.008'
    issued: '2017-04-06'
    language: en
    modified: '17 December 2020, 01:44 (UTC+01:00)'
    OntologyEngineeringTool: Protégé
    ontologyLanguage: owl
    ontologySyntax: rdf
    example: Unknown
    ReferenceLKRepository: SREP
    referenceOntology: Unknown
    referenceDatasets: Unknown
distribution: time-owl
keyword: Time
publisher: W3C
category:
  - Upper-Level
versionNotes: >-
  The new version includes updates in 2016-2017: - initial update of OWL-Time -
  modified to support arbitrary temporal reference systems - adjust range of
  time:timeZone to time:TimeZone, moved up from the tzont ontology. - restore
  time:Year and time:January which were present in the 2006 version of the
  ontology, but now marked deprecated. - intervalIn, intervalDisjoint,
  monthOfYear added; TemporalUnit subclass of TemporalDuration - hasTime,
  hasXSDDuration added; Number removed; all duration elements changed to
  xsd:decimal - Update of OWL-Time ontology, extended to support general
  temporal reference systems.
landingPage: 'http://www.w3.org/'
accessRigths: Public
creator: 'Feng Pan, Jerry R. Hobbs, Simon Cox'
hasVersion: Unknown
isVersionOf: Unknown
issued: '2017-04-06'
modified: '17 December 2020, 01:44 (UTC+01:00)'
language: en
provenance: "(2013-05-22) Bernard Vatant: This important vocabulary is much reused, but is unfortunately stuck on the W3C track at ""Working Draft"" stage, and badly needs to move forward.
(2014-05-21) Bernard Vatant: Another year has passed, but time has not moved forward ...
(2015-05-01) Bernard Vatant: ... the more things change, the more they are the same. Why is time so badly ignored by the linked data community? Too complicated?
(2016-07-08) Ghislain Atemezing: A new revised version is on the way at http://w3c.github.io/sdw/time/ by the SDW WG. See https://raw.githubusercontent.com/w3c/sdw/gh-pages/time/rdf/time.ttl
(2017-08-09) Pierre-Yves Vandenbussche: The new version includes updates in 2016-2017: - initial update of OWL-Time - modified to support arbitrary temporal reference systems - adjust range of time:timeZone to time:TimeZone, moved up from the tzont ontology. - restore time:Year and time:January which were present in the 2006 version of the ontology, but now marked deprecated. - intervalIn, intervalDisjoint, monthOfYear added; TemporalUnit subclass of TemporalDuration - hasTime, hasXSDDuration added; Number removed; all duration elements changed to xsd:decimal - Update of OWL-Time ontology, extended to support general temporal reference systems
Provenance from:LOV"
page: 'http://www.w3.org/2006/time'
wasGeneratedBy: crowd-sourced community effort
versionInfo: version v2017-04-06
formalityLevel: Teleontology
OntologyEngineeringMethodology: Unknown
acronym: time
CompetencyQuestion: Unknown
preferredNamespacePrefix: time
toDoList: To completely annotate.
namespacesGenerated: Unknown
namespacesReused: Unknown
datasetLevel: Knowledge Level(L3-4)
spatialExtent: Unknown
temporalExtent: Unknown
---