---
#- `title:` The project title.
title: edudrive@RNP
#- `notitle:` Set this to `true` if you don't want a title displayed on the project card. Optional.
#- `description:` The text shown in the project card. It supports markdown.
description: A Cloud Computing storage service for academics and researchers of Brazilian institutions.
#- `people:` The people working on the project. This is a list of keys from the `_data/people.yml` file.
people:
  - kaduardo
#- `layout: project` This sets the layout of the actual project page. It should be set to `project`.
layout: project
#- `image:` The URL of an image for the project. This is shown on both the project page and the project card. Optional.
image: /img/projects/edudrive/logo-edudrive-vetorizada.svg.png
#- `last-updated:` Date in the format of `YYYY-MM-DD`. The project cards are sorted by this, most recent first.
last-updated: 2015-01-01
#- `status: inactive` Set this to `inactive` if don't want the project to appear on the front page. Just ignore it otherwise.
#- `link:` Set this to an external URL if this project has a page somewhere else on the web. If you don't have a `link:`, then the content of this markdown file (below the YAML frontmatter) will be this project's page.
#- `no-link: true` Set this if you just don't want a project page for your project.
---


Cloud-based storage systems nowadays are common tools with several solutions available for varied user profiles and by different commercial providers. However, it is also common to find different issues and discussions in terms of users rights regarding privacy and ownership of their data.

The edudrive@RNP started as the Cloud Computing for Science (CNC *Computação em Nuvem para a Ciência*) project, with the aim of offering a strictly national cloud storage service for academics and researchers of Brazilian education and research institutes.

Under the leadership of Dr. Roberto Araujo and Dr. Carlos da Silva the project was conducted as a Working Group of the R&D programme of the Brazilian National Education and Research Network (RNP - Rede Nacional de Pesquisa), with the aim of designing, developing, and deploying a cloud-based storage service for Brazilian academic institutions inside the network infrastructure of RNP.

The project studied, developed and deployed the first cloud computing storage solution in Brazilian territory based on the Openstack cloud computing platform and the Owncloud framework, with support to federated authentication through the CAFe service of RNP.

<figure class="text-center">
  <img class="figure-img img-fluid rounded" src="{{ site.baseurl }}/img/projects/edudrive/cncoverview.png" alt="Overview of the CNC architecture" title="Overview of the CNC architecture"/>
  <figcaption class="figure-caption">Overview of the CNC architecture.</figcaption>
</figure>

The project was conducted over 5 years (phases):

### Phase #1 (2011-2012) - Prototype

In its first phase the project was focused on a detailed study of cloud-based storage systems with an evaluation of different tools for building cloud computing storage services. This study resulted in the deploying of a prototype using the Openstack cloud computing platform, one of the tools evaluated, with servers spread over two Brazilian universities over 3700 Km apart.

### Phase #2 (2012-2013) - Pilot

In its second phase the project was focused in refining the developed prototype into a pilot service. This included the development of Web-based access and desktop file synchronization into the storage service, similar to available commercial services, and the integration of the cloud storage service into the federated authentication service provided by RNP (CAFe - Comunidade Acadêmica Federada). The pilot was made available to a number of academics all over Brazil.

### Phase #3 (2013-2014) - Experimental Service

In its third phase the pilot was further refined and deployed as an experimental service, being offered to 11 academic and research institutions all over Brazil. 
This phase was focused on aspects related to user experience, with an improvement of its Web-based interface based on the Owncloud framework and its integration to the CAFe federated authentication service, the development of new functionalities and an expansion of its supporting infrastructure, with a new dashboard for monitoring and management of the service.

### Phase #4 (2014-2015) - Experimental Service 2

The fourth phase focused on the development of new functionalities, with a focus on mobile and desktop clients. It also included the development of tools and approaches for the monitoring, management and maintenance of the cloud infrastructure, as well as a refining of the security aspects of the service (e.g., access control) and its usage of cryptographic technologies. This phase also included aspects related to service governance and the planning of the transition into a production service. 
The service continues to be used by 11 institutions with the objective of obtaining feedback to the development team, and is .

### Phase #5 (2015-2020) - Production

The fifth phase marks the transition from an experimental service maintained by a research group into a full-fledge product to be offered by RNP to its clients. Now rebranded as [edudrive@RNP](https://edudrive.rnp.br) the service is maintained and operated by RNP in partnership with [Anolis TI](https://anolis.com.br/), a spin-off company created by the participants of the project.

In this phase the service started to be used in production scenarios and new features have been developed based on final users feedback, including: collaborative editing, interactive tutorials and onboard guides, MS office widget and draw.io integration. As new users joined the service, infrastructure and monitoring improvements were required, which include: better infrastructure automatization, search and analysis tools for machine-generated big data logs, better CI/CD strategies and so on.

Today, edudrive@RNP is used by five large institutions in Brazil and stores millions of files, resulting in terabytes of storage data in its environment.

# Publications

* <span class="title"><b>Managing Access to Service Providers in Federated Identity Environments: A Case Study in a Cloud Storage Service</b></span>
by <span class="author">Diniz, Thomas F. S., Felipe, Andre Luiz Castro, Medeiros, Taina J., da Silva, Carlos Eduardo, and Araujo, Roberto</span>
<span class="periodical"><em>In 2015 XXXIII Brazilian Symposium on Computer Networks and Distributed Systems, 2015</em></span>
[doi: 10.1109/SBRC.2015.32](https://doi.org/10.1109/SBRC.2015.32)

* <span class="title"><b>SE-CNC-A Brazilian Experimental Cloud Storage Service</b></span>
by <span class="author">Araujo, Roberto; da Silva, Carlos Eduardo; Diniz, Thomás; Medeiros, Tainá; Marins, André; and Stanton, Michael</span>
<span class="periodical"><em>In 7th Annual Conference of the UbuntuNet Alliance (UbuntuNet Connect 2014), 2014</em></span>

* <span class="title"><b>Estudo de Caso: Integração de Clientes da Nuvem OpenStack Swift Com Uma Federação de Identidade</b></span>
by <span class="author">Silva, Lucas Melo, Silva, Felipe Leite, Aguiar, Daniel, Diniz, Thomas, da Silva, Carlos Eduardo, and Araújo, Roberto</span>
<span class="periodical"><em>
In III Workshop de Gestão de Identidades, 2013</em></span>

* <span class="title"><b>Integrando o Openstack Keystone com uma Federação de Identidades</b></span>
by <span class="author">Diniz, Thomas F. S., da Silva, Carlos Eduardo, and Araujo, Roberto</span>
<span class="periodical"><em>
In III Workshop de Gestão de Identidades (WGID) no Simpósio Brasileiro em Segurança da Informação e de Sistemas Computacionais (SBSeg), 2013</em></span>
