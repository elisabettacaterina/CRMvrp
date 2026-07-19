# CRMvrc v.2


# CRMvr v.1

Virtual Reconstruction (VR) processes are, in most cases, the result of a series of activities related to the definition of a representation of Cultural Heritage.

The identification of these processes, together with the analysis of different kind of source documentation, provides to scholars and people involved in 3d modelling different virtual representation of the same object.
  
All information contributes to produce a more detailed understanding of the development of a virtual reconstructed element that must be three-dimensionally defined to be modelled.
  
The three-dimensionally need, that involves metadata and paradata highlighted the necessity of adding more specialized concepts to describe the very complex structure of data provenance in VR, especially as concerns the description of a VR Elements and the relationship among its parts and with the whole and among its referenced sources.

The goal of the VR extension for CRM is an ontology to encode metadata and paradata related to VR processes and knowledge representation structure inside 3D models.

---

The goal of the concept model is to provide support to:

* Understand the VR process and its development 
* Recognize the provenance of information used
* Identify the various version of the same element because of documentation used to model it
* Support the investigation and interpretation about digital representation of elements
* Understand the correlation between parts and whole
* Support the encoding process to identify each part/version of 3d model
* Support the assignment of classification to Reference Sources used in VR to depict uncertainty of the 3D representation
* Support the assignment of level of accuracy of VR elements that can be deducted from the Reference Source

The model is built on the same principle of CIDOC-CRM. The model reuses, when appropriate part of the CIDOC-CRM classes and properties, and refers to other CRM extensions that were developed to ensure the completeness of documentation.

# References
// Load Citation.js
const { Cite } = require('@citation-js/core')
// Load plugins
require('@citation-js/plugin-doi')
require('@citation-js/plugin-csl')

// Parse input
Cite.async('10.7717/peerj-cs.214').then(data => {
  // Format output
  const bibliography = data.format('bibliography', {
    format: 'html',
    style: 'apa',
    lang: 'en-US'
  })
  console.log(bibliography)
})
Giovannini, Elisabetta Caterina (2018) Virtual Reconstruction Information Management. A scientific method and 3D visualization of Virtual Reconstruction Processes., [Dissertation thesis], Alma Mater Studiorum Università di Bologna. Dottorato di ricerca in Architettura, 30 Ciclo. DOI 10.6092/unibo/amsdottorato/8330.





