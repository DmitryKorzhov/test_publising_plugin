---
share: true
---

type:: [[call transcription]]


## Answers 1-5 min

> [!summary]- Full answer 0-5 min.
> Speaker 0: Thank you all for joining. I am actually going to share my screen. I have just a few slides just for visuals that we've talkedabout in the past to help us just stay on the same page and making sure we're all the same understanding, but gimme onesecond and it will join. Angela. Couldn't join, but you have me Dana and Dave from our side. And then Eric is Michaeljoining.
> 
> Speaker 1: He should let me ping him really quick. I know that Fabio and Ariel are on as well, but let me, let me ping Michael.
> 
> Speaker 0: Okay, perfect.
> 
> Speaker 2: We can see your screen on.
> 
> Speaker 0: Awesome. Okay, well, I'm gonna go ahead and get started. There's a lot of people on this call, so I just wanna do quickintroductions, Eric or Fabio, if you wanna introduce your side and then me and Dave and Dan can introduce our side.
> 
> Speaker 3: Yeah. Thank you. Laura FIO. Marton I'm the chief strategy officer here I'm role in the project is to, as executive supportedto be sure that I he's moving forward properly. And from our end, we have Eric our VP solution consulting in charge ofthe professional service. Michael Belan is our key account manager for T-Mobile account and is the project manager thatis coordinating all activities from the professional services perspective. Nice to meet you all.
> 
> Speaker 0: Thank you. And then from our side, you know, a lot of us, but you have me Dan and Dave who are project leads, Mohifrom your side. Would you mind introduce?
> 
> Speaker 0: Introduce your side as well.
> 
> Speaker 2: Drew has joined, so I'll let you do do it. Oh, thank you.
> 
> Speaker 4: Yeah. Do I represent the, the larger RS group? Oh, nice meet you for folks. No, yeah. Nice meeting you too. So from theT-Mobile side, number of our team, number of the teams know us, but we fulfill a role where we try to consolidateanalytics and reporting, try to provide kind of one-stop shop for a number of different lines of business. And so that's kindof where the expertise comes in is that we typically are sourced in data, both internal and external T-Mobile to bringtogether kind of that consolidated customer view. And so on the call you've got here Mo hit Aries list as well. They helpus from management of our platforms, infrastructure also providing kind of our technical roadmap, capabilities, guidelines, kind of help guide our future. Then you got Mondu, which I actually don't. Oh, she
> 
> Speaker 0: Must be able to join she's on PTO.
> 
> Speaker 4: Okay. Right now she represents the, some of our support for the line of business within digital. And so she's that kindaconnection to that specific string. And then, yeah. And then I'm just here, so
> 
> Speaker 0: Awesome. And then Jennifer, you and Keenan, I know everybody knows you, but feel free to introduce your size. Well, just since it's new more faces.
> 
> Speaker 5: Yes. So Millie manages media analytics under the broader marketing group. We support across enterprise lines ofbusinesses. So on so forth, we are one of the many of ours stakeholders when it comes to reporting analytics data, wework with ours very closely when it comes to media data together with a law of the conversion data as well, you wouldsee us being involved in a law platform, configurations, especially when it comes to different metrics, whether or not it'sonline, offline, and also us providing quite a bit of business requirements over to the RS team. So we work very closelywith and drew for many of our projects.
> 
> Speaker 0: Well, thank you all. And I, I know I saw keen join. I don't think anybody else joined last minute, but what I wanna go overcuz there's, it is a larger project and there's been a lot of back and forth, but kind of grounding us on the meeting purposeand Dave, you and I were just chatting. So feel free to jump in at any point, but as you all know, what we're calling theprototype phase is having Imprivado manage the connection of 100% of the data for media team reporting and landing itin a single environment. And a single environment is the question mark. And I have visuals that Millie shared with Philnarrative to get cross functional alignment and make sure they're all in agreement. And then one thing we've talked abouta lot in emails drew, you may have seen is the idea of mid to long term, mid to long term we're scheduling meetings in acouple in the future later later date to look at once this prototype phase of stuff and running, and it's a working prototype, then looking at doing a gap analysis to feed, to see what is missing within T-Mobile data and how can we bridge theconnection so long term, we're just using internal data, but we need something up and running for media reporting aspect.
> 
> Speaker 0: And then we'll look at the mid to long term, which is where we will really heavily lean on working with Jennifer and drewand Mohan and the rest of the team, because this is S y'all's bread and butter. But so the purpose of the call is to reallydiscuss like which environment is the best. And like what's our options here. Milli had shared when there's some internalunderstanding that it would be an Imprivado environment. I know Fabio you had recommended it'd be a T-Mobile Azureenvironment. And so I wanna kind of actually make this a little more of a brainstorm discussion between Fabio you anddrew and your team what's the best solution. And I know there are a lot of, of caveats and nuances if it were to be T-Mobile and I wanna make sure that we have all of those laid out and then once we figure out what the best plan is, what'snext steps. So that me and Dan can hit the ground running for y'all any initial thoughts or questions.

> [!summary]- Summary answer 0-5 min.
> [[T-Mobile]] and Improvado came together to discuss how to best gather and store customer data for reports and analytics. T-Mobile's team is responsible for managing and coordinating data from various business lines, while Imprivado's team is responsible for connecting data from various sources. The goal of the meeting was to determine which environment would be best for storing and connecting the data. T-Mobile's team recommended that the data be stored in a T-Mobile Azure environment, while Imprivado's team recommended that the data be stored in an Imprivado environment. After discussion, it was decided that the data should be stored in an Imprivado environment. The next steps are to determine how to connect the data from various sources and to create a prototype phase to test the connection.


## Answer 5-15 min.
### Full answer 5-15 min.
- 5-15 min.
	- Full 5-15.
		- Speaker 2: It's it's great. I, I think we should just proceed. I, I just love how we have faced it out. It, it gives clarity on where we wantto be and, you know, given there are a lot of consideration security wise to make from a long term or midtermperspective, which can bring in additional complexity. So right out of the gate, it's, it's good to start with all thosecomplexities aside. So yeah, let's, let's discuss prototype phase and yeah, what's in there. I,
		  
		  Speaker 0: I also have man's initial questions. I don't know if y'all wanna start here. This is really y'all's domain drew and Mohi. SoI'm gonna let, y'all kind of take over, like, if we wanna talk about what would it be if it's T-Mobile's Azure and Iremember I'm not a technical person, so my verbiage may not be accurate. So please correct me. I'm gonna let, y'all kindof take over, but I just wanna pull up Mohi, sorry man. You's original questions.
		  
		  Speaker 2: Yes. So we, we worked with Manju in compiling these questions and I think we can come to it. I personally would preferjust a quick demo on how Imprivado thinks of their solution, whether it's a SaaS solution or whether it can plug into ourexisting Azure as a pass offering. You know, just, just trying to understand if you need a sync for all that Imprivado isdoing, whether it has to be relational or can it be a storage account, you know, just, just kind of cover those aspect. Andhopefully we'll answer some of these questions over there. If not then will, will revisit it.
		  
		  Speaker 0: Okay. If FIO, I have your diagram that you put together, if you want me at any point to pull that up
		  
		  Speaker 3: Yeah. Will be helpful. I can work through it, Laura. So without going too much into detail, this is the suggestedarchitecture where on the left main diagram here in bravado is basically our full SA product. So basically where the usercan establish authentication to the variety source from which we extract data from and is our extraction load component. Then what we see in the right, in the, in the park, one project educated, dedicated Azure SQL storage is because we needan environment where we can load the data that the extract from the variety of sources. And in the previous conversation, we understood that in the long term, your areas storage is based on Azure SQL. So our recommendation was to stick tothe same type of technology, even if it's a prototype, because if the moment in time tomorrow, we want to switch from theprototype phase and you want to have all these data that we are extracting and will be much easier transition if the, theunderlying technology is the same.
		  
		  Speaker 3: So that's why in the previous conversation, we, we suggested to stick to a Azure SQL from, from architecture perspective, from the product standpoint, how, how it works. We do support any type of storage and we support Azure SQL Azureblob, snowflake, Google queries. So the way we load the replicated data to the, our customer destination, as we call isreally dependent by the technology that's been chosen. And even if in a moment in time, we don't support a specificdestination or our customer has specific requirements that can become from architectural security perspective. We havethe ability to, to tweak it, consider the, the standard. Let me say, approach that we have, is it clear so far or there is anyquestions
		  
		  Speaker 2: Just to one clarifying question. So you mentioned you do support Azure SQL storage. So essentially your me, you meanAzure databases yes. That work on relational SQL technology, correct?
		  
		  Speaker 3: Correct. Yeah. The current state, we support Azure SQL and Azure blob as a, as a technology. And so it really dependswhich one, which one do you prefer for this project?
		  
		  Speaker 2: Sure. And I mean, so the, the, the data landscape that we are working on, right. It's, it's like really big data, unless until weare like extracting really aggregated reporting kind of data. So given the data landscape and given what we want to bedoing, like you said, beyond the prototype phase, I think Azure storage is a better choice just because it gives the kind ofscalability that we want and it's immutable, right? So once you write it, then it depends on us on how we are going toconsume it. So my preference would be to use Azure storage accounts where we can set up dedicated containers for youruse and, and have the data landed there rather than working on a relational SQL technologies. Because the moment wetalk about relational secure, SQL technologies, it has limitations depending on whether it's oil TP or all app model. Soyeah.
		  
		  Speaker 3: Yeah. Quick question. When you say storage, you mean blob,
		  
		  Speaker 2: Correct? Yeah. Blob or ADLs either of the two, depending on what you support
		  
		  Speaker 3: At the currency, we support blob. We don't support the S but it's something that we can mitigate. And sure. So it's, I mean, it request and development time, but is something that is part of our standard approach. We cause we want to support themost destination as possible. And another important information I would like to share, do we have the possibility toreplicate the data to different technologies? So potentially at the same time, as you're on the left, we store the data on ourend, right? When we extract from, from the external sources, our loading mechanism can support multiple destination atthe same time. So potentially we can replicate to both Azure SQL and Azure blob or Azure SQL and Azure ADLs at thesame time. So this is another option that we can keep in consideration is gonna be helpful.
		  
		  Speaker 2: Okay. So you are keeping all of this data on AWS cloud and it's a SaaS offering,
		  
		  Speaker 3: Correct? Yes.
		  
		  Speaker 2: Do you have any similar SA offering for Azure cloud?
		  
		  Speaker 3: No. It is a full size. So AWS is our own architecture where our product and solution is built on.
		  
		  Speaker 2: And so I'm guessing you will have a set of net IPS for us to white list because it will not be supported network wise on thesame technology stack, right?
		  
		  Speaker 3: Correct. Yes. There are a set of IP address that you should in order to give us the ability to replicate the data to your ownenvironment.
		  
		  Speaker 2: Okay. I, I believe we have had some review with our DSO team in the past. I will check on those while we go from there, but for now, as long as you can support, and it's more of a replication that you're doing on either storage or SQL, I, I thinkwe should be good.
		  
		  Speaker 3: Yeah. It's just replication. And I can share the documentation about how Azure, broad storage and Azure SQL workstoday. What are the parameters that we need? Because of course this configuration varies by each technology, right. Andso we can follow up with these documentation. So you can have a look at the moment time you would prefer to proceedwith ADLs is something that we can accommodate in any case.
		  
		  Speaker 2: Yeah. I mean, if, if you think of it long term as well, ADLs brings about the hierarchical name space. So once we startgetting data from you, you know, knowing Imprivado will be providing data for multiple parties, like, you know, so if weare to go going and organizing it by folders, then we can set up our back based on those folders, depending on who needsaccess to it and, and what the business wants rather than, you know, just with blob storage, there's just container and ornothing else. So that's why we have been transitioning to ADLs because of the hierarchical name space. So it would begreat if you can support that in, in near time near future.
		  
		  Speaker 3: Yeah. I, I, I think, I mean, it is a good, it is a good approach to keep the short term and long term separate of coursealways keeping the long term in mind, because from the project implementation standpoint, as our data analyst team, working with your business users, we are going to implement data transformation. And on top of it, there will be doubledashboard connected to it. Do we need, we need relational database. So probably for the positive phase makes more senseto stick to Azure SQL because I dunno it's just a suggestion, but to Azure SQL, because on top of it, we can rise SQL andwe can implement this T-Mobile data model that is based on the business requirement that we got. Cuz otherwise, if wewill start with blob, it requires some action from your end, in order to give to our team a relational or set of table wherewe can rise SQL.
 
### Summary answer  5-15 min.
T-Mobile and Imprivada are discussng how to move forward with their partnership and data sharing. They discuss the pros and cons of using Azure SQL storage versus Azure blob storage. Imprivada suggests using Azure blob storage because it is more scalable and easier to transition to in the future. T-Mobile agrees that Azure blob storage is the best option for their needs. Imprivada will provide documentation on how to configure Azure blob storage for their use. T-Mobile is also interested in using Imprivada's ADLs service in the future. Imprivada is currently only able to support Azure blob storage but may be able to support ADLs in the future. T-Mobile and Imprivada agree that Azure blob storage is the best option for their needs at this time. Imprivada will provide T-Mobile with a set of IP addresses that they will need to whitelist in order to use their services. T-Mobile and Imprivada will continue to discuss their data sharing needs and how to best move forward.

### Ful answer 15-25 min.
- 15-25 min.
	- Full 15-25 min.
		- Speaker 2: Can, can, can you maybe drill down a little bit on that? It's not clear to me your ask.
		  
		  Speaker 3: Yeah. The step number four here in, in the diagram where we see T-Mobile data model, basically we have data analyststhat are gonna write SQL code in order to manipulate and transform the data based on the business requirement we, wecollect and, and the result of this step are a new set of views or table that will be used by the table dashboard that wealready start to build. And so Tablo require access to a relational database or database, not, not a file storage, not like a BLstorage. So if we are going to replicate the data using blob, we still need an, a layer that give us the ability to rise sequel.
		  
		  Speaker 2: Okay. So I think we need to take a step back here because it's expanding on the scope of prototype from the prototype. Iunderstood the scope is whatever Imprivado will be doing. Azure is just a place for the final output to come through. Butfrom what I'm hearing from you is once it comes through, once you have a data model defined, then you are going tobuild a consumption layer using Tableau that will consume the data that we have put in this Azure environment. So as itstands right now, it's not, it's not a right only use case. It's a read, write use case. And, and, and then the considerations ofwhich Tableau environment is being spoken about here also comes into play because like we have Tableau our side. Andso, you know, even, even taboo as an infrastructure will, will come into play here.
		  
		  Speaker 3: Yeah. Co correct. And that's why from the, again, for the previous conversation, the, the, the best approach that weidentified for the prototype was to stick to Azure SQL because it give us the ability to write custom views and, and havinga dedicated Azure SQL environment from your end, specifically for the prototype.
		  
		  Speaker 2: Hmm. And, and what kind of size limitations you are looking for? Azure SQL database.
		  
		  Speaker 3: That's a good question. We can follow up because it's really based on the data volumes. So we should double check.
		  
		  Speaker 2: Yeah. And because that's going to D the kind of Azure SQL offering that we can provide, you know, and, and given thisrequirement, I really don't think there is much difference with respect to what we reviewed with Jennifer, because, youknow, Jennifer outlined both the read, write, use cases with us and, and that's where our recommendation was coming. Soif you need a sequel system, you know, for either of the use cases, then I, I do not see much difference between what ourshort term goal is or what our long term goal is in terms of what we want to be doing here.
		  
		  Speaker 3: Okay. This is even better. Yeah. We need a SQL environment in order to, to, to ride those customer transformation andbuild this data model. And from the size perspective, I, if you have a list of points that you want to double check, I can, we can check internally with our tech team and provide Allion that we can.
		  
		  Speaker 2: Sure. So, given, given there was new information for me, especially on how you plan to use the data model and, and theconnectivity with taboo, we'll have to kind of review that and, and provide that questions to you. I don't have it handyright now, I can guess, but I would rather keep the guesswork out. And I'll, I'll share the document, the questions with youlater. Any, any reason why taboo? Why not? Like given, it's flowing through Azure? Why not power BI or any Microsoftstack technology?
		  
		  Speaker 3: I been discussing during the presales phase with the,
		  
		  Speaker 0: Probably I can actually chime in here originally the, it came down cause that's what we, the media org understood asanalytics teams preferred. Jennifer's told me recently that that's actually not the case. So while we've been going withTableau, the, if I need to check with I Imprivado, but like, if we need to look at power BI, because that would be simpler, we're not opposed to it. So just understand that there's, there's two options here. It's just, we've been going with Tableaubecause of leadership's preference, but that's not that doesn't have to be the answer is what I'm saying.
		  
		  Speaker 2: Sure. So in that case, and, and that's the reason why I ask never hurts to ask the question. So yeah,
		  
		  Speaker 0: No, just wanna make sure that whatever Imprivado is done, that doesn't derail. Yeah. If we cha if we decide to change. SoI just wanna caveat that.
		  
		  Speaker 2: Yeah. Because I I'll give you the new nuances of it. So what's happening here is AWS is where all these connectors anddata acquisition is happening. It's getting relayed back to our Azure infrastructure where transformation and datamodeling is, is happening. And then the data is made, ready to serve. But if you choose Tabu, then Tableau sits on our on-prem infrastructure. So the data will, again, has to move, have to move from Azure to on-prem. So you see, there are liketwo steps of egress. It will increase, cost, increase the latency. Whereas if it is on power BI, where we have nativeconnectors with Azure stack and, and it uses the Microsoft backbone for all the data transfer, given we have somenetwork level connectivity, which is called express route. I think the performance overall will be better if you choosepower BA so that's, that's the motivation behind it. But if you choose taboo, it's, it's not like day and night, kind of adifference. It's, it's just something to consider from a cost and, and long term perspective.
		  
		  Speaker 0: That's good to know Eric and we'll chat like with the team, just cuz we, we have Jennifer informed me of like whyTableau was originally the push and I doesn't really see that there's a valid reason. I just wanna make sure that that's notgonna mess of any work that y'all have already done. So no changes, but let's just chat offline and figure out like what thebest solution is for like what we're doing.
		  
		  Speaker 2: So from what I have learned, have you, based on your explanation, if you get a Azure sequel, then you don't need a Azurestorage, correct?
		  
		  Speaker 3: Correct. Yes.
		  
		  Speaker 2: Okay.
		  
		  Speaker 3: Correct. I mean potentially if you want also the, the, the blog version, we can push again in parallel to both.
		  
		  Speaker 2: Yeah. I
		  
		  Speaker 3: Mean,
		  
		  Speaker 2: I hit your point. So that will come into play, especially when, you know, we have analytical use cases where we just wantto hit the data and, and not the custom views or rely on SQL compute to extract the data. So when such a use casehappens, sure. We can directly replicate the data to Azure storage and, and get going from there. But if, if the objective isto fetch the data based on the data modeling or the transformation that you'll be doing in the sequel layer, then no matterwhat the consumption has to be from the sequel layer.
		  
		  Speaker 3: Correct.
		  
		  Speaker 2: Yeah. Okay.
		  
		  Speaker 7: So
		  
		  Speaker 8: I have, I have one, one question just to, because I think, I think we're on the same page and this is super helpful, but to, tolevel set, I wanna make sure that the, the initial assumptions by some dif by our, by the two different teams, Fabio, I thinkyour original recommendation was the solution. We just talked through where the Azure instance lives on the T-Mobileside. I think I, I just learned that Millie's assumption was that this Azure lived on the Imprivado side. So I wanna makesure that is, I wanna make sure that kind of the reasons for that. And she was under the assumption that the cloud storageagreement that we've already signed with Imprivado covered that. So just wanted to kind of pick your brain around. Maybe the reasons why that is not the ideal solution or if that's also on the table as a potential solution. And it maysimplify things.

### Summary 15-25 min.
- [x] [[Dmitry Korzhov]] please try to add with links to gong next time, so ti wil be easier to find. asi undertand it is simple just copy past. [completion:: 2022-09-14]
- [ ] ![[Pasted image 20220913222435.png]]
The Diagram depicts T-Mobile's data model in which data analysts write SQL code to manipulate and transform data collected from business requirements into new views or tables that can be used by Tableau dashboards. Tablo requires access to a relational database or database not a file storage or BLOB storage in order to replicate the data. The best approach for the prototype is to stick with Azure SQL because it will give the ability to write custom views and have a dedicated Azure SQL environment. The size limitations for Azure SQL databases are based on the data volumes. Power BI is an option for the prototype if Tableau is not preferred. AWS is where all the connectors and data acquisition is happening. The data is then relayed back to Azure infrastructure for transformation and data modeling. If Tableau is chosen as the method for data consumption, the data will have to be moved from Azure to on-prem, which will increase cost and latency. If Power BI is chosen, the performance will be better because of the native connectors and Microsoft backbone. Azure SQL does not require Azure storage. The initial assumption was that the Azure instance would live on the Imprivado side, but it is better if it lives on the T-Mobile side.

### Full answer 25-35 min.
- 25-35 min.
	- Full 25-35 min.
		- Speaker 3: Yeah. Thanks David, for bringing it up and our managing Azure was not part of the solution. And so I dunno where thesemessages being, let me say misunderstood because we don't, we Don not offer Azure manager service. We do offer otherdata warehouse technology. We mentioned in before in the past Google query and snowflake, but the reason why, becausethose are full SA full cloud. While instead with Azure, we need to establish the box operation based on Azure, whereactually we have a company based on AWS. That's the, the reason why we do not offer Azure manager service. I knowthat Microsoft offer Azure SQL in manager service in the same way we will be query in snowflake. So potentially issomething that we can explore if you don't want to spin up Azure SQL environment dedicated for the project internally. But to be on the same page is, is an offering that we don't have based on Azure technology. So these environments shouldcome from T-Mobile. If there is a friction point and Microsoft has an offering that doesn't requiring Prova to, to havedeveloped resources, basically managing a new type of technology that we don't master today is something that we canexplore at the same time. It makes sense.
		  
		  Speaker 8: Yep. Yeah.
		  
		  Speaker 3: So probably the, the conversation get a little bit confused. The moment time we were exploring other option, because wedo offer this service again for Google require snowflake, but not for Azure, but the moment by Microsoft as is offering, we, we can double check it if you don't want to have, and in-house environment dedicated for this project.
		  
		  Speaker 2: So Dave, there are, there are pros and cons of it, you know, like Imprivado is already a SA solution. Now, if you rely onposting the data, even on a SAS solution, then the control of data will always be with that environment. It it'll not be withyou. So if you want to use the data, then you'll always have to read the data from that SAS kind of, you know, managedsequel instance. That's the better way of putting it. It will, it will not be on how you want to configure it. So there, thereare pros and cons. Like I, I see the motivation of why having it on, especially if it is covered under our contracts. I'm notsure, but if it is, then there are motivations why we want to have it out of the gate in, in that environment for now, butlong term, it, it makes sense to have the control of our data in our hands. Yeah. That's one thing to put it and Fabio oneclarification I have. So say suppose if the sequel option doesn't work and, and what we can provide you is just Azurestorage. How does that change things on your end? Or what, or, or does that stop you from delivering the solution?
		  
		  Speaker 3: Yeah, we need a sequel layer because it's where the data analyst has gonna as to, to be discussing transformation.
		  
		  Speaker 2: Okay. So you need Azure SQL without that you'll not be able to deliver the consumption layer.
		  
		  Speaker 3: Correct.
		  
		  Speaker 2: Okay.
		  
		  Speaker 3: And also to, to get back on what you were saying before mahi, I totally agree with you having, having T-Mobilemanaging these, these Azure storage is I think is convenient for everyone also from the, from the security perspective, butalso considering hearing the diagram, the point number three is there are some business dashboards that we rely on datathat are not coming from Prova product, but are already stored in a T-Mobile environment. So if we will move forwardwith Azure SQL management in prodo, it means that somehow this provato manage environment must have access tosome data that are today, first
		  
		  Speaker 2: On the T mobile side. Yeah. Yeah. I completely agree with you. Yeah.
		  
		  Speaker 3: So I think it's much better if you guys keep control of it and, and give access to our team to, to our, to the data that Areedby us, to the data that are already available in T-Mobile just to build this data model layer where you have full control ofwho has access and all the user grants.
		  
		  Speaker 2: So from a data model perspective, will you be hosting the data model through any Cing technologies or will all thequeries from taboo or power be whatever it is directly hit the Azure Quin?
		  
		  Speaker 3: So that's a, that's a good question. And we can, we can share more technical details basically without going to match intodetail. We are gonna write SQL directly in, in Azure SQL. So there will be custom view custom table. Sometimes it reallydepends by the use case and the volume. In some cases, there are also materialized view. So it really depends by thecomplexity that, of, of the use case that right now, we are not able to give you all those type of details. But our typicalapproach is really based on what are the business requirement, how the dashboard has been designed and the volumes inorder to have good performances. So, but is SQL written. That is SQL code that will be executed on Azure to answer yourquestion
		  
		  Speaker 2: And how will you deploy these views or transformation into the SQL? Will you, will someone be manually logging intothe database or is it something managed on the IPRO side that automatically deploys the solution
		  
		  Speaker 3: We used get D BT and GitHub from this perspective, I need to double check with our solution architect, how exactly howthat works. There are basically two approaches in, in some situation, these how to say this custom view, let me say, arebuilt on our side. So on the left side of this diagram, if those custom view rely only on data that are extracted by bravado, in some other situation, if this custom view needs to be blended with data that are already on T-Mobile side, then ofcourse this call will be on only on, on Azure. So when we have in this type of situation, of course, it's better to stick toonly one approach. So probably in your scenario will be only on, on Azure, but how technically is gonna work, the, thedeployment, you need to double check, but get, get DBT and GI are the two main, something about technology that weuse.
		  
		  Speaker 2: Sure. And, and I'm asking this question because, you know, the, the moment we talk about platforms on two differentclouds, authentication becomes a challenge. And I'm guessing you'll not be able to work with ad in any way. You willneed some static SQL accounts to work through it, right? And, and anytime you start talking about SQL authentication, the audit or, or the entire elementary behind who is doing what is, is lost, because what we see is just the SQL account. Sothe developer experience coming out of the same platform, which is hosting your consumption layer is, is something to becognizant of. And, and that's why I wanted to check whether you have that auditing capabilities through jet hub or DBT, whatever you are using, because that essentially means no developer will log in directly into the SQL server,
		  
		  Speaker 3: Sorry, Mo I, I get a little bit lost, but I'm sure that our solution architect and developers are able to, to provide more detailshow this, these specific things works. And if it's possible, if you can send me this follow up question, I'm happy to, toprovide you the specific details. So if you have any specific requirements from the security perspective, we can elaborateon that.
		  
		  Speaker 2: Okay. Sure. I mean, a lot of it, as of now, given you have put a constraint that it has to be Azure SQL, you know, a lot ofit depends on the size of data because I'm not sure if you're aware, but on the Azure side, we have Azure databases, whichhas a limit of four terabyte for business critical workloads. With higher IO, we have a terabyte limit on general purposecompute. And, and if the data that we are talking is going to be beyond that limit, then, then we have to rely on hyperscalecompute, which may use a bit of PP processing. And, and what that does essentially is the type of oil TP, or, you know, high transaction workload that you're planning to build. It will impact your ability to deliver the latency from a reportingside and so on. So that's why the size of the data is a key factor in ING. What the right solution for you is going to be

### Summary answer 25-35 min.
[[Azure SQL]] is not currently offered as a managed service by Prova, but this may be something that they are able to explore if it is a necessary requirement for T-Mobile. Without a managed Azure SQL environment, T-Mobile would be responsible for maintaining and managing the environment themselves. Some of the data that Prova would need to access for their solution is currently stored on T-Mobile's side, so this would need to be taken into account when considering whether or not to use Azure SQL. Prova typically uses SQL code to answer business requirements and they deploy this code using either DBT or GitHub. Authentication can be a challenge when working with platforms on different clouds, so it is important to consider whether or not the auditing capabilities of the deployment tools being used are sufficient.

### Full answer 35-40 min.
- 35-40 min.
	- Full 35-40 min.
		- Speaker 3: Understood. Yeah, this is helpful. I will follow up internally with the team. I'm not expecting this huge volume of dataalso because most of the time from aggregated from the marketing sources, those type of ag, those data points areaggregated. So are not log level type of information, but are good point that I, I can double check. Are you able to, to sendme those?
		  
		  Speaker 2: Yeah, yeah. I will. I will send it out. And do you support data bricks SQL point?
		  
		  Speaker 3: We do.
		  
		  Speaker 2: So you do support data, bricks, sequel endpoint.
		  
		  Speaker 3: Yes.
		  
		  Speaker 2: Okay. That's, that's good to know.
		  
		  Speaker 3: We support also databases. Yes.
		  
		  Speaker 2: Okay, cool. I think that will simplify a lot of things. We don't have to work on the storage constraint that way. So yeah.
		  
		  Speaker 9: Are you thinking Delta DV instead?
		  
		  Speaker 2: Yeah. Yeah. I think instead, yeah, because it'll set up, set us up for scalability. Yeah. Storage wise, as well as computerwise and
		  
		  Speaker 9: Separation
		  
		  Speaker 3: Yes, I can. I can follow up and with all the destination we support today and also how those destination works. Okay. Andso, yeah, and we can D from there.
		  
		  Speaker 2: Okay, cool. And your Nat gateway IPS have been approved by DSO on our site? Correct.
		  
		  Speaker 3: Can you repeat my head? Sorry.
		  
		  Speaker 2: Your Nat gateway IPS have been approved by our T-Mobile DSO team for network level transactions. Correct?
		  
		  Speaker 3: I think we communicated AP probably a couple of days ago. So I don't know the
		  
		  Speaker 0: IP
		  
		  Speaker 8: Over
		  
		  Speaker 0: The DSO. Sorry, Dave, you wanna chime in?
		  
		  Speaker 8: I was gonna say, I don't believe so. I don't think that was part of the initial analysis since, since the IPS were just, justshared in the past few days,
		  
		  Speaker 2: I think we'll have to go through DSO again with the new information, Dave, because any white listing that we do withinthe T-Mobile system, the moment, you know, we try and hit a new endpoint, which is essentially the new set of IPS here. It will start flagging the traffic. So we need the approval beforehand even before we test out any workflow.
		  
		  Speaker 3: Okay. Makes sense.
		  
		  Speaker 8: Okay. So it sounds like Fabio, you can send over those technical specs is the, is the size estimate still a, would that be anice to know Moit or
		  
		  Speaker 2: It'll, it'll still be nice to know, because that will enable us irrespective of, you know, whether it's data, bricks, Delta, orAzure sequel, it'll help us size up the right compute resource for you. So it, it is still essential to D combining the right setof technology.
		  
		  Speaker 8: Okay. And then based on, based on the, the documents that FIO will send over, sounds like you could follow up with anyadditional questions. Yeah. You might have. Yeah. Great.
		  
		  Speaker 0: Awesome. So just to kind of recap, FIO, specs and size limits, second MOG, you'll send any questions that you havefollowing that Dave and Dan and I will work on the I P IDs for DSO. And then from there either we can have this viaemail or another meeting, but I just wanna make sure once we get approval, that everything's good to go. We have clearunderstanding from res on what you need from us to get us started for Imprivado.
		  
		  Speaker 2: Yeah.
		  
		  Speaker 0: And I can follow up with y'all separately to work through that.
		  
		  Speaker 2: Cool.
		  
		  Speaker 0: Awesome. Imprivado any questions or like thoughts?
		  
		  Speaker 3: No, I saw clear from my side at the moment, probably a follow out that we can take of line is more about double power BIto evaluate the impact. Yeah.
		  
		  
		  Speaker 0: Let's let's cause I wanna make sure we're considering all, all sides of it. Yeah.
		  
		  Speaker 5: One question I have since it seems like there's no longer, further back and forth and therefore there's still some time forme to ask a question. Wasn't there some assessment where like 1 billion records estimate for the cloud environment interms of sow. So just the reason why I'm bringing this up is while we're working with aggregate data, which, and not loglevel data. So indeed we're, we shouldn't have a crazy amount of records, but it gets hairy very quickly, depending on thedimensions that are requested by different business groups. So is there an updated assessment, do you think? Or the 1 billion is something that is still reasonable because I think you guys have been talking to business stakeholders already.

### Summary answer 35-40 min.
The team is working on understanding the data requirements for Imprivado in order to determine the best way to set up the data pipeline. They are considering using [[Databriks Delta lake]] due to the scalability it offers. The team needs to know the size estimate in order to determine the right compute resources. Fabio will follow up with any questions the team has. Once the IP addresses have been approved, the team can start working on the data pipeline. The team is still considering the 1 billion records estimate for the cloud environment.

### Full answer 40-45 min.
- 40-45 min.
	- Full 40-45 min.
		- Speaker 3: I don't know if we have an updated assessment from this perspective, because it's a good point. We, we can, now that wehave a more, more clarity, let me say from the business acquire in the dimension that we need, probably we can kindarevise it. So we, we, we, we can double check it, but yes, I think one bill for the information that we had at the time, it wasthe, our best estimation. Let me say, but at the same time, you, there are some type of dimension that it's kinda impossibleto estimate, like, you know, keywords or right. Geo city. So it's very dependent on how the user out there interact with thecampaign. So, but it's a good point. I think we can keep this 1 billion of record as, as a ballpark number in terms ofnumber of total roles that you're going to, to extract. And, but how to convert this one in, in terabytes is something that weneed to double check with the team. And, but yeah, it's a, is a good point, Jen, we can, we can, we can double check if wecan revise the estimate here.
		  
		  Speaker 5: Just some sharing too, is on our engagement with res too. We were particularly mindful of the dimensions that we have toask because it gets so granular to the point where not only, it's not very usable by the time that we get into visualizations, but at the same time, the way that you guys are working with business requirements, it's the other way round where Ithink it starts from visualization and go from there. So yeah, it'll be good to have some, some better assessment given. Now you have more visibility to the business requirements too, so
		  
		  Speaker 3: Absolutely. Yeah, yeah. This will be part also the documentation, but in general, our approach journey is when we haveiCal in many, in many type of dimension, right? So the moment in time we, we have, I don't know, the asset level, we, weare not also extracting just the campaign level. So we just try to optimize the number of tables, a number of, but we, it is agood part. We will share this documentation absolutely. Then for the input. Okay. All
		  
		  Speaker 0: Right. Awesome. Well, I think that covers it. I hope, I guess, speak now since we have all the important people on the call, but I will follow up with everybody that's on this call with next steps and we'll just keep things moving from there, but Ireally appreciate everybody on this call, basically dropping everything to, to get this moving and just wanna say, thankyou. Is there any other questions that y'all had last minute, saw someone come off mute?
		  
		  Speaker 5: Can we reasonably expect there might need to be a second round of technical conversations once the information isshared across the two teams?
		  
		  Speaker 0: Yeah, I, yeah. I mentioned that you can either give you an email, but it gets more technical than probably more theinformation the te sorry, the specs and the questions moving first, and then I'll follow up with if a call is needed.
		  
		  Speaker 5: Okay. I, I just don't necessarily want to lose momentum given it's fresh on Fabio and Mohi, mine and, and Emery as well. So,
		  
		  Speaker 0: Nope. It's it's number one priority on the media work. So it's not losing momentum. Yeah. Appreciate it. Mohi. If youwouldn't mind, since you'll be the one that gets the recording, if you could forward that to me and I'll make sure it's sentout to everybody. Yeah. Send a hand, quit, enjoy, and I'll do that. Awesome. Thank you. And in prat, I'll make sure youhave access to it as well. So if you need to refresh on anything. Thank you. Thank you. Awesome. Thank you all. We'lltalk soon. Thank you.

### Summary answer 40-45 min.
The estimated amount of data that would need to be processed is 1 billion records, which would be converted to terabytes. The team is still working on refining the estimate and determining how to best convert the data. There may be a need for another round of technical conversations once more information has been exchanging between the teams. The goal is to keep the momentum going so that the project does not lose any forward momentum.