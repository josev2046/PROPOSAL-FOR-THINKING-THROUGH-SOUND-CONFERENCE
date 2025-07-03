# [DRAFT July 2nd 2025] Thinking Through Sound: Activating Black British and Diasporic Audiovisual Archives Through Experiential Installation

**Authors:**
Dr. David Dunkley Gyimah, Reader/Associate Professor, Cardiff School of Journalism, Media and Culture; 
José Velázquez, MA, Archivist and Multimedia Producer, University of Pablo de Olavide (Associate Lecturer)

---

## Abstract

****This paper details the "Save Your Archive: BlackLives" art installation series, outlining a technical approach to preserving and providing innovative, experientially-driven access to vulnerable Black British and diasporic audiovisual archives, thereby inviting audiences to "think through sound."****

The initiative directly addresses the critical need for robust digital preservation and new forms of archival engagement, particularly in how sound shapes our understanding of history and identity. This is achieved through advanced digitisation techniques for legacy media formats and the integration of a Retrieval-Augmented Generation (RAG) architecture within a custom Media Asset Management (MAM) system. This framework provides enhanced accessibility and nuanced engagement with historically underrepresented narratives, exploring how the very act of listening can reveal hidden histories. The series, exemplified by our "Unframed Voices" prototype, features a modular exhibition design that connects analogue audio heritage with contemporary digital technologies. This encompasses the development of time-based media installations utilising single-board computers (SBCs) and custom API development for dynamic content delivery and secure playback management. These installations cultivate immersive listening experiences through concealed digital media players and high-fidelity audio outputs, enabling unique public interaction with archival material. The curatorial framework prioritises historical care, creative reclamation, and public access, positioning the installations as pedagogical and political interventions that activate overlooked voices in public spaces. This technical and conceptual approach, validated by the completed prototype, enables the systematic processing of significant collections, such as the "GLR Black London" archive. This ensures these vital historical assets inform contemporary discourse and contribute to long-term cultural memory through innovative access pathways, demonstrating how sound can serve as a potent tool in both research and the revelation of an archive of resistances. The project highlights the multifaceted role of sound in archival practice, illustrating its capacity to reveal histories, shape identity, and contribute to interdisciplinary research methodologies, even where sound is not the primary focus of the initial research.

**Keywords:** Audiovisual Archives, Digital Preservation, Black British History, Media Art Installation, Retrieval-Augmented Generation (RAG), Media Asset Management (MAM), Single-Board Computers (SBCs), DIY, API Development, Cultural Memory, Sound Studies, Audio Accessibility.

---

## 1. Introduction: Thinking Through Sound as Method and Memory

R. Murray Schafer’s assertion that “the sense of hearing cannot be closed off at will” (Schafer, 1977, p. 11) underscores sound’s profound and inescapable influence on human perception and experience. This paper explores the "Save Your Archive: BlackLives" art installation series, a project that embodies the notion of “thinking through sound” not merely as a sensory engagement but as a critical methodological approach to excavating, preserving, and recontextualising neglected historical narratives. In an era where analogue media faces critical decay, the tangible sonic traces of Black British and wider African and Caribbean diasporic experiences risk being irrevocably lost, along with the crucial insights they offer into societal issues, cultural identity, and political resistance.

This initiative directly addresses the urgent need to preserve these vulnerable audiovisual archives and, crucially, to develop innovative, experientially-driven methods for public access. By leveraging advanced digital preservation techniques alongside experimental time-based media installations, "Save Your Archive: BlackLives" proposes sound as a powerful tool in research and as a catalyst for public dialogue. This paper will detail the project's context, its methodological and technical frameworks, and its significant contribution to understanding how sound can reveal archives of resistances, trace histories, and shape identity within and beyond traditional academic confines.

## 2. Project Context and Rationale: Unearthing Overlooked Audio Histories

The historical record, particularly in Britain, has often omitted or under-documented the lived experiences of Black individuals. Audiovisual archives, holding invaluable first-person accounts, cultural expressions, and political commentaries, are particularly susceptible to loss due to the obsolescence of their physical carriers (Gyimah, 2023). "Save Your Archive: BlackLives" emerges from this critical void, specifically targeting endangered broadcast formats such as Beta SP, D1, D2 tapes, and quarter-inch reels. The project is rooted in the conviction that preserving these sound-rich assets is essential for a more complete and pluralistic understanding of history.

Our work has focused significantly on collections such as the "GLR Black London" archive, a series of rare BBC radio recordings from 1991-1993. This material offers a multi-dimensional view of Black life in London, encompassing themes of systemic racism, political activism, cultural production, and social justice. The rationale extends beyond mere preservation; it seeks to activate these voices, allowing them to inform contemporary discourse and reinforce long-term cultural memory. The project responds directly to the conference's call to explore how sound contributes to other disciplines and vice versa, and how sound can shape methodologies, even when not the central focus of the original material.

## 3. Methodology and Technical Implementation: Engineering Experiential Access

The "Save Your Archive: BlackLives" project employs a multi-faceted methodology combining rigorous archival practice with cutting-edge digital innovation, culminating in a unique approach to public engagement.

### 3.1 Preservation-Grade Digitisation and Media Asset Management

The initial phase involved the professional digitisation of obsolete analogue media by specialist partners, including Memnon Archive Services. Materials were converted to preservation-grade digital standards and ingested into a custom-built Media Asset Management (MAM) system. Critical to this process was meticulous metadata enrichment, employing controlled vocabularies and transcription generation to ensure comprehensive description and discoverability of the assets. This structured approach underpins the long-term sustainability and searchability of the collection.

### 3.2 Retrieval-Augmented Generation (RAG) for Nuanced Archival Inquiry

To facilitate intelligent and context-aware access to the digitised content, a Retrieval-Augmented Generation (RAG) architecture has been integrated into the MAM system. This system segments archival content (transcripts, annotations, descriptions) into indexed chunks. When a user query is issued, the RAG system retrieves the most relevant chunks and passes them to a large language model (LLM), enabling precise, context-aware responses that transcend simple keyword searches. This innovation transforms raw archival data into a dynamic resource for research and public inquiry, allowing for a deeper “thinking through sound” in the discovery phase itself. Future iterations are planned to transition to fully open-source components such as ByteDance-Seed/BAGEL-7B-MoT to enhance replicability and community engagement.

### 3.3 Experimental Access: Time-Based Media Installations via SBCs and API Development

The project distinguishes itself through its approach to public access, moving beyond conventional online portals to create immersive, physical encounters with the archive. This is realised through a series of modular art installations, exemplified by “The Fela Kuti Tapes, ‘Unframed Voices’” prototype, which has already been built and developed.

Each installation serves as a “listening station” designed for flexible deployment in diverse venues, from galleries and libraries to community centres. A visual centrepiece, such as a quarter-inch analogue open-reel archive tape, acts as a conceptual entry point. Crucially, the activation of these installations relies on bespoke time-based media technology. Concealed digital media players, powered by Single-Board Computers (SBCs) (e.g., Raspberry Pi, as detailed in related project documentation), play curated audio loops. These SBCs are integrated with custom API development (such as leveraging the Vimeo API for dynamic content sourcing), enabling automated, scheduled content refresh and secure playback management. High-quality headphones or directional audio speakers offer an intimate, focused auditory experience.

This technical framework allows for dynamic content delivery, ensuring that installations can evolve, receive updates, and present different thematic selections over time. The use of SBCs ensures a cost-effective, robust, and scalable solution for distributed, experiential access points. The installations are conceived as pedagogical and political interventions: by inviting individual and shared deep listening, they activate overlooked voices, challenging passive consumption and fostering new modes of engagement with cultural memory. This experimental methodology directly demonstrates how sound can contribute to research practices by creating new avenues for reflection within and about the archival material.

## 4. Thematic Insights from the GLR Black London Archive

The digitised “GLR Black London” collection, processed through this framework, offers profound insights into the Black British experience. The content reveals intersecting themes of:
* Political and Social Activism: Documenting debates on race equality, immigration, and protests in response to events like the Rodney King verdict, highlighting transnational solidarity.
* Systemic Racism and Discrimination: Exploring the disproportionate impact of the criminal justice system on Black Britons, health disparities, and underrepresentation in public institutions.
* Grassroots Advocacy: Showcasing community resilience and independent organising against systemic neglect, such as the “Black Camden Sisters.”
* Cultural Identity and Representation: Capturing vibrant artistic movements, music (including Fela Kuti’s influence), theatre, and community celebrations that shaped Black identity in London during the early 1990s.

These thematic insights underscore the critical importance of preserving and activating these sonic histories, proving the methodology’s efficacy in revealing previously obscured narratives.

## 5. Project Significance and Contribution

The "Save Your Archive: BlackLives" project makes a significant contribution to digital humanities, archival studies, and sound studies. It provides a robust, replicable model for securing vulnerable audiovisual heritage and activating it for public scholarship and creative practice. By combining meticulous digitisation with advanced discovery systems (MAM, RAG) and innovative experiential installations (SBCs, API-driven playback), the project moves beyond passive archiving to dynamic engagement.

It directly addresses the conference’s invitation to explore the “multiplicity of sound—as medium, metaphor, method, and memory.” Sound serves as the *medium* of the original recordings, a *metaphor* for unheard voices, a *method* for both technical processing and experiential engagement, and a vessel for *memory* and identity formation. This initiative demonstrates how sound can fundamentally shape our methodologies, allowing researchers and the public alike to “think through sound” to reveal archives of resistances and contribute to a more inclusive historical narrative.

## 6. Conclusion

The "Save Your Archive: BlackLives" project offers a compelling model for revitalising critical components of Black British and diasporic history. Through the systematic application of preservation-grade digitisation, intelligent data management via RAG, and the deployment of innovative, SBC-driven time-based media installations, voices once at risk of being lost are now made accessible and active. This project not only safeguards invaluable historical assets but also pioneers new pathways for public interaction with archives, profoundly enriching contemporary discourse and long-term cultural memory by inviting us all to truly think through sound.

---

### References

* Gyimah, D. D. (2023). *Black London (BBC GLR 1991–1993): the Importance of a BBC Radio Archive for Black British People and Scholars.* Journal of Radio & Audio Media, 30(2). https://doi.org/10.1080/19376529.2023.2261924
* Schafer, R. M. (1977). *The Tuning of the World*. Knopf.
* Velázquez, J. (2022). *Save Your Archive: Black Lives – Historical Friendships and the King's Men*. Zenodo. https://doi.org/10.5281/zenodo.15045939
* Digital-Signage-System GitHub Repository (Refers to the technical implementation of SBC and API for content delivery).

---

### Preferred Presentation Format: [TBD]

---

### Curators' Biographies

**Dr. David Dunkley Gyimah** is a Reader/Associate Professor at the Cardiff School of Journalism, Media and Culture. His research and practice focus on innovation and digital labs within journalism and storytelling, international journalism, and cinema journalism. Dr. Gyimah's work frequently explores the intersection of media, technology, and cultural narratives, particularly concerning underrepresented histories and novel forms of digital engagement.

**José Velázquez, MA,** is an archivist and multimedia producer with over two decades of experience designing interoperable systems. His expertise lies in bridging technology, academia, and the creative industries, with a particular focus on audiovisual preservation, cultural memory, and the development of open, interoperable systems for managing media at scale. Velázquez has consulted for organisations including the BBC, IBM, and Google, and is an Associate Lecturer on the Digital Humanities Master's programme at the University of Pablo de Olavide.

