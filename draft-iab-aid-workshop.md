---
title: Report from the IAB Workshop on Analyzing IETF Data (AID), 2021
abbrev: IAB AID Workshop 2021
docname: draft-iab-aid-workshop-latest
date:
category: info

ipr: trust200902
keyword: Internet-Draft

stand_alone: yes
pi: [sortrefs, symrefs]

author:
  -
    ins: N. ten Oever
    name: Niels fen Oever
    org: University of Amsterdam
    email: mail@nielstenoever.net

  -
    ins: C. Cath
    name: Corinne Cath
    org:
    email: corinnecath@gmail.com

  -
    ins: M. Kühlewind
    name: Mirja Kühlewind
    org: Ericsson
    email: mirja.kuehlewind@ericsson.com

  -
    ins: C. Perkins
    name: Colin Perkins
    org: University of Glasgow
    email: csp@csperkins.org


normative:


informative:


--- abstract

The 'Show me the numbers: Workshop on Analyzing IETF Data (AID)' was convened by the Internet Architecture Board (IAB) and the IN-SIGHT.it project at the University of Amsterdam in November and December 2020. This report summarized the workshop's significant points of discussion and identifies topics that may warrant future work and consideration.

Note that this document is a report on the proceedings of the workshop. The views and positions documented in this report are those of the workshop participants and do not necessarily reflect IAB views and positions.

--- middle

# Introduction

The Internet Architecture Board (IAB) regularly organizes workshops designed to consider long-term issues and strategies for the Internet, and to suggest future directions for the Internet architecture.  This long-term planning function of the IAB is complementary to the ongoing engineering efforts performed by working groups of the Internet Engineering Task Force (IETF).

The IETF as an international Standards Developing Organization hosts diverse data on the history, development, and current activities in the development and standardization of Internet protocols and its institutions. A large portion of this data is publicly available, yet this data is arguably underutilized as a tool to inform the work in the IETF and research on topics like Internet governance and trends in ICT standard-setting.

The aim of this workshop was to analyze how IETF data currently is used, what insights can be drawn from that, and what questions that are worth pursuing remain unanswered. These questions could inform a research agenda for IETF data for collaborative work among interested parties, ranging from academia and civil society to industry and IETF leadership. 

# Workshop Scope and Discussion

## Tools, data, and methods

The IETF holds a wide range of data sources. The main ones used are the [mailinglist archives](), [RFCs](), and [the datatracker](). The latter provides information on participants, authors, meeting proceedings, minutes [and more](). Furthermore there are [statistics for the IETF websites](), working group Github repositories, IETF [survey data](). 

There are a wide range of tools to analyze this data, produced by IETF participants or researchers interestested in the work of the IETF. Two projects that presented their work at the workshop were [BigBang](https://bigbang-py.readthedocs.io/en/latest/) and Sodestream's [IETFdata](https://github.com/lumisota/ietfdata) library. These projects could be used to add additional insights to the existing [IETF statistics](https://www.arkko.com/tools/docstats.html) page and the [datatracker statistics](https://datatracker.ietf.org/stats/)

## Observations on affiliation and industry control

Discussions about the analysis of IETF data shows that affiliation is hard to narrow down. In part because affiliation is an open text field, which causes people to write their affiliation down in different ways (capitilization, space, word seperation, etc). 

Furthermore there is the issue of mergers and acquisitions and subsidiary companies. There is no authorotative exogenous source of variation for affiliation changes so hand-collected and curated data is used to analyze changes in affiliation over time. Whereas this is imperfect, conclusions can be drawn from the data, such as that in case of a merger or acquisition where a small organizations joins a large organization, this results in a statistically significant  increase in liklihood of an individual being put in a working group chair position [BaronKanevskaia](https://www.iab.org/wp-content/IAB-uploads/2021/11/Baron.pdf)

A common data format could contribute to analyses that compare SDO performance and behavior of actors inside and across standards bodies. To help this a draft data model has been developed during the workshop which can found under [Annex A].



## Community and diversity

## Publications, process, and decision-making

## Environmental Sustainability

# Position Papers {#positionpapers}

## Tools, data, and methods

Sebastian Benthall [Using Complex Systems Analysis to Identify Organizational Interventions](https://www.iab.org/wp-content/IAB-uploads/2021/11/Benthall.pdf) 
  
Stephen McQuistin, Colin Perkins [The ietfdata Library](https://www.iab.org/wp-content/IAB-uploads/2021/11/McQuistin.pdf)
 
Marc Petit-Huguenin [The RFC Prolog Database](https://www.iab.org/wp-content/IAB-uploads/2021/11/Petit-Huguenin.txt)
 
Jari Arkko [Observations about IETF process measurements](https://www.iab.org/wp-content/IAB-uploads/2021/11/Arkko.pdf)

## Observations on affiliation and industry control

Justus Baron, Olia Kanevskaia [Competition for Leadership Positions in Standards Development Organizations](https://www.iab.org/wp-content/IAB-uploads/2021/11/Baron.pdf)

Nick Doty [Analyzing IETF Data: Changing affiliations](https://www.iab.org/wp-content/IAB-uploads/2021/11/Doty.pdf)

Don Le [Position Paper](https://www.iab.org/wp-content/IAB-uploads/2021/11/Le.pdf)

Elizaveta Yachmeneva [Research Proposal](https://www.iab.org/wp-content/IAB-uploads/2021/11/Yachmeneva.pdf)

## Community and diversity

Priyanka Sinha, Michael Ackermann, Pabitra Mitra, Arvind Singh, Amit Kumar Agrawal [Characterizing the IETF through its consensus mechanisms](https://www.iab.org/wp-content/IAB-uploads/2021/11/Sinha.pdf)

Mallory Knodel [Would feminists have built a better internet?](https://www.iab.org/wp-content/IAB-uploads/2021/11/Knodel.pdf)

Wes Hardaker, Genevieve Bartlett [Identifying temporal trends in IETF participation](https://www.iab.org/wp-content/IAB-uploads/2021/11/Hardaker.pdf)

Lars Eggert [Who is the Average IETF Participant?](https://www.iab.org/wp-content/IAB-uploads/2021/11/Eggert.pdf)

Emanuele Tarantino, Justus Baron, Bernhard Ganglmair, Nicola Persico, Timothy Simcoe [Representation is Not Sufficient for Selecting Gender Diversity](https://www.iab.org/wp-content/IAB-uploads/2021/11/Tarantino.pdf)

## Publications, process, and decision-making

Michael Welzl, Carsten Griwodz, Safiqul Islam [Understanding Internet Protocol Design Decisions](https://www.iab.org/wp-content/IAB-uploads/2021/11/Welzl.pdf)

Ignacio Castro et al [Characterising the IETF through the lens of RFC deployment](https://dl.acm.org/doi/abs/10.1145/3487552.3487821)

Carsten Griwodz, Safiqul Islam, Michael Welzl [The Impact of Continuity](https://www.iab.org/wp-content/IAB-uploads/2021/11/Griwodz.pdf)

Paul Hoffman [RFCs Change](https://www.iab.org/wp-content/IAB-uploads/2021/11/Hoffman.pdf)

Xue Li, Sara Magliacane, Paul Groth [The Challenges of Cross-Document Coreference Resolution in Email](https://www.iab.org/wp-content/IAB-uploads/2021/11/Groth.pdf)

Amelia Andersdotter [Project in time series analysis: e-mailing lists](https://www.iab.org/wp-content/IAB-uploads/2021/11/Andersdotter.pdf)

Mark McFadden [Position Paper](https://www.iab.org/wp-content/IAB-uploads/2021/11/McFadden.pdf)

## Environmental Sustainability

Christoph Becker [Towards Environmental Sustainability with the IETF](https://www.iab.org/wp-content/IAB-uploads/2021/11/Becker.pdf)

Daniel Migault [CO2eq: Estimating Meetings’ Air Flight CO2 Equivalent Emissions: An Illustrative Example with IETF meetings](https://www.iab.org/wp-content/IAB-uploads/2021/11/Migault.pdf)


# Workshop participants {#participants}

Bernhard Ganglmair
Carsten Griwodz
Christoph Becker
Colin Perkins
Corinne Cath
Daniel Migault 
Don Le
Effy Xue Li
Elizaveta Yachmeneva
Francois Ortolan
Greg Wood
Ignacio Castro
Jari Arkko
Justus Baron 
Karen O’Donoghue 
Lars Eggert
Mallory Knodel
Marc Petit-Huguenin
Mark McFadden
Michael Welzl
Mirja Kühlewind 
Nick Doty
Niels ten Oever
Priyanka Sinha
Safiqul Islam
Sebastian Benthall
Stephen McQuistin
Wes Hardaker
Zhenbin Li

# Program Committee

The workshop Program Committee members were Niels ten Oever (chair, University of Amsterdam), Colin Perkins (chair, IRTF, University of Glasgow), Corinne Cath (chair, Oxford Internet Institute), Mirja Kühlewind (IAB, Ericsson), Zhenbin Li (IAB, Huawei), Wes Hardaker (IAB, USC/ISI).

# Acknowledgments

The Program Committee wishes to extend its thanks to Cindy Morgan for logistics support and to Kate Pundyk for notetaking.

This workshop was made possible through funding from the Dutch Research Council (NWO) through grant MVI.19.032 as part of the programme ‘Maatschappelijk Verantwoord Innoveren (MVI)’.

# Annexes

## Annex 1 - Data Taxonomy

A Draft Data Taxonomy for SDO Data:

Organization:
	Organization Subsidiary
    		Time
	Email domain
	Website domain
	Size 
        	Revenue, annual
        	Number of employees
	Org - Affiliation Category (Labels) ; 1 : N
        	Association
        	Advertising Company
        	Chipmaker
		Content Distribution Network
		Content Providers
		Consulting
		Cloud Provider
		Cybersecurity
		Financial Institution
		Hardware vendor
		Internet Registry
		Infrastructure Company
		Networking Equipment Vendor
		Network Service Provider
		Regional Standards Body
		Regulatory Body
	        Research and Development Institution
		Software Provider
	        Testing and Certification 
		Telecommunications Provider 
		Satellite Operator

Org - Stakeholder Group : 1 - 1
       Academia
       Civil Society
       Private Sector -- including industry consortia and associations; state-owned and government-funded businesses
       Government
       Technical Community (IETF, ICANN, ETSI, 3GPP, oneM2M, etc)
       Intergovernmental organization 

SDO:
	Membership Types (SDO)
	Members (Organizations for some, individuals for others…)
	Membership organization
		Regional SDO
            		ARIB
			ATIS
			CCSA
			ETSI
			TSDSI
			TTA
			TTC
		Consortia

Country of Origin:
	Country Code

Number of Participants

Patents
	Organization
	Authors - 1 : N - Persons/Participants
	Time
	Region
	Patent Pool
	Standard Essential Patent
		If so, for which standard

Participant (An individual person)
	Name
	1: N - Emails
		Time start / time end

	1 : N : Affiliation
		Organization
		Position
	        Time start / end

	1 : N : Affiliation - SDO
		Position
		SDO
		Time

	Email Domain (personal domain)

	(Contribution data is in other tables)

Document
	Status of Document
        	Internet Draft
        	Work Item
		Standard
	Author - 
		Name
        	Affiliation - Organization
		Person/Participant
    		(Affiliation from Authors only?)

Data Source - Provenance for any data imported from an external data set

Meeting
	Time
	Place
	Agenda
	Registrations
		Name
		Email
		Affiliation

