# Strategy for the Implementation of a FAIR Data Policy in Chile

Second Edition: March 2025

**Powered by:**

* Data Observatory  
* Pontificia Universidad Católica de Chile  
* Universidad Central  
* Universidad de Los Andes

**Authors** (in alphabetical order):\
Abedrapo, I.; Carrasco, R.; Catalán, A.; Díaz, I.; Escapil-Inchauspé, P.; Hartley Belmar, R.; Keim, A.; Koelbl, M.; Meyers, N.; Quiroz, S.; Paredes, Á.; Rivera, M.; Roa, R.

**Contributors and reviewers**\
Kirkpatrick, Christine R.; Cragin, Melissa H.; Meyers, Natalie.\
Muñoz, Patricia; Bravo, Soledad; Roa, Verónica; Muñoz, Francisca.

This document has been based on the guide "FAIR Data Stewardship Plan Template for Organizations and Institutions", from the SDSC Research Data Services Materials Collection, UC San Diego Library Digital Collections (2021). [https://doi.org/10.6075/J0CV4G8C](https://doi.org/10.6075/J0CV4G8C)

This work is licensed under CC BY-NC-SA 4.0. To view a copy of this license, visit  [creativecommons.org/licenses/by-nc-sa/4.0](http://creativecommons.org/licenses/by-nc-sa/4.0)

## Message from the Executive Director

Collaboration between institutions has become a fundamental pillar in today's world for developing projects that generate significant impact at the national level and integrate sustainability from their conception.

When such cooperation aligns with clear strategic objectives, it becomes a catalyst for innovation, enabling more effective actions, and strengthening the capacity to address complex challenges.

This document is the result of a collaborative effort between the Pontificia Universidad Católica de Chile, Universidad Central, Universidad de Los Andes, and the Data Observatory. Since early 2024, these institutions have worked together to design a robust, inclusive, and future oriented proposal.

With a shared vision of optimizing data use, this project not only outlines a path to implement FAIR principles, but also lays the foundation for an advanced data management system. This system aims to boost scientific development and promote the advancement of knowledge in Chile.

Through this document, Chile positions itself as a regional leader in promoting of open data, fostering research, innovation, and sustainable development. It also highlights the role of data as a key input for artificial intelligence, as the country advances toward building an ethical and responsible digital ecosystem. 

Rodrigo Roa López de Heredia\
Executive Director\
Data Observatory Foundation

## 1. Introduction

In the current digital age, data play a critical role in virtually every aspect of society and the economy. In this context, **effective data management has become a necessity** to ensure transparency, efficiency and innovation across diverse sectors.

In 2016, the document entitled *"The FAIR Guiding Principles for scientific data management and stewardship”* [\[1\]](https://www.nature.com/articles/sdata201618) was published in the Scientific Data journal. The objective of this document was to provide guidelines to ensure the findability, accessibility, interoperability, and reusability of digital objects; The FAIR principles emphasize the ability of machines to act, i.e., the ability of computer systems to find, access, interoperate, and reuse data with no or minimal human intervention.

In an increasingly data-centric world [\[2\]](https://doi.org/10.1016/j.ces.2021.117271) driven by large volumes of data, **these principles are fundamental** to maximize the value and impact of the generated information in various areas.

It is essential that Chile adapts and remains competitive in the changing global landscape. To achieve this, it is necessary to design and develop a *"Strategy for the Implementation of a FAIR Data Policy in Chile"*—hereinafter in this document, FAIR Strategy— so that they comply with international standards that allow data to be shared efficiently.

By developing the FAIR Strategy, Chile will be able to:

* Improve the quality and impact of its research and scientific results;  
* Facilitate interdisciplinary and frontier collaboration;
* Establish itself as a regional leader in data governance, open access, and data ethics;  
* Promote a robust and innovative data ecosystem

It should be noted that Chile is already in a phase of growth and technological transformation. This is evident when reviewing the tasks carried out by the different institutions linked to research, and observing how various local initiatives emerge that aim to safeguard and add value to data. Below are presented some initiatives of interest.

### Data Observatory

The [Data Observatory Foundation](https://dataobservatory.net/) —DO hereinafter— is the outcome of a public private-academic collaboration. It aims to maximize the benefit that can be derived from data for science, research, and productive development. This is achieved through the creation, management, and enrichment of open data platforms that are available to the community. These platforms enable the development of public policies and initiatives with social impact in areas such as climate change, logistics and transport, mining, aquaculture, territorial management, and the prevention of natural disasters, among others. The creation of the DataObservatory facilitates interoperability and access to high-quality data, promoting the reuse of data at the national and international levels. In addition, this initiative supports the training of advanced human capital in data science, aligning with the FAIR principles.

### Proposed Bill on Technology and Knowledge Transfer

Through this initiative, The Government of Chile aims to promote a balanced environment for technology and knowledge transfer, based on the interaction and collaboration of academic and research institutions, government agencies, and industry. This is based on factors that contribute to this process and encourage sustainable development. It is in this area that, through legislation, policies and guidelines are issued to ensure open access to research data, improving their findability, access and reuse.

### datos.gob.cl Portal

The portal [datos.gob.cl](http://datos.gob.cl) is a centralized data repository from public institutions, whose purpose is to make data generated with public funds available to different actors, in open formats and for free use by interested parties. The data can be obtained by downloading it from the platform or by accessing it directly through the API provided by datos.gob.cl. This allows the generation of value such as visualizations, applications, studies, research and services. This initiative provides a centralized point of access to government data, facilitating its discovery, access, interoperability, and reuse by the community.

### Millennium Institute Foundational Research on Data

The [Millennium Institute Foundational Research on Data](https://imfd.cl/) is a joint initiative of the Universidad Católica de Chile and the Universidad de Chile, in which academics from the Universidad Técnica Federico Santa María, Universidad de Concepción, Universidad de Talca, and Universidad Diego Portales also collaborate. This project seeks to address data in all its dimensions—from its origin as a complex computing unit, through the study of storage systems, security, availability, and new query languages, to its use and social impact.

All the initiatives mentioned above **bear witness to the diverse ecosystem in existence and the growth potential** of the FAIR culture within the national territory of Chile.

## 2. The National Need

Considering that efficient data management is essential for transparency and innovation, the need for the FAIR Strategy arises from the demand to properly generate and use data in various areas of society, both for scientific research and for economic and social development, in order to **continue positioning Chile as a regional leader** in Data Governance.

The FAIR principles emphasize the ability to locate or retrieve, access, interoperate and reuse data with no or minimal human intervention, since the use of powerful information processing machines becomes necessary to process large volumes of data. In general, these 4 principles apply to 3 types of entities:

* Data, or any digital object;  
* Metadata, information about that digital object;
* Infrastructure, used for processing those digital objects.

Chile is known for being an “open-air laboratory” due to its particular geography, which facilitates both collaboration and access to data. However, beyond these aspects, efficient management and exchange of data can drive economic growth by fostering data-driven industries, such as artificial intelligence or big data analysis, which are essential for addressing key social challenges in Chile—where mitigating information bias is critical, and the FAIR principles can provide strong support [\[3\]](https://www.sciencedirect.com/science/article/pii/S0167739X24000694). For example, we can point to challenges in public health, environmental concerns, and social inequalities, where better tools would enable informed decision-making and the development of more effective and equitable public policies.

By adopting the FAIR principles and advancing in open data standards, Chile can remain competitive in the globalization of research, and also promote its own scientific community. Sharing data in an open and accessible manner fosters transparency and reproducibility in studies, strengthening the credibility of Chilean research at the global level. This, in turn, supports and facilitates its use by researchers from other countries, which may lead to broader international collaborations and a greater impact of national research.

In this way, the FAIR Strategy will facilitate Chile’s adaptation to the changing global data landscape, by promoting the establishment of quality standards for data management and exchange, the training of advanced human capital in data processing and analytics, the creation of incentives for the publication and use of open data, the encouragement of collaboration between public and private sectors in data-driven projects, and the strengthening of technological infrastructure. 

In Chile, several initiatives underscore the growing need for the FAIR Strategy. For example, the National Artificial Intelligence Policy [\[4\]](https://www.bcn.cl/leychile/navegar?i=1169399&f=2021-12-03), initiatives such as the Conocimiento público platform [\[5\]](https://www.conocimientopublico.cl/), the work of the Secretariat of Digital Government, and the open data policies of the [National Research and Development Agency](https://anid.cl/)—hereinafter ANID— [\[6\]](https://s3.amazonaws.com/documentos.anid.cl/estudios/Politica_acceso_a_informacion_cientifica_2022.pdf), along with their articulation and governance at the international level through the Latin American Network for Open Science (LA Referencia), have contributed to fostering dialogue around the creation of a necessary regulatory framework. This framework should guarantee long-term compliance, provide clarity regarding responsibilities and obligations, and ensure the sustainability of data management practices.

To complement the rationale of the FAIR Strategy, the following key aspects are emphasized:

1. **International alliances and visibility:** A robust national strategy can enhance Chile's visibility and attractiveness as a partner in international research projects and collaborations, strengthening its leadership role.
2. **Regional collaboration and standard-setting:** Chile can lead regional initiatives to standardize data practices, fostering a collaborative data ecosystem in Latin America.
3. **Innovation and Technological Development:** Leading FAIR data practices can stimulate innovation in technologies, such as the development of AI solutions and data services, positioning Chile as a center of technological development in data management.
4. **Impact of policies:** Chile's experience and knowledge in implementing FAIR data practices can serve as a reference for developing data governance policies at the regional level, thereby establishing standards for data management in Latin America.
5. **Economic opportunities:** Leadership in data governance can generate economic opportunities, including the attraction of investment in the technology sector.
6. **Capacity building and knowledge sharing:** By developing expertise in FAIR data principles, Chile can become a hub for training and knowledge exchange in the region, helping to elevate Latin America's competencies.
7. **Good Practice Model:** The implementation of a comprehensive FAIR data strategy can position Chile as a model for other Latin American countries, showcasing best practices in data management.

## 3. Benefits

The benefits of incorporating FAIR principles into data—enabling opportunities for collaboration, interdisciplinary research, and innovation— are inseparable from the training needs of those involved in research and innovation processes. This applies not only within the framework of Open Science but also in the context of responsible research. This is because it facilitates the ability of both individuals and various computational tools to find, access, and reuse data and/or its metadata.

In addition, it should be noted that **the principles serves as guidelines rather than strict rules**, which facilitates their implementation and requires collaborative efforts to address specific contextual challenges [\[7\]](https://dx.doi.org/10.15497/RDA00050). Among the key opportunities presented by the adoption of these principles are: enabling the discovery of data and metadata produced in collaboration with Chilean institutions and researchers; supporting their use and reuse; enhancing their recognition and value; and promoting the adoption of Persistent Identifiers to ensure not only the traceability of data and metadata but also their versioning and validity. The latter is particularly essential in the context of credibility and transparency, as it confirms that the data being used or cited are the same as those originally accessed. In this way, the FAIR principles **provide a robust framework to maximize the value of data** generated and used across all areas of research, innovation and policy-making—beyond both public and private spheres.

Along with the above, it can facilitate the integration and collaboration of initiatives stemming from the National Policy on Science, Technology, Knowledge and Innovation [\[8\]](https://minciencia.gob.cl/politicactci/documentos/Politica-Nacional-CTCi_Chile-2020.pdf), the Bill on Technology and Knowledge Transfer [\[9\]](https://www.camara.cl/legislacion/ProyectosDeLey/tramitacion.aspx?prmID=17258&prmBOLETIN=16686-19), and also strenghten the implementation of the ANID Open Access Policy [\[6\]](https://s3.amazonaws.com/documentos.anid.cl/estudios/Politica_acceso_a_informacion_cientifica_2022.pdf). In a strategic context, the following benefits can be highlighted:

* **Improvement of Quality and Efficiency in Research and Development:** The application of the FAIR principles promotes greater efficiency and effectiveness in research by facilitating access to and reuse of data and metadata across disciplines and sectors. This results in reduced duplication of efforts and accelerates the scientific discovery process [\[1\]](https://www.nature.com/articles/sdata201618). It recognizes data management as a continuous process throughout the research project, requiring ongoing planning and documentation in a data management plan. This approach facilitates and complements the scope of the national science and technology system’s data management plan, as well as those developed by individual institutions. This implies a commitment to capacity building and training aimed at researchers, data specialists, and project managers, with the goal of fostering a deep understanding and application of the FAIR principles—thus complementing existing data management plans at both national and institutional levels.

* **Fostering Open Innovation:** The FAIR Strategy fosters an open innovation ecosystem by making data and metadata more accessible and reusable—not only for the scientific community, but also for the private sector and the general public. This is particularly relevant for driving innovative solutions in response to social and economic challenges, in alignment with public calls, such as the Open Innovation Program that connects science and technology [\[10\]](https://www.gob.cl/noticias/desafios-publicos-minciencia-y-corfo-lanzan-el-primer-programa-de-innovacion-abierta-que-vincula-ciencia-y-tecnologia/), as well as with agreements like the one between the Ministry of National Defense and the Ministry of Science, Technology, Knowledge and Innovation [\[11\]](https://www.gob.cl/noticias/ministerios-de-defensa-y-ciencia-firman-convenio-para-fomentar-la-investigacion-y-la-innovacion-en-ciencia-y-tecnologia/).

* **Promotion of Intersectoral Collaboration:** By promoting the interoperability of data and metadata, the FAIR principles facilitate intersectoral collaboration, allowing different actors—academia, industry, government—to work jointly on research and development projects, thereby strengthening collaborative innovation efforts. This would help ensure equitable access to the technical resources required for the implementation of FAIR, in alignment with the Action Plan of the National Policy on Science, Technology, Knowledge and Innovation [\[12\]](https://minciencia.gob.cl/politicactci/documentos/Politica-Nacional-CTCI_Plan_Accion_Chile_2020.pdf) and with the challenges outlined by the Government Laboratory in its publication *Allowed to Innovate: How can we develop data science projects to innovate in the public sector?* [\[13\]](https://www.lab.gob.cl/permitido-innovar).
  
* **Increasing Transparency and Trust in Science:** Implementing data management practices that adhere to the FAIR principles increases the transparency of research processes and strengthens public trust in science by enabling the verification and replication of scientific results [\[14\]](https://observa.minciencia.gob.cl/encuesta/encuesta-nacional-de-percepcion-social-de-la-ctci).

* **Contribution to Sustainable Development:** The accessibility and reuse of data and metadata in accordance with the FAIR principles support efforts to address the Sustainable Development Goals (SDGs) by providing a foundation for the analysis of research outputs, thereby promoting their use in evidence-informed decision-making in critical areas such as climate change, health, and social equality.

* **International Strategic Positioning:** By aligning its data management strategy with the FAIR principles, Chile is strategically positioned on the international stage as a leader in the adopting open and reusable data practices, thereby favoring its integration into global research and innovation networks. In turn, this facilitates collaboration with international initiatives such as the European Open Science Cloud (EOSC) and the EU Open Data Directive.

* **Development of Open Educational Resources:** A strategy to centralise guide, best practices, recommended tools, and case studies on data management will be implemented. These resources will strengthen access to vital information for the implementation of the FAIR principles, promoting knowledge sharing and standardization of data management practices at the national level.

* **Ethical Reuse and Secure Accessibility:** Responsible AI Licenses (RAIL) are a set of licenses designed to promote the open use of artificial intelligence by establishing restrictions to guarantee ethical and responsible applications, while preventing uses that could be harmful to society.

## 4. Stakeholders

Stakeholders are individuals, groups, or organizations with an interest in the development, implementation, and outcomes of the FAIR Strategy. Their participation is crucial to ensure the project’s success, as they contribute resources, knowledge, and support. Within Chile's open ecosystem, these stakeholders encompass entities from the public, private, and mixed sectors, whose objectives and activities are publicly accessible and actively promote the access, use and reuse of open data.

### Classification according to strategy

#### Public Sector

* Scope: This sector includes government institutions involved in public policy, regulation, and promotion of access to open data.  
* Actions: Develop open data policies, regulate access to and use of data, and promote transparency and citizen participation.

#### Private Sector

* Scope: Includes companies and consortia that generate, manage or use data to improve their products and services, and that are committed to social responsibility and transparency.
* Actions: Innovate in products and services based on open data, promote corporate social responsibility, and contribute to economic development through the use of data.

#### Cross Sector

* Scope: Includes universities, research centers, and NGOs that collaborate with public and private sectors to advance open data research, education, and policy development.
* Actions: Support open research and education, foster interdisciplinary collaboration, and promote inclusion and equitable access to data.

### Stakeholders Roles in relation to Data/Metadata

* **Generation:** Production of open, high-quality data.  
* **Use:** Application of open data across various domains for the development of products, services and policies.  
* **Research:** Study and analysis of open data to advance knowledge and foster innovation.  
* **Regulation:** Definition of policies, norms, and standards for the management and use of open data.  
* **Implementation:** Execution of projects and strategies for the integration and utilization of open data across multiple sectors.  
* **Innovation:** Development of new technologies, methods, and practices based on open data to enhance processes and solutions in diverse sectors.

### Main Stakeholders Identified

| Organizations | Classification according to strategy | Role |
| :---- | :---- | :---- |
| Network of Centers / UC Data Science Initiative | Cross sector | Generation; Use; Research |
| Millennium Institute Foundational Research on Data \- IMFD | Cross sector | Generation; Use; Research |
| Chilean Geospatial Data Infrastructure \- IDE Chile | Public sector | Generation; Use; Research |
| National Institute of Statistics \- INE | Public sector | Generation; Use; Research |
| National Research and Development Agency \- ANID  | Public sector | Generation; Use; Implementation |
| Ministry of Economy, Development and Tourism \- MinEcon | Public sector | Generation; Use; Regulation |
| Ministry of Science, Technology, Knowledge and Innovation \- MinCyT | Public sector | Generation; Use; Regulation |
| Ministry of Health \- MinSal | Public sector | Generation; Use; Regulation |
| Consejo Nacional de Ciencia, Tecnología, Conocimiento e Innovación para el Desarrollo \- Consejo CTCI | Cross sector | Generation; Use; Research |
| GOFair US | Cross sector | Generation; Use; Research |
| Ministry of Education \- MinEduc | Public sector | Generation; Use; Regulation |
| National Access Infrastructure Support Network \- INA | Public sector | Regulation |
| Research Center for Integrated Disaster Risk Management \- CIGIDEN | Cross sector | Generation; Use; Research |
| National Accreditation Commission \- CNA | Public sector | Generation; Use; Regulation |
| General Secretariat of Digital Government \- SGD | Public sector | Generation; Use; Regulation |
| Chilean Association of Information Technology Companies \-  ACTI | Private sector | Generation; Use; Implementation; Innovation |
| Factory Development Society \- SOFOFA | Private sector | Generation; Use; Implementation; Innovation |
| Center for Climate Science and Resilience \- CR2 | Cross sector | Generation; Use; Research |

In addition, at the national level, there are multiple examples of prominent institutions engaged in data publication:

* Chilean Meteorological Directorate  
* Institute for Disaster Resilience (ITREND)  
* Ministry of Finance  
* Ministry of the Environment  
* Ministry of the General Secretariat of the Presidency

## 5. Gaps

In the daily work of researchers, the need to advance toward the safe and effective reuse of open science research outputs is evident. In practice, several gaps have been identified that must be addressed in order to implement the FAIR principles in our country, thereby contributing to the development of a democratic and accessible knowledge ecosystem for the entire community. These gaps give rise to needs that must be met, including the development of common policies, guidelines, and standards to facilitate access, discovery, and reuse of research results, as well as the cultural shift required by this new approach.

### Cultural Change

Implementing a model that transitions toward Open Data is not an easy task; however, currently it is becoming increasingly necessary. By publishing their data, researchers will not only strengthen their own work, but also will be able to contribute to the country’s development, thereby promoting a more equitable and sustainable development for society as a whole.

As Pedro Bouchon,Vice-Rector for Research at the Pontificia Universidad Católica de Chile (2024) notes in an [interview](https://cienciaabierta.uc.cl/testimonios/vicerrector-de-investigacion/): "The shift toward Open Science is, like all large-scale cultural changes, a complex process that—if it is to deliver its justified benefits—must address the tensions, resistances, and ecosystem adjustments within our institution. That is why the change must be gradual and progressive, with the involvement of all relevant sectors and with a cross-cutting perspective that enables us to anticipate the challenges that may arise during its implementation.

### Recognitions and Incentives

**Academic recognition:** Open research is valued and acknowledged in academic evaluation processes, such as promotions and career advancement. This may include considering open research practices in the assessment research quality and impact, as well as in the evaluation of researcher's contribution to the scientific community.

**Traditional metrics vs. quality metrics:** Currently, researchers are expected to demonstrate the impact of their work, which is typically measured through traditional metrics such as the journal impact factor. To successfully transition to the open data model, it is necessary to complement these measures by incorporating new academic evaluation criteria. Shifting the assessment of science from reliance on impact factors toward an emphasis of research quality is essential for promoting a fairer and more rigorous system.

Evaluation should focus on the intrinsic quality of the research, rather than depending solely on quantitative metrics such as the impact factors of a journal. It should consider aspects such as originality, relevance, methodological rigor, transparency and the actual impact on both the scientific community and society. This more holistic approach not only recognizes the diversity of scientific research but also fosters a more inclusive, collaborative, and knowledge-driven academic culture.

### Governmental and Institutional Funding for Open Research

The design of public policies that ensure access to publications produced with public funds is currently a key issue on the agenda of organizations that fund science, technology, knowledge, and innovation (STI) activities. Funding agencies—both public and private—are expected to provide targeted funding for research projects that adopt open practices. This may include additional resources to cover the costs associated with publishing open access articles, hosting data in open access repositories, and developing open research infrastructure. In addition, this has the positive externality of promoting Open Innovation.

### Growth and Projection of a National Research Network

The document published in 2024 by the Sub Directorate of Networks, Strategy and Knowledge of ANID, in collaboration with the Technical Advisory Committee of the National Access Infrastructure Support Network (INA), titled *Metadata Guidelines and Interoperability Mechanisms*, represents the first step towards the creation of a National Access Node. Therefore, it is necessary to optimize this national research system/node to enable Chilean research to be projected internationally as a joint effort, rather than relying on the individual capacities of each institution.

#### Training and Support

Training and support programs are needed for researchers, librarians, IT teams and civil society, who wish to adopt open research practices. These programs may include workshops, online resources, and personalized guidance on how to share data ethically and effectively, publish in open access journals, and comply with open access policy requirements. As a first step to achieve this, it is essential to develop a “train-the-trainer” program to prepare professionals as data stewards. Additionally, these topics should be incorporated into undergraduate curricula in Schools of Library Science and other related fields of professional education.

#### Data Fragmentation

Currently, data in laboratories and institutions are often dispersed across various platforms, including general-purpose and thematic repositories. Some disciplines lack dedicated repositories, and data are presented in different formats, which complicates their discovery, access, reproducibility, reuse and interoperability. The absence of standardised metadata and the inconsistent organization of data hinder the discoverability and effective reuse.

#### Interoperability Issues

Incompatibility between different software systems, tools, and formats hinders data integration and interoperability. The lack of standardized data models,ontologies, and controlled vocabularies obstructs the exchange and integration of FAIR data across disciplines and research domains. This issue could be significantly improved if standards were agreed upon across different disciplines and contexts, regardless of the existing fragmentation in national repositories. Currently, the document *Metadata Guidelines and Interoperability Mechanisms*, published by the Subdirectorate of Networks, Strategy and Knowledge of ANID, in collaboration with the Technical Advisory Committee of the National Access Infrastructure Support Network ([INA](https://acceso-abierto.anid.cl/comites_tecnicos_asesores_ina/)), establishes key [guidelines for the use of metadata and interoperability in open infrastructures](https://acceso-abierto.anid.cl/wp-content/uploads/sites/4/2024/05/Metadatos_para_la_Interoperabilidad_de_los_Repositorios_2024.pdf).

#### Limited Accessibility

Access to data is often restricted due to concerns about ownership or privacy, resulting in limited availability and hindering collaboration and reproducibility.
Legal and ethical considerations—along with concerns about security, confidentiality and intellectual property—pose barriers that could be mitigated by adopting the FAIR principles and promoting open data sharing.

#### Data Quality and Lack of Documentation

Inadequate documentation, incomplete metadata, and inconsistent data formats negatively affect the quality and reliability of data. Poor documentation makes it difficult to understand the context in which the data were generated, complicating their validation and interpretation. Incorporating Machine Learning tools to assist data creators or custodians could help streamline, enhance and improve this process.

#### Infrastructure and Resources

Some institutions lack the necessary infrastructure, resources, and technical expertise to implement effective data management practices in accordance with the FAIR principles. This includes challenges related to data storage, backup, curation, and long-term preservation.

## 6. Components to Reduce Gaps

The implementation of the FAIR principles is a comprehensive process involving multiple levels: data management culture, training in FAIR principles, and the necessary technological requirements to build a FAIR ecosystem. According to the GO FAIR initiative, these three pillars help bridge national gaps and needs, enabling the transition to a FAIR data system. This chapter highlights the importance of FAIR policy and capacity building in these principles as key elements on the path toward a FAIR-aligned system.

### Institutional Support to the FAIR Strategy

In order to develop a FAIR Strategy that responds to Chile's needs, it’s essential that ANID and the Ministry of Science, Technology, Knowledge andInnovation (MinCyT) establish an official FAIR agenda. The transformation ofChile into a country with a FAIR ecosystem requires a plan that integrates technical, political, and specific financing aspects to guarantee its implementation. An official FAIR policy in Chile would enable the inclusion of more actors in society in this transformation process effectively. Likewise, a nationalFAIR agenda would enhance the benefits of having FAIR systems and data by promoting, recognizing, and supporting various organizations in the implementation of these principles.

### How FAIR will meet the needs in Chile

The chapter on gaps outlines the key areas where Chile can leverageopportunities to progress toward the FAIR principles. The following paragraphs detail how the GO FAIR initiative can facilitate this process.

#### FAIR Agenda Priority: Training and Capacity Building

##### Who is the training aimed at?

For the maintenance and development of the FAIR ecosystem, training people in various roles will be necessary. Officials and representatives need to understand the FAIR principles at the strategic level, while key actors in universities, research centers, and companies can benefit from understanding the advantages and applications of these principles in their organizations. Data professionals, known as data stewards, must receive adequate training.Finally, it is recommended to train system administrators, engineers, and IT developers in the technical aspects of FAIR data.

##### The Different Training Formats in FAIR

Based on the experience of GO FAIR US, it is recommended to develop specific training plans tailored to these key roles, including securing their funding. While the creation of systems and infrastructure for data management requires targeted support at the time of implementation, training will need continuous funding, as there will always be a need to train new data stewards or update the skills of existing ones, especially in the FAIR systems that are being developed.

Therefore, it is recommended to allocate funds for FAIR education and training. With financial support, FAIR Chile could implement the following educational initiatives, based on GO TRAIN, the second pillar of the GO FAIR framework:

* **Training in the FAIR agenda:** Provides a comprehensive overview of the potential of the FAIR principles, the development of FAIR policies and their key points. This training is aimed at stakeholders, intermediaries and decision-makers from various fields in both public and private sectors.  
* **Data stewardship training:** Training to perform the role of data steward or curator of scientific data in universities, research centers, or other public and private entities.  
* **FAIR training in research:** For researchers, focused on providing the knowledge and tools to design a research workflow oriented towards the FAIR principles at all stages of scientific research.  
* **Workshops:** Focused on tools and technical knowledge for IT teams. Workshops can be training sessions or more collaborative formats, such as joint programming sessions.

#### Institutional and Governmental Funding for Open Research

Since 2022, the National Research and Development Agency (ANID) has required open access obligations for projects that produce scientific results and indicate this requirement in their terms. It is recommended to continue developing a public funding policy that promotes the application of FAIR principles in research processes, taking into account the different types of scientific outputs across all phases of the research cycle.

Likewise, the current policy is aligned with the principles of open science, incorporating the FAIR principles. To date, ANID has published two key documents: the *"Policy on Open Access to Scientific Information and Research Data Funded by ANID’s Public Resources"* and the *"Guidelines on Metadata and Interoperability Mechanisms"* (NationalResearch and Development Agency \[ANID\], 2022; 2024). Although these documents address important aspects such as open access and interoperability, they do not explicitly reference other FAIR data principles, such as data reuse or data findability.

In addition, the Data Observatory entity promotes the development of open data in Chile, aiming to "maximize the benefit that can be obtained from data for science, research, and productive development, through the creation, management, and enrichment of open data platforms \[...\]" (*Data Observatory*, n.d.). It is recommended to involve other institutions and stakeholders with extensive experience—such as the DataObservatory—in the development of regulations.

#### Cultural Change: the academic sector

It is essential to include "all relevant stakeholders at all levels" of the academic sector within this process (*GO FAIR Initiative*, n.d.).

Since 2022, several Chilean universities have been implementing open science cultures through **InES Open Science** projects funded by ANID. In these projects, cultural change is effected through internal training, the implementation of repositories for publications and data, changes in universities’ policies regarding open science, and the creation of national and international networks. Several InES projects have succeeded in proposing open science policies; however, these remain nonbinding. It is recommended to strengthen and sustain these efforts in universities, as ANID funding support ends when a project concludes. Frequently, the units responsible for InES projects receive no further support from their universities, limiting their ability to promote academic culture beyond the initial scope of the project.

Although cultural changes induced by university projects have mostly emerged from bottom-up initiatives, it is recommended to complement and encourage topdown transformations. The **National Accreditation Commission (CNA)** of Chile evaluates and accredits the quality of higher education institutions under the Ministry of Education. It is recommended to incorporate the FAIR principles into the CNA's criteria and indicators. This inclusion would allow for the recognition of the FAIR principles in university policies regarding data, data management, and research. Furthermore, universities could be incentivized to adopt the culture of open science.

#### Growth and Projection of a National Research Network

As part of the creation of a research network at the national level, it is recommended to promote and expand the **Chile Node** (an initiative led by ANID), along with its connection to global scientific data networks, such as the European Science Cloud. In Chile, it is also recommended to overcome the isolation of scientific data stored in large silos by fostering a national connection that, through the Chile Node, facilitates the integration of Chilean databases with global networks—both for sharing and receiving information.

#### Data Fragmentation and Interoperability Issues

To address data fragmentation and interoperability issues, it is recommended to develop **interoperable repositories** using formats and standards that enable the exchange, findability, access, and reuse of data. In addition, it is advisable to continuously review **metadata standards**, ensuring that the metadata stored in the repositories of the **Chile Node** are updated and maintained in a way that guarantees compatibility with global systems.

Based on the above, it is proposed to develop standardized data models, as well as ontologies and controlled vocabularies, to facilitate the exchange and integration of FAIR data across different disciplines and research areas.

#### Data Quality and Lack of Documentation

Low data quality and the absence of metadata or proper documentation continue to be persistent issues in Chile. These problems reflect the lack of robust data policies in both public and private organizations, including the absence of a **national data governance policy**. It is recommended to establish clear regulations on data governance and data security at the national level to support institutional policies and ensure the proper handling and improvement of data quality.

Backed by national laws and guidelines, this would facilitate the promotion and implementation of institutional policies in both the public and private sectors,including the funding of key positions such as data governance officers, data curators, and other specialists. Large public entities—such as universities—which manage significant volumes of data, some of it sensitive, should have a well-defined data policy and dedicated professionals to ensure its effective implementation.

#### Limited Accessibility

Similarly, limited data accessibility requires different measures depending on the underlying reasons:

* **Concerns regarding data ownership:** It is important to clarify institutional policies related to data ownership. To achieve this, clear agreements must be developed regarding data usage across the different organizations that manage and utilize it. In the case of universities, this means establishing guidelines that clearly define who owns the research data and at what stage.
* **Concerns regarding privacy:** To ensure proper data management, it is essential to work closely with ethics committees to guarantee that each dataset is published as openly as possible, but as restricted as necessary—that is,published at the highest permissible level of openness, while applying the necessary restrictions to protect privacy. Furthermore, all data should be accompanied by the appropriate licence that clearly specifies the terms of use and reuse. For organizations or institutions uncertain about the potential impact of data on individual privacy, it is recommended to carry out privacy impact assessments to mitigate possible risks.
* **Concerns regarding data security:** It is necessary to develop open-access repositories that offer strong protection against attacks and fraud, are regularly maintained, and are subject to continuous audits and monitoring. In this regard,there are certified repositories with various security seals, and it is recommended that Chile adopts and use these same certifications.

The implementation of the FAIR principles is an ongoing process that requires a multidisciplinary and collaborative approach. Proactively addressing concerns about ownership, privacy, and security—alongside fostering an institutional culture that values openness and transparency—are key steps toward the effective implementation of the FAIR principles.

### GO FAIR Chile Office

#### The GO FAIR International Initiative

GO FAIR is a self-governed international initiative aimed at implementing the FAIR data principles. It is based on national communities of experts and stakeholders,known as implementation networks , which are responsible for defining and creating FAIR-related materials and tools in their respective countries. Given the highly flexible structure of GO FAIR, the model can also be adapted to the Chilean context, with strategic support from the GO FAIR US office for the Americas region.

These implementation networks are supported by National Support Offices,which serve as the most concrete representation of GO FAIR in each country. The purpose of these offices is to:

>*"recognize and support the principles that form the basis of the GO FAIR Initiative of independent yet coordinated implementation networks"* (GO FAIR, n.d.).

The National Support Offices ensure the participation of all relevant stakeholders at the national level and coordinate the initiative’s organization. Additionally, they maintain close coordination with the International Support and Coordination Offices, currently based in Leiden (Netherlands), Hamburg (Germany), and Paris (France). Besides these, the GO FAIR US Office in San Diego promotes coordination with national GO FAIR initiatives throughout theAmericas.

While the International Support and Coordination Office offers planning support to the National Support Offices, it does not provide financial assistance. Each office is responsible for its own funding and remains independent from for-profit organizations, although they may be physically hosted by other institutions. These offices work in close collaboration with national authorities to implement the FAIR principles.

#### The National Support Office in Chile

It is recommended to establish and support a National Support Office in Chile.The GO FAIR Chile office will connect all relevant stakeholders with the universities and institutions that are part of the national FAIR network, advancing the integration of the FAIR principles into research practices. It will facilitate the exchange of best practices among ANID, universities, research centers and communities, as well as public and private research funding organizations, with the Ministry of Science, Technology, Knowledge and Innovation as a facilitator. In addition, the office will coordinate training and capacity-building activities related to the FAIR principles.

The establishment of such an office would contribute to building a FAIR community in Chile, to working toward a clearnational directive for the FAIR ecosystem, and to coordinating both nationally and internationally with stakeholders, International Support and Coordination Offices,along with government authorities to develop a robust FAIR ecosystem in the country.

The GO FAIR office would provide substantial support to accelerate science and innovation in Chile, reduce research-related costs, and improve the return on investment for tax payers. Moreover, Chile could become the first Spanish-speaking nation worldwide to host a National Support Office within the GO FAIR initiative, joining the leading countries in the global FAIR Movement.

The first step following the launch of this Strategy will be the creation of multidisciplinary working groups to define the action plan and its follow-up.

### Dissemination

The dissemination strategy for implementing the FAIR principles in Chile must be articulated across three complementary levels: institutional, educational, and technical-cultural. At the institutional level, it is essential to position the FAIR initiative as an official national policy supported by ANID and the Ministry of Science, Technology, Knowledge and Innovation. This can be achieved through formal government communication channels, inter-ministerial events, and digital campaigns that emphasize how this transformation will benefit the national data ecosystem—and in particular, Chilean scientists. This effort should include informational webinars for decision-makers, strategic position papers, and the promotion of national and international success stories that showcase the return on investment for those who participate.

In the educational sphere, dissemination efforts will focus on tailored training programs according to the target audience: strategic sessions for university leaders, research centers, civil society, and government entities; hands-on workshops for data stewards; and training modules for researchers and technical teams. These programs will be delivered through existing academic networks, national educational platforms, partnerships with InES Open Science projects, and communications from participating government entities. A centralized repository of educational resources—including guides, infographics, and video tutorials adapted to the Chilean context—will highlight the tangible benefits of FAIR principles for each audience segment.

The third level will address technical-cultural change through a communication strategy that fosters communities of practice, interdisciplinary working groups, and participatory events that encourage collaboration across sectors. This will be complemented by the dissemination of technical standards, best practices, and tools for the implementation of interoperable repositories—highlighting Chile’s potential to become the first Spanish-speaking country to host a GO FAIR National Office. The strategy will include regular newsletters, a presence on specialized social networks, and a program of FAIR ambassadors and data stewards who act as knowledge multipliers within their respective institutions. This will contribute to the creation of a national movement towards the digital transformation of Chile’s data ecosystem.

Dissemination should be a cross-cutting activity that fosters a culture of open data and promotes collaboration among institutions, researchers, and civil society. In this regard, it is recommended to establish strategic alliances with the media and academic networks to amplify the impact of FAIR initiatives in Chile.

## 7. Successful FAIR Cases in Chile

To introduce this section, some governance initiatives at the national and local levels are listed. Then, specific success stories in Chile are detailed.

### Governance Initiatives at the National Level

* Policy on open access to scientific information and publicly funded research data [\[6\]](https://s3.amazonaws.com/documentos.anid.cl/estudios/Politica_acceso_a_informacion_cientifica_2022.pdf);  
* Data Management Plan, National Research and Development Agency ANID (2023) [\[15\]](https://www.cincel.cl/documentos/PGD_20220506.pdf);  
* Metadata Guidelines and Interoperability Mechanisms; National Research and Development Agency ANID & Technical Advisory Committee of the National Access Infrastructure Support Network (INA) (2024) [\[16\]](https://acceso-abierto.anid.cl/wp-content/uploads/sites/4/2024/05/Metadatos_para_la_Interoperabilidad_de_los_Repositorios_2024.pdf);  
* 27 Innovation Projects in Higher Education, Open Science (National Research and Development Agency \[ANID\], n.d.) [\[26\]](https://acceso-abierto.anid.cl/componentes/inescienciaabierta/).

### Governance Initiatives at the Regional Level

* LA Referencia support for national Open Science strategies in Latin America and Spain (LA Referencia, n.d.) [\[27\]](https://www.lareferencia.info/es/).

### Governance Initiatives at the Local Level

* Open Science Policy of the Universidad Central de Chile. Universidad Central de Chile (2023) [\[17\]](http://doi.org/10.5281/ZENODO.10204585);  
* Declaration of Metadata Interoperability of the Institutional Repository of the Universidad Central de Chile (2024) [\[18\]](http://doi.org/10.5281/ZENODO.10523136);  
* Template for the Data Management Plan of the Universidad Central de Chile (2023) [\[19\]](http://doi.org/10.5281/ZENODO.10067320);  
* Data Management Plan of the Universidad Católica de la Santísima Concepción (2023) [\[20\]](https://cienciaabierta.ucsc.cl/wp-content/uploads/sites/157/2023/11/Formato-Plan-de-Gestion-de-Datos-UCSC.docx);  
* Institutional Open Science Policy of the Universidad Católica de la Santísima Concepción (2023) [\[21\]](https://cienciaabierta.ucsc.cl/wp-content/uploads/sites/157/2023/08/D.R._108_2023_PROMULGA_ACUERDO_DEL_HCS_QUE_APRUEBA_POLITICA_DE_CIENCIA_ABIERTA_DE_LA_UCSC-2.pdf);  
* Open Science Policy of the Universidad del Desarrollo (2023) [\[22\]](https://www.udd.cl/wp-content/uploads/2022/08/dr-nro144-23-politica-ciencia-abierta-udd-timbrado.pdf).

### Assessment of National Repositories and Data Management Plans

The InES Open Science project of the Universidad Central de Chile, funded by ANID, generated a series of documents that lay the foundations for the development of open research data management. First, an Open Science Policy was enacted, establishing the areas of action, promotion, and support for the academic community to begin recognizing and integrating open science practices—particularly by fostering the promotion of the FAIR principles for research data. The policy mandates the completion of a data management plan for all research conducted at the university, as well as the deposit of research data in the new Institutional Repository.

Additionally, the university publicly released its Declaration of Metadata Interoperability for the Institutional Repository, enabling other repositories to extract data—an uncommon practice, according to the study conducted by Hartley and Abedrapo [\[23\]](https://doi.org/10.5281/ZENODO.10557407).

Finally, the implementation of the National Data Center Plan (PDATA) [\[24\]](https://minciencia.gob.cl/uploads/filer_public/95/6b/956b8c9f-d937-4b4d-8f6c-a871495a52ff/plan_nacional_de_data_centers_pdata.pdf) in Chile presents an opportunity to access advanced digital infrastructure that can significantly enhance data management and storage. By integrating both existing and future repositories with the PDATA data centers, it would be possible to ensure greater efficiency in the processing and safeguarding of information.This synergy not only optimizes data access and interoperability but also promotes collaboration among academic institutions, civil society, government, and data centers,thereby strengthening the country’s research and development ecosystem. Moreover, by aligning with the PDATA's sustainability policies, the growth of digital infrastructure is ensured to be environmentally responsible and respectful of local communities.

### Availability of Scientific Data from Research Stations

The Network of Regional Centers and Stations of the Universidad Católica ([RCER](https://www.uc.cl/unidades-academicas/red-de-centros-y-estaciones-regionales-rcer-uc/)) seeks to support interdisciplinary research by university researchers through a network of centers and stations where research activities,undergraduate and postgraduate teaching, and interaction with the most relevant ecosystems of the country take place. The project, led by the Data Science Initiative of the Universidad Católica (UC),has as its main objective to make data available to support scientific development and maximize the use of information to generate more knowledge and impact. The initiative aims to make relevant data accessible, fostering interdisciplinary research and promoting solutions to local and global problems. Making data available is crucial for driving scientific development, as it enables researchers and academics to explore new areas of knowledge, validate previous studies, and develop innovations that can significantly impact various disciplines.Furthermore, it facilitates collaboration and information sharing among researchers, which can lead to faster and more efficient discoveries. Openly publishing data promotes transparency in research and allows the reproducibility of studies, thereby strengthening trust in scientific results.

The project faces several challenges, such as data governance, which involves implementing clear policies to ensure data quality, security and privacy, and establishing regulations on who can access data and under what conditions.Ethical and responsibility-related issues are also addressed, ensuring that data is managed ethically, protecting individual’s privacy, and respecting legal and ethical standards. Another challenge is to promoting interoperability—enabling data to be easily shared and used across different systems and platforms through the use of common standards.

This effort is strategically connected to the opening of a GO FAIR office in Chile, a global initiative that promotes the implementation of FAIR principles in scientific data management. The GO FAIR office in Chile will help strengthen the country's data infrastructure by promoting best practices in data management and facilitating international collaboration.

### Building the Foundations of Open Science at the Pontificia Universidad Católica de Chile

ChileIn 2021, the Pontificia Universidad Católica de Chile was awarded the execution of the project *"Building the foundations of open science at the PontificiaUniversidad Católica de Chile"*, funded by ANID. The goal of this project was to establish and/or strengthen capacities in the open management of publications and scientific data at the UC. Specifically, it aimed to develop an institutional open science ecosystem thatencompassed operational models, participation of people, publication of research outputs, data management, and the implementation of a standardized, open,independent and interoperable technological infrastructure with services and applications in accordance with ANID's open access policies and international standards.

The project was structured around four main pillars: Governance and Policies,Infrastructure and Services, Training and Capacity Building, and Dissemination and Networks. Among the documents produced are:

* Guidelines on interoperability policies between systems and projects,
* Guidelines for dissemination and continuous training in the field of OpenScience,  
* Guidelines for the application of Creative Commons licenses to research outputs, and Guidelines on the Digital Preservation Policy of the UC [\[24\]](https://doi.org/10.7764/InESCA.UC.l06).

## 8. Integrated Strategy for the Implementation of FAIR

This chapter presents an operational strategy that transforms the components identified in the document into concrete actions to achieve a robust FAIR data policy.

### Governance and Coordination

The creation of a National FAIR Implementation Network (GO FAIR) is proposed. This network would bring together the Ministry of Science,Technology, Knowledge and Innovation, the National Research and Development Agency(ANID), universities, research centers, companies, data startups, and representatives of civil society. The network will facilitate inter-institutional coordination and collaboration in strategic decision-making. In addition, the GO FAIR Office is established as the central hub to articulate and execute the strategy.

### Infrastructure and Standards

Develop a data infrastructure that allows interoperability among current repositories through the adoption of persistent identifiers (such as DOI,ORCID, etc.) and standardized metadata aligned with the FAIR principles.This will provide the technical foundation for integrating different components and ensuring an efficient and accessible flow of data.

### Training and Capacity Building

Implement a national training program on open science and FAIR data,offering courses and workshops on standards, data management,interoperability, and data ethics. This initiative will strengthen digital competencies within universities and organizations, promoting the FAIR dataculture.

### Regulatory Framework, Financing and Evaluation

Adapt the current regulatory framework to align with data protection laws and other relevant regulations. Establish competitive funding mechanisms and promote public-private partnerships to ensure the sustainability of the infrastructure. Finally, design a monitoring and evaluation system to measure impact and allow for dynamic adjustments to the strategy.

This comprehensive proposal aims to integrate the identified components, providing the qualitative leap necessary for the successful implementation of the FAIR data policy in Chile.

## 9. Bibliography

\[1\] M. D. Wilkinson et al., "The FAIR Guiding Principles for scientific data management and stewardship”, Sci. Data, vol. 3, no 1, p. 160018, mar. 2016, doi: [10.1038/sdata.2016.18](https://www.nature.com/articles/sdata201618).

\[2\] I. Pan, L. R. Mason, y O. K. Matar, "Data-centric Engineering: integrating simulation, machine learning and statistics. Challenges and opportunities”, Chem. Eng. Sci., vol. 249, p. 117271, 2022\. [10.1016/j.ces.2021.117271](https://doi.org/10.1016/j.ces.2021.117271).

\[3\] R. González-Sendino, E. Serrano, y J. Bajo, "Mitigating bias in artificial intelligence: Fair data generation via causal models for transparent and explainable decision-making”, Future Gener. Comput. Syst., vol. 155, pp. 384–401, jun. 2024, doi: [10.1016/j.future.2024.02.023](https://www.sciencedirect.com/science/article/pii/S0167739X24000694).

\[4\] Biblioteca Nacional del Congreso, "Decreto 20 Aprueba Política Nacional de Inteligencia Artificial”, [www.bcn.cl/leychile](http://www.bcn.cl/leychile). Accedido: 31 de mayo de 2024\. \[En línea\]. Disponible en: [https://www.bcn.cl/leychile/navegar?i=1169399\&f=2021-12-03](https://www.bcn.cl/leychile/navegar?i=1169399&f=2021-12-03).

\[5\] Transformación Pública y Prodigio Lab, "Portal \- Conocimiento Público”, Conocimiento Público. Accedido: 31 de mayo de 2024\. \[En línea\]. Disponible en: [https://www.conocimientopublico.cl/](https://www.conocimientopublico.cl/).

\[6\] Agencia Nacional de Investigación y Desarrollo (ANID), "Política de acceso abierto a la información científica y a datos de investigación financiados con fondos públicos de la ANID”. Gobierno de Chile, 2022\. Accedido: 21 de junio de 2023\. \[En línea\]. Disponible en: [https://s3.amazonaws.com/documentos.anid.cl/estudios/Politica\_acceso\_a\_informacion\_cientifica\_2022.pdf](https://s3.amazonaws.com/documentos.anid.cl/estudios/Politica_acceso_a_informacion_cientifica_2022.pdf)

\[7\] Research Data Alliance FAIR Data Maturity Model Working Group, "FAIR Data Maturity Model: specification and guidelines”, 2020, doi: [10.15497/RDA00050](https://dx.doi.org/10.15497/RDA00050).

\[8\] Ministerio de Ciencia, Tecnología, Conocimiento e Innovación de Chile, "Política Nacional de Ciencia, Tecnología, Conocimiento e Innovación”. 2020\. Accedido: 17 de mayo de 2024\. \[En línea\]. Disponible en: [https://minciencia.gob.cl/politicactci/documentos/Politica-Nacional-CTCi\_Chile-2020.pdf](https://minciencia.gob.cl/politicactci/documentos/Politica-Nacional-CTCi_Chile-2020.pdf)

\[9\] Ministerio de Ciencia, Tecnología, Ciencia e Innovación; Ministerio de Economía, Fomento y Turismo; Ministerio de Educación, "Proyecto de Ley: Dicta normas sobre transferencia de tecnología y conocimiento”. 4 de enero de 2024\. Accedido: 17 de mayo de 2024\. \[En línea\]. Disponible en: [https://www.camara.cl/legislacion/ProyectosDeLey/tramitacion.aspx?prmID=17258\&prmBOLETIN=16686-19](https://www.camara.cl/legislacion/ProyectosDeLey/tramitacion.aspx?prmID=17258&prmBOLETIN=16686-19)

\[10\] Gobierno de Chile, "Desafíos Públicos: MinCiencia y Corfo lanzan el primer programa de innovación abierta que vincula ciencia y tecnología \- Gob.cl”, Gobierno de Chile. Accedido: 17 de mayo de 2024\. \[En línea\]. Disponible en: [https://www.gob.cl/noticias/desafios-publicos-minciencia-y-corfo-lanzan-el-primer-programa-de-innovacion-abierta-que-vincula-ciencia-y-tecnologia/](https://www.gob.cl/noticias/desafios-publicos-minciencia-y-corfo-lanzan-el-primer-programa-de-innovacion-abierta-que-vincula-ciencia-y-tecnologia/)

\[11\] Gobierno de Chile, "Ministerios de Defensa y Ciencia firman convenio para fomentar la investigación y la innovación en ciencia y tecnología \- Gob.cl”, Gobierno de Chile. Accedido: 17 de mayo de 2024\. \[En línea\]. Disponible en: [https://www.gob.cl/noticias/ministerios-de-defensa-y-ciencia-firman-convenio-para-fomentar-la-investigacion-y-la-innovacion-en-ciencia-y-tecnologia/](https://www.gob.cl/noticias/ministerios-de-defensa-y-ciencia-firman-convenio-para-fomentar-la-investigacion-y-la-innovacion-en-ciencia-y-tecnologia/)

\[12\] Ministerio de Ciencia, Tecnología, Conocimiento e Innovación, "Plan de Acción de la Política Nacional de Ciencia, Tecnología, Conocimiento e Innovación”. 2020\. \[En línea\]. Disponible en: [https://minciencia.gob.cl/politicactci/documentos/Politica-Nacional-CTCI\_Plan\_Accion\_Chile\_2020.pdf](https://minciencia.gob.cl/politicactci/documentos/Politica-Nacional-CTCI_Plan_Accion_Chile_2020.pdf)

\[13\] Laboratorio de Gobierno, ["Permitido innovar: ¿Cómo podemos desarrollar proyectos de ciencia de datos para innovar en el sector público?”](https://www.lab.gob.cl/permitido-innovar) 2018\.

\[14\] Ministerio de Ciencia, Tecnología, Conocimiento e Innovación, "Encuesta Nacional de Percepción Social de la Ciencia, Tecnología, Conocimiento e Innovación (CTCI) 2022”. 2022\. Accedido: 17 de mayo de 2024\. \[En línea\]. Disponible en: [https://observa.minciencia.gob.cl/encuesta/encuesta-nacional-de-percepcion-social-de-la-ctci](https://observa.minciencia.gob.cl/encuesta/encuesta-nacional-de-percepcion-social-de-la-ctci)

\[15\] Agencia Nacional de Investigación y Desarrollo ANID, "Plan de Gestión de Datos ANID v1”. mayo de 2022\. Accedido: 14 de mayo de 2024\. \[En línea\]. Disponible en: [https://www.cincel.cl/documentos/PGD\_20220506.pdf](https://www.cincel.cl/documentos/PGD_20220506.pdf)

\[16\] Agencia Nacional de Investigación y Desarrollo ANID y Comité Técnico Asesor de la Red de Apoyo a la Infraestructura Nacional de Acceso (INA), "Directrices de Metadatos y Mecanismos de Interoperabilidad”. 2024\. Accedido: 22 de mayo de 2024\. \[En línea\]. Disponible en: [https://acceso-abierto.anid.cl/wp-content/uploads/sites/4/2024/05/Metadatos\_para\_la\_Interoperabilidad\_de\_los\_Repositorios\_2024.pdf](https://acceso-abierto.anid.cl/wp-content/uploads/sites/4/2024/05/Metadatos_para_la_Interoperabilidad_de_los_Repositorios_2024.pdf)

\[17\] Universidad Central de Chile, "Política de Ciencia Abierta de la Universidad Central de Chile”, nov. 2023, doi: [10.5281/ZENODO.10204585](http://doi.org/10.5281/ZENODO.10204585).

\[18\] Universidad Central de Chile, "Declaración de interoperabilidad de metadatos Repositorio Institucional Universidad Central de Chile”, ene. 2024, doi: [10.5281/ZENODO.10523136](http://doi.org/10.5281/ZENODO.10523136)

\[19\] R. Hartley y I. Abedrapo Rosen, "Plantilla del Plan de Gestión de Datos de la Universidad Central de Chile”, nov. 2023, doi: [10.5281/ZENODO.10067320](http://doi.org/10.5281/ZENODO.10067320)

\[20\] Dirección de Investigación, Universidad Católica de la Santísima Concepción, "Plan de Gestión de Datos (PGD) Universidad Católica de la Santísima Concepción”. agosto de 2023\. Accedido: 14 de mayo de 2024\. \[En línea\]. Disponible en: [https://cienciaabierta.ucsc.cl/wp-content/uploads/sites/157/2023/11/Formato-Plan-de-Gestion-de-Datos-UCSC.docx](https://cienciaabierta.ucsc.cl/wp-content/uploads/sites/157/2023/11/Formato-Plan-de-Gestion-de-Datos-UCSC.docx).

\[21\] Universidad Católica de la Santísima Concepción, "Política Institucional de Ciencia Abierta de la Universidad Católica de la Santísima Concepción”. 15 de junio de 2023\. \[En línea\]. Disponible en: [https://cienciaabierta.ucsc.cl/wp-content/uploads/sites/157/2023/08/D.R.\_108\_2023\_PROMULGA\_ACUERDO\_DEL\_HCS\_QUE\_APRUEBA\_POLITICA\_DE\_CIENCIA\_ABIERTA\_DE\_LA\_UCSC-2.pdf](https://cienciaabierta.ucsc.cl/wp-content/uploads/sites/157/2023/08/D.R._108_2023_PROMULGA_ACUERDO_DEL_HCS_QUE_APRUEBA_POLITICA_DE_CIENCIA_ABIERTA_DE_LA_UCSC-2.pdf).

\[22\] Universidad del Desarrollo, "Política de Ciencia Abierta de la Universidad del Desarrollo”. 4 de diciembre de 2023\. \[En línea\]. Disponible en: [https://www.udd.cl/wp-content/uploads/2022/08/dr-nro144-23-politica-ciencia-abierta-udd-timbrado.pdf](https://www.udd.cl/wp-content/uploads/2022/08/dr-nro144-23-politica-ciencia-abierta-udd-timbrado.pdf).

\[23\] R. Hartley y I. Abedrapo Rosen, "Repositorios y Universidades Chilenas 2023”, 23 de enero de 2024\. doi: [10.5281/ZENODO.10557407](https://doi.org/10.5281/ZENODO.10557407).

\[24\] Pontificia Universidad Católica de Chile. Lineamientos para Política de Preservación digital de la UC. Accedido el 6 de julio de 2024\. doi: [10.7764/InESCA.UC.l06](https://doi.org/10.7764/InESCA.UC.l06).

\[25\] Ministerio de Ciencia, Tecnología, Conocimiento e Innovación, “Plan Nacional de Data Centers”. 2024\. Accedido: 03 de marzo de 2025\. \[En línea\]. Disponible en: [https://minciencia.gob.cl/uploads/filer\_public/95/6b/956b8c9f-d937-4b4d-8f6c-a871495a52ff/plan\_nacional\_de\_data\_centers\_pdata.pdf](https://minciencia.gob.cl/uploads/filer_public/95/6b/956b8c9f-d937-4b4d-8f6c-a871495a52ff/plan_nacional_de_data_centers_pdata.pdf)

\[26\] Agencia Nacional de Investigación y Desarrollo (ANID). (s. f.). InES Ciencia Abierta. Recuperado 3 de febrero de 2025, de [https://acceso-abierto.anid.cl/componentes/inescienciaabierta/](https://acceso-abierto.anid.cl/componentes/inescienciaabierta/)

\[27\] LA Referencia. (s. f.). LA Referencia. Recuperado 3 de febrero de 2025, de [https://www.lareferencia.info/es/](https://www.lareferencia.info/es/)

Licence: [Creative Commons Atribución-NoComercial 4.0 Internacional (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)