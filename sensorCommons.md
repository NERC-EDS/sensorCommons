# The Narrow Middle

The "thin or narrow middle" is defined as using the minimal set of services essential for the system's core, with only these services being standardised. For EDS Commons we provide specifications for persistent identifiers (PIDs), a data model, and a metadata system all underpinned by semantic artefacts and their accompanying tools.

## PIDs

PIDs can identify many different entities. These can be:
- **Born digital**: documents, data, software, services (digital objects), and collections made of them.
- **Physical**: people, instruments, artefacts, samples.
- **Conceptual**: organisations, projects, vocabularies.

The PIDs we are focusing on include identifiers for entities that are core to the EDS data commons and are listed below. We chose these because DOIs are already used by all EDS data centres, ORCIDs and RORs are widely accepted, and BOOST-Instrument PIDs are used for instrument identifiers by the BOOST project.

| Short Name            | Long Name                                        | Official Page                                 | Maturity  | Globally Resolvable | Object Type          |
|----------------------|------------------------------------------------|----------------------------------------------|-----------|---------------------|----------------------|
| ORCID               | Open Researcher and Contributor ID              | [ORCID](https://orcide.org/)                 | Emerging  | Yes                 | People               |
| ROR                 | Research Organisation Registry                  | [ROR](https://ror.org/)                      | Emerging  | Yes                 | Organisation         |
| BOOST-Instrument PIDs | Identifier for Instruments                      | N/A                                          | Emerging  | Yes                 | Instruments         |
| DOI                 | Digital Object Identifier                       | [DOI](https://www.doi.org/)                  | Mature    | Yes                 | Publication         |
| NVS                 | NERC Vocabulary Server                          | [NVS](https://vocab.nerc.ac.uk)              | Mature    | Yes                 | Semantic Repository |
| EnvThes             | Thesaurus for long-term ecological research     | [EnvThes](https://vocabs.lter-europe.net/envthes/en/) | Mature | Yes | Semantic Repository |

## Semantic Artefacts & Tools
- **Controlled Vocabularies**
- **Ontologies**
- **The Semantic Analyser**
- **VocPrez**
- **SKOSMOS**
- **OWL**
- **SKOS**

## Data Model

For sensor data, we adopted the **SensorThingsAPI** as the data model.

The **OGC SensorThings API** provides an open, geospatial-enabled, and unified way to interconnect the Internet of Things (IoT) devices, data, and applications over the web. It has two main functionalities:

1. **Sensing Part**: Manages and retrieves observations and metadata from heterogeneous IoT sensor systems.
2. **Tasking Part**: Provides a standard way to parameterize (task) IoT devices such as sensors or actuators.

We chose the **OGC SensorThingsAPI** because it:
- Provides both an API standard and a data model.
- Is open enough to enable the inclusion of domain-specific metadata and controlled vocabularies.
- Works well with **MQTT**.
- Allows for the publication of data streams.

We plan to publish an **EDS profile** of the SensorThingsAPI to enable practical interoperability. This profile will:
- Semantically enhance the standard with controlled vocabularies.
- Specify common metadata elements to describe a sensor and its lifecycle.

## Discovery Metadata Model

Additionally, we specify a **discovery profile** applicable to all EDS data, leveraging:
- **schema.org**
- **CDIF**
- **FE-DCAT-AP**

This ensures alignment with the **European Open Science Cloud (EOSC)** and **Cross-Domain Interoperability Framework (CDIF)** standards.

## References
- [A Persistent Identifier (PID) Policy for the European Open Science Cloud](file:///C:/Users/alexk/Downloads/a%20persistent%20identifier%20pid%20policy%20for%20the%20european-KI0420576ENN.pdf)
- [Zenodo Record](https://zenodo.org/records/11396767)
