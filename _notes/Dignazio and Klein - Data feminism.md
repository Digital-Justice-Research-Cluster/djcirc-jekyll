D’Ignazio, C., & Klein, L. F. (2020). _Data Feminism_. The MIT Press.

## Introduction: why data science needs feminism

- Starts with anecdote about Christine Mann Darden - NASA "human computer" 
- central aim of the book: describe a form of intersectional feminism that takes the inequities of the present moment as its starting point and begins its own work by asking: How can we use data to remake the world? (p. 5)

- ==data feminism== - a way of thinking about data, both their uses and their limits, that is informed by direct experience, by a commitment to action, and by intersectional feminist thought. (p. 8)
- ==relationship between data and power== (p. 11) - evident through colonialist proactices of the dominant culture 
	- how this is replicated in ways that government continues to collect and quantify - eugenics movements - Link to [[Murphy - The economization of life]]  - biometric data 
- Examining how power operates in the world:
	- Who does the work (and who is pushed out)? Who benefits (and who is neglected or harmed)? Whose priorities get turned into products (and whose are overlooked)?
	- The current answer to most of these questions is “people from dominant groups,” which has resulted in a *privilege hazard* so acute that it explains the near-daily revelations about another sexist or racist data product or algorithm. The matrix of *domination helps* us to understand how the privilege hazard—the result of unequal distributions of power—plays out in different domains. (p. 47) - next chapters ==challenge power==

The close relationship between data and power is perhaps most clearly visible in the historical arc that begins with the logs of people captured and placed aboard slave ships, reducing richly lived lives to numbers and names. It passes through the eugenics movement, in the late nineteenth and early twentieth centuries, which sought to employ data to quantify the superiority of white people over all others. It continues today in the proliferation of biometrics technologies that, as sociologist Simone Browne has shown, are disproportionately deployed to surveil Black bodies. (p. 12)

- Data feminism - beyond thinking about women 
	- intersectional feminism - Data feminism is about power, about who has it and who doesn’t, and about
how those differentials of power can be challenged and changed using data. (p. 19)

That’s because data feminism isn’t only about women. It takes more than one gender to have gender inequality and more than one gender to work toward justice. Likewise, data feminism isn’t only for women. Men, nonbinary, and genderqueer people are proud to call themselves feminists and use feminist thought in their work. Moreover, data feminism isn’t only about gender. ==Intersectional feminists have keyed us into how race, class, sexuality, ability, age, religion, geography, and more are factors that together influence each person’s experience and opportunities in the world.== ==Finally, data feminism is about power—about who has it and who doesn’t. ==Intersectional feminism examines unequal power. And in our contemporary world, data is power too. Because the power of data is wielded unjustly, it must be challenged and changed. (p. 14)

- ==Book employs seven core principles== - emerge from the foundation of intersectional feminist thought

1. ==Examine power==. Data feminism begins by analyzing how power operates in the world.
	- Matrix of domination
2. ==Challenge power==. Data feminism commits to challenging unequal power structures and working toward justice.
3. ==Elevate emotion and embodiment==. Data feminism teaches us to value multiple forms of knowledge, including the knowledge that comes from people as living, feeling bodies in the world.
4. ==Rethink binaries and hierarchies==. Data feminism requires us to challenge the gender binary, along with other systems of counting and classification that perpetuate oppression.
5. ==Embrace pluralism==. Data feminism insists that the most complete knowledge comes from synthesizing multiple perspectives, with priority given to local, Indigenous, and experiential ways of knowing.
6. ==Consider context==. Data feminism asserts that data are not neutral or objective. They are the products of unequal social relations, and this context is essential for conducting accurate, ethical analysis.
7. ==Make labor visible==. The work of data science, like all work in the world, is the work of many hands. Data feminism makes this labor visible so that it can be recognized and valued.

## The power chapter

- Anecdote starts with Serena Williams' traumatic birth experience/experience shared in aggregate by Black women in America
- ==power and the matrix of domination== 
	- Definition of power - Link to [[Castells - The rise of the network society]] 
	- Power - describe the current configuration of structural privilege and structural oppression (p. 24)

We use the term power to describe the current configuration of structural privilege and structural oppression, in which some groups experience unearned advantages—because various systems have been designed by
people like them and work for people them—and other groups experience systematic disadvantages—because
those same systems were not designed by them or with people like them in mind. (p. 24)

- ==The matrix of domination== - Patricia Hill Collins - *Black Feminist Thought* - explains how systems of power are configured and experienced: structural, disciplinary, hegemonic and interpersonal 
	- **structural** - The structural domain is the arena of laws and policies, along with schools and institutions that implement them. (p. 24) ==organizes oppression== 
	- **disciplinary** - This is the disciplinary domain that Collins names: the domain that administers and manages oppression through bureaucracy and hierarchy, rather than through laws that explicitly encode inequality on the basis of someone’s identity (p. 25) ==administers and manages oppression==
	- **hegemonic** - Neither of these domains would be possible without the hegemonic domain, which deals with the realm of culture, media, and ideas. (p. 25) ==circulates oppressive ideas==
		- anti-suffragist pamphlet
	- **interpersonal** - The final part of the matrix of domination is the interpersonal domain, which influences the everyday experience of individuals in the world. (p. 26) ==individual experiences of oppression==

- ==minoritized== vs minority - use of the term throughout book
	- discussion of who does data science

Beginning in this chapter and continuing throughout the book, we use the term ==*minoritized* to describe groups of people who are positioned in opposition to a more powerful social group==. While the term ==*minority* describes a social group that is comprised of fewer people==, *minoritized* indicates that a social group is actively devalued and oppressed by a dominant group, one that holds more economic, social, and political power.

- the gap between women in CS - getting worse and not better - peaked in the 1980s at 37%, steady decline
	- under representation is reflected throughout higher education


This example reinforces the work of Safiya Umoja Noble, whose book, *Algorithms of Oppression*, has shown how both gender and racial biases are encoded into some of the most pervasive data-driven systems—including Google search, which boasts over five billion unique web searches per day. Noble describes how, as recently as 2016, comparable searches for “three Black teenagers” and “three white teenagers” turned up wildly different representations of those teens. The former returned mugshots, while the latter returned wholesome stock photography (p. 27)
- Link to [[Noble - Algorithms of oppression]] 
- gender and racial bias in IS - "the data that shape them, and the models designed to put those data to use, are created by small groups of people and then scaled up to users around the globe" (p. 28)
	- ==privilege hazard== - ignorance of being on top
		- data teams that are composed of people from dominant groups - those perspectives exclude other identities perspectives - white cis guyn perspective - hard to imagine anything else
		- occurs at every level of the individual - interpersonal domain of the matrix of domination

So it matters deeply that data science and artificial intelligence are dominated by elite white men because it means there is a collective privilege hazard so great that it would be a profound surprise if they could actually identify instances of bias prior to unleashing them onto the world.
- Kate Crawford - biggest threat to AI is not they will become smarter than humans but that they will ==hard-code sexism, racism, and other forms of discrimination into the digital infrastructure== (p. 29)
- Example of Joy Buolamwini - Algorithmic Justice League - uncovers privilege hazard in faical recognition software

For people in positions of power and privilege, issues of race and gender and class and ability—to
name only a few—are OPP: other people’s problems. Author and antiracist educator Robin DiAngelo describes instances like the “shock” of Darden’s boss or the surprise in the media coverage of Buolamwini’s various projects as a symptom of the “racial innocence” of white people.39 In other words, those who occupy positions of privilege in society are able to remain innocent of that privilege. (p. 31)
- bias, sexism, racism exist falls on the shoulders of people who experience the adverse effects - "exist—in datasets, in data systems, and in data science, as in everywhere else" (p. 31)
- downstream effects of privilege hazard - datasets are biased or unrepresentative and aren't collected at all 

The *who question* in this case is: Who benefits from data science and who is over looked? (p. 34)
- question that data activism, etc attempts to answer 
	- Ida B Wells - set of stats that addressed the epidemic of lynching
	- Maria Salguero 
- "quantification is representation" (p. 39)

- problem of surveillance in data: 

Far too often, the problem is not that data about minoritized groups are missing but the reverse: the databases and data systems of powerful institutions are built on the excessive surveillance of minoritized groups. (p. 39)
- flawed assumptions that data is always beter and data are a neutral input
- whose goals are prioritized in data science? 
	- bureaucratic goal of efficiency - Link to [[Marjanovic Cecez-Kecmanovic Vidgen - Theorising algorithmic justice]]

- Key questions: 
==How did we get to the point where data science is used almost exclusively in the service of profit (for a few), surveillance (of the minoritized), and efficiency (amidst scarcity)?== It’s worth stepping back to make an observation about the organization of the data economy: data are expensive and resource-intensive, so only already powerful institutions—corporations, governments, and elite research universities—have the means to work with them at scale.
- resource requirements: three S - science, surveillance, selling - whose purposes are served
	- example of the cloud - not cheap, resource intensive

##### Data as oil: 

In the past decade or so, many of these men at the top have described data as “the new oil.” It’s a metaphor that resonates uncannily well—even more than they likely intended. The idea of data as some sort of untapped natural resource clearly points to the potential of data for power and profit once they are processed and refined, but it also helps highlight the exploitative dimensions of extracting data from their source—people—as well as their ecological cost... But unlike crude oil, which is extracted from the earth and then sold to people, data are both extracted from
people and sold back to them (p. 45)
- ==asymmetry between who is collecting, storing, and analyzing data, and whose data are collected, stored and analyzed== 
	- The goals are corporate/institutional - neither neutral nor democratic

On the contrary, focusing on those *three Ss*—science, surveillance, and selling—to the exclusion of other possible objectives results in significant oversights with life-altering consequences. Consider the Target example as the flip side of the missing data on maternal health outcomes. Put crudely, there is no profit to be made collecting data on the women who are dying in childbirth, but there is significant profit in knowing whether women are pregnant. (p. 45)

#power #data-colonialism #colonialism