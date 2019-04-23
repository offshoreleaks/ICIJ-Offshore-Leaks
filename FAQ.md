
Frequently Asked Questions

- [How current is the data?](#1)
- [Should I assume that everyone named in the database has committed a crime?](#2)
- [Have you made any updates to the database?](#3)
- [Why can’t I find some names related to companies in the database that appeared in the Paradise Papers, the Panama Papers and the Bahamas Leaks stories?](#4)
- [Have you performed any transformations to the data?](#5)
- [How did you link a name to a country?](#6)
- [I can’t understand some of the terms used in this database. Could you help me with that?](#7)
- [Why are you linking to Open Corporates and Google Maps?](#8)
- [Why did you decide to use a graph database?](#9)
- [Can I download all the data in my computer?](#10)
- [What are the best tips on searching the Offshore Leaks database?](#11)
- [How do I get in touch with ICIJ?](#12)
- [Who funds ICIJ?](#13)

<h2 id="1">How current is the data?</h2>

- The Offshore Leaks data is current through 2010.
- The Panama Papers data is current through 2015.
- The Bahamas Leaks data is current through early 2016.
- The Paradise Papers Appleby data is current through 2014 and the Paradise Papers corporate registries data (Aruba, Cook Islands, Bahamas, Barbados, Malta, Nevis and Samoa) is current through 2016.

<h2 id="2">Should I assume that everyone named in the database has committed a crime?</h2>

No, there are legitimate uses for offshore companies and trusts. We do not intend to suggest or imply that any individuals, companies or other entities included in the ICIJ Offshore Leaks Database have broken the law or otherwise acted improperly.

<h2 id="2">Have you made any updates to the database?</h2>
**2013**

- June 14, 2013: [The Offshore Leaks Database was first published](https://www.icij.org/offshore/icij-releases-offshore-leaks-database-revealing-names-behind-secret-companies-trusts) with the names of more than 100,000 offshore entities incorporated through agents Portcullis Trustnet and Commonwealth Trust Limited.
- October 11, 2013: ICIJ provided [the possibility to search the names](https://www.icij.org/blog/2013/10/users-can-now-search-country-icij-offshore-leaks-database) inside the Offshore Leaks data by country.

**2014**

- January 23, 2014: more [records were added from ICIJ’s China Leaks](https://www.icij.org/investigations/offshore/unlocking-chinas-secrets/) investigation

**2016**

- May 9, 2016: [ICIJ added more than 200,000](https://panamapapers.icij.org/blog/20160509-offshore-database-release.html) offshore entities from the [Panama Papers](https://panamapapers.icij.org/) investigation, that had been incorporated through agent Mossack Fonseca. We also launched a new site design with more functionalities. That version of the database included address connections that were incorrect. This error was fixed on May 10, 11 p.m. EDT.
- May 24, 2016: we updated some records with better country identification, including connections to South and North Korea, and fixed a website glitch that did not display North Korea, French Polynesia and Tonga in the dropdown box of the homepage. ICIJ also included jurisdiction information for some entities that were previously labeled as "undetermined".
- September 21, 2016: ICIJ added more than 175,000 companies, trusts and foundations incorporated in the Bahamas from the Bahamas Leaks investigation.

**2017**

- November 5, 2017: ICIJ added data from some politicians featured in the Paradise Papers investigation.
- [November 17, 2017](https://www.icij.org/investigations/paradise-papers/icij-releases-paradise-papers-data-appleby/): ICIJ added records connected to around 25,000 entities that were linked to the offshore law firm Appleby.
- December 1, 2017: ICIJ added more than 20,000 new officer roles connected to the entities linked to Appleby.
- [December 19, 2017](https://www.icij.org/blog/2017/12/four-caribbean-tax-havens-added-offshore-leaks-database/): ICIJ added records connected to more than 160,000 entities from the Aruba, Bahamas, Barbados and Nevis corporate registries from the Paradise Papers investigation.

**2018**

- [February 14, 2018](https://www.icij.org/investigations/paradise-papers/data-ever-added-offshore-leaks-database/): ICIJ added records connected to more than 85,000 entities from the Cook Islands, Malta and Samoa corporate registries from the Paradise Papers investigation.

We will continue to provide information about any updates to the database in this section as they occur.

<h2 id="3">Why can’t I find some names related to companies in the database that appeared in the Paradise Papers, the Panama Papers and the Bahamas Leaks stories?</h2>

While the ICIJ Offshore Leaks Database opens up a world that has never been shown in this much detail, not every officer of a company that appears in the Paradise Papers, the Panama Papers and the Bahamas Leaks shows up in the public database. This is because information about ownership is often buried in emails, power-of-attorney letters and internal notes and cannot easily be extracted in a systematic manner. In addition, Mossack Fonseca often failed to collect the necessary information about the real owners of companies, relying instead on banks and other intermediaries to keep track of that essential data. In the case of the Bahamas Leaks, this is because many directors of offshore entities are found in unscanned registers that cannot be easily extracted in a systematic manner. While we faced a similar situation with the original Offshore Leaks data, those original databases from Portcullis Trustnet and Commonwealth Trust Limited contained more ownership information.

On November 5, 2017 and on April 3, 2016 ICIJ published interactive applications with detailed information on dozens of politicians in the leaked files. In order to better tell those specific stories, ICIJ manually added information from the Paradise Papers and the Panama Papers documents about the politicians to this database. You will identify these records easily because they include a note that says “record manually added from leaked documents.” In those cases ICIJ only published the information connected to the public figure and not that of others who may be associated with an offshore entity. On September 21, 2016, ICIJ performed a similar manual addition from documents within the Bahamas Leaks of information about former public officials and others.

<h2 id="4">Have you performed any transformations to the data?</h2>

The names of individuals and entities in this website come from leaked files. ICIJ used reverse engineering techniques to extract the information from them and build this database. In most occasions, the original records connected names with codes, which are used as unique identifiers. However, this was not always the case. For example, shareholder and beneficiary records in the Panama Papers lacked a code. In the case of agent Commonwealth Trust Limited, there were cases where the same name was associated with different codes. This means that sometimes what seems to be the same name could appear as two or more different nodes in this database.

ICIJ did not merge records with similar names, so there may be duplicates. However, we did merge shareholder and beneficiary records in the Panama Papers data if the names and the addresses were the same. We did this because those records had no unique identifiers in the leaked databases.

Names could have typos or be misspelled, but this is how they appear in the original databases ICIJ obtained. We did not perform any cleaning or standardization on the names, except for some slight cleaning on the entity names in the Panama Papers data to split the current from the former name of the company (both were sometimes together in Mossack Fonseca’s database). In the case of the Aruba corporate registry we had to translate some officer roles that were in Dutch into English.

In order to facilitate the exploration of the data, ICIJ created links between nodes with similar names and addresses. Those links also connect the Paradise Papers, the Bahamas Leaks, the Panama Papers and the Offshore Leaks data, all the sources of information that make up the database. ICIJ incorporated one additional node type with the Paradise Papers release in November 2017 that is connected to the Appleby data. This node “other” connects all the entities that are part of a holding group. This same node was also part of the Aruba corporate registry data. These connections were not created by ICIJ but are a direct reflection of the Aruba corporate registry and Appleby’s data.

Because this is a database that connects people and companies, isolated entities or people with no apparent connections have been removed. Isolated addresses have also been removed.

<h2 id="5">How did you link a name to a country?</h2>

ICIJ performed automatic identification of country names within all the addresses contained in the database. We used geocoding tools to complement the process. Some of the addresses ended up being manually reviewed by our team. ICIJ also shared these identifications with the reporting team of more than 370 journalists and improved the results based on their feedback.

Once a country was determined, the connected record -- an entity, an officer or an intermediary -- was linked to that country. The record was tagged as “not identified,” if no match could be made. The limitations to this identification process include potential data-entry and country-matching errors. If you find a name that is identified with the wrong country, please [contact us](https://offshoreleaks.icij.org/tips/new).

The original addresses from the leaked records were not standardized, containing multiple spellings or ways of describing the same address. ICIJ did not perform any cleaning on the addresses. This may mean that what to a human eye appears to be same address, in our database appears as several records.

<h2 id="6">What should I keep in mind before using the data or publishing any findings?</h2>

The information contained in the ICIJ Offshore Leaks Database is just a fraction of the leaked files of the Paradise Papers, the Panama Papers, the Offshore Leaks and the Bahamas Leaks investigations. We recommend caution before drawing any conclusions, as many people and entities have the same or similar names. We suggest you confirm the identities of any individuals or entities found in the database using addresses or other identifiable information.

The data comes directly from the leaked files ICIJ has received throughout different investigations and each set goes through a specific year. Keep in mind that some information, like the status of a company and its shareholders, might have changed over time.

<h2 id="7">I can’t understand some of the terms used in this database. Could you help me with that?</h2>

This database contains information about offshore entities, officers, intermediaries and addresses:

**Offshore Entity:**

A company, trust or fund created by an agent in a low-tax jurisdiction that often attracts non-resident clients through preferential tax treatment.

Agent (registered agent or offshore service provider):

Firm in an offshore jurisdiction that incorporates, registers and manages an offshore entity at the request of a client.

**Officer:**

A person or company who plays a role in an offshore entity.

**Intermediary:**

A go-between for someone seeking an offshore corporation and an offshore service provider -- usually a law-firm or a middleman that asks an offshore service provider to create an offshore firm for a client.

**Address:**

Contact postal address as it appears in the original databases obtained by ICIJ.

These are some useful definitions of other terms used in this application, which originate from the terminology that appeared in the leaked records:

**Beneficial owner (ultimate beneficial owner (UBO) or beneficiary):**

The true owner of a company. In the offshore world, the identity of beneficial owners is often kept secret.

**Bearer shares:**

Shares that are considered owned by whoever physically holds a share certificate. Bearer shares provide one of the deepest levels of secrecy. Many countries have banned bearer shares because they are considered a facilitator of tax evasion and money laundering. In the database, bearer shares are sometimes referred to in Spanish as “Portador.”

**Nominee:**

A person or company that acts on behalf of the beneficial owner of an entity to provide an extra level of secrecy.

**Nominee director:**

A stand-in who controls a company on paper but exercises no real authority over its activities.

**Nominee shareholder:**

A person who is listed as a shareholder on a company’s documents but has no real power over the company or claim to its assets. This is common practice in offshore financial structures to hide the identity of the real owner.

**Power of attorney:**

Authorization to represent the offshore company. It can confer rights that include managing the company without any limitation, carrying out contracts, purchasing products and borrowing or lending money. Each authorization notes which powers are granted to the person who will act on behalf of the company and whether they are general or specific.

**Incorporation Date:**

The date when an offshore entity was created.

**Dormancy Date:**

The date when an offshore entity stopped being active.

**Inactivation Date:**

The date when a client told the agent to deactivate the offshore entity, which could be reactivated at a later date.

**Struck off Date:**

A company becomes struck off when it fails to be in good standing, which happens if it fails to pay license fees. In the offshore world, this is the equivalent to closing an entity, although it can be reactivated at a later date if the fees start being paid again.

**Sundry Account:**

An internal account created by the offshore services firm to record miscellaneous charges of an officer or master client.

**Tax status:**

In this database, it is information that relates to the jurisdiction where an entity may have fiscal duties.

And here’s some terminology connected to trusts:

**Trust:**

A legal arrangement in which an individual transfers personally owned assets to a trustee.

**Trustee:**

A person who holds title to the assets in a trust and is responsible for administering the assets on behalf of the beneficiaries of the trust.

**Beneficiary:**

A person who is entitled to certain financial benefits under a trust arrangement. Sometimes beneficiaries are not aware of their role in a trust because the neither the settlor nor the trustee has notified them.

**Protector:**

An adviser to a trust settlor who oversees the work of the trustee.

**Trust settlor:**

A person who creates a trust or transfers assets to an already existing trust.

**Defaulted:**

It may indicate that the company chose not to renew a payment or otherwise missed a payment necessary to remain active on the country's corporate registry. It does not necessarily mean the company defaulted.

<h2 id="8">Why are you linking to Open Corporates and Google Maps?</h2>

[OpenCorporates](https://opencorporates.com/) is a website with information on more than 99 million companies (as of May 9, 2016). It claims to be “the largest open database of companies in the world”. The website was very useful for the reporting of ICIJ’s offshore investigations. As the offshore economy is directly connected to our regular economy and its companies, we believe there is an added value for connecting the opaque structures exposed in the ICIJ Offshore Leaks Database with OpenCorporates.

ICIJ also linked to [Google Maps](https://www.google.es/maps) in the pages showing addresses to provide additional information on its geolocation.

The connection to both sites was done automatically, and it may not yield any results. We also recommend you double-check whether  the result obtained refers to the same record in this database.

<h2 id="9">Why did you decide to use a graph database?</h2>

The datasets reveal the names of the people behind purposely complicated offshore structures and expose these networks of secrecy. Graph databases are the best way to explore the relationships between these people and entities – it’s much more intuitive to use for this purpose than a SQL database or other types of NoSQL databases. In addition, graphs allow users to understand these networks in a very intuitive way and easily discover connections.

<h2 id="10">Can I download all the data in my computer?</h2>

Yes, of course! Follow the instructions in [this link](https://offshoreleaks.icij.org/pages/database). Remember that the ICIJ Offshore Leaks Database is licensed under the [Open Database License](http://opendatacommons.org/licenses/odbl/1.0/) and contents under [Creative Commons Attribution-ShareAlike](http://creativecommons.org/licenses/by-sa/3.0/) license. Always cite the International Consortium of Investigative Journalists when using this data.

<h2 id="11">What are the best tips on searching the Offshore Leaks database?</h2>

You can read more about how to use the Offshore Leaks database [here](https://offshoreleaks.icij.org/pages/howtouse). We have also published some tutorials that could be useful:

- [How to search the Offshore Leaks database by location](https://www.icij.org/blog/2018/01/offshore-leaks-database-tips-location-geogrpahy/)
- [How to explore networks and entity metadata in the Offshore Leaks Database](https://www.icij.org/blog/2018/01/how-to-explore-networks-and-entity-metadata-in-the-offshore-leaks-database/)
- [How to investigate companies found in the Offshore Leaks Database](https://www.icij.org/blog/2018/01/investigate-companies-found-offshore-leaks-database/)

<h2 id="12">How do I get in touch with ICIJ?</h2>

The easiest way to contact us about any issues related to this database is to fill out this [form](https://offshoreleaks.icij.org/tips/new). We’ll answer any emails that have to do with tips, questions or errors you may find in the database. If you have any general queries for ICIJ, please email [contact@icij.org](mailto:contact@icij.org).

If you wish to contact us in a secure manner, follow the instructions in [this page](https://www.icij.org/securedrop), which includes a link to our Secure Drop server.

If you’re a journalist wanting access to the totality of the leaked files or interested in collaborating with ICIJ, please send an email to [data@icij.org](mailto:data@icij.org). We welcome these new offers of collaboration but also ask for your patience, as we are vetting the requests carefully and may only add a few new partners to each investigation.

This is not easy data to understand. It took great commitment from all of our current media partners to find stories of important public interest. ICIJ’s data unit provided training to our partners to make sure that everyone understood the intricacies of the information they were reporting on.

<h2 id="13">Who funds ICIJ?</h2>

ICIJ is a non-profit organization. We rely heavily on charitable foundations and on financial support from the public. We do not take funding from governments. Without our readers’ support, we cannot exist. Recent ICIJ funders include: Adessium Foundation, Ford Foundation, Hollywood Foreign Press Association, Jonathan Logan Family Foundation, Laura and John Arnold, Omidyar Network, Open Society Foundations, and the Swedish Postcode Foundation. Read more about our supporters [here](https://www.icij.org/about/our-supporters/).
