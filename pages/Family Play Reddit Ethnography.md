public:: true

- # Motivation
	- While previous work has analyzed gaming in the context of families, it always did so in artificial contexts (i.e. interviews, laboratories, questionnaires). Other contexts (such as reddit communities) can provide further insight into what games families seek, how they discuss it and what constraints exist.
## Research Questions
	- **How are people talking about playing with their families, specifically in reddit communities ?**
	- What are the possibilities for promoting family play?
	- How are games used as a vehicle of communication and expression between family members?
	- How are gaming experiences constrained by the player's family?
# Study
	- ## Data Collection
	  collapsed:: true
		- ### Reddit
			- #### Data Collection/Selection
				- **Posts data was collected on [[Feb 14th, 2023]] **
				- **Comments data was collected on [[Mar 20th, 2023]] **
				- Analyse posts that talk about family-constrained experiences in gaming subreddits.
				- **Subreddit** selection:
					- Collection of reddit gaming communities provided by /r/Gaming with over 1000 entries.
					- The communities with more than 1000 posts are then sorted by number of relevant (i.e. posts with at least one of the keywords in their title) posts divided by total number of posts.
				- **Post** selection:
					- Select from first 20 posts of each subreddit
						- Select 10 posts maximum
						- Until we include 20 subreddits with at least 2 relevant posts
				- **Comment** selection:
					- Select the top-level comments of each selected post, sorted by "top" (most upvotes)
				- **Exclusion** criteria:
					- Exclude posts that:
						- Are obviously not related to digital gaming
						- Doesn’t have gaming experiences shared with or constrained by family
						- Opportunities for family play
						- Not video
						  collapsed:: true
							- (gifs or videos shorter than 30 sec are allowed)
	- ## Data Analysis
		- Two authors coded 25 (one for each subreddit) of the selected content and discussed results. First author then coded the remaining content
		- Mentions of games were counted (max 1 per post) and more posts were included from these game's subreddits (how many posts? How many games?)
		- ### [[Codes]]
		  collapsed:: true
			- So far, codes are organized by:
				- How the experience is shared
					- [[Shared Experiences/Co-playing]]
					- [[Shared Experiences/Spectating/Active Spectating]]
					- [[Shared Experiences/Projecting game into Real life]]
					- [[Shared Experiences/Sense of wonder and novelty]]
				- Which media component the experience is being shared through
					- Have some doubts about when this could should be used
						- If I use this every time someone mentions gameplay, for example, it might get muddied really fast (?)
					- [[Media Component/Gameplay]]
					- [[Media Component/Narrative]]
				- How family affects the experience
					- [[Affected by Family/Grief Affecting]]
					- [[Affected by Family/Facilitating others' play]]
					- [[Affected by Family/Conform to play together]]
				- Social outcomes
					- [[Social Outcomes/Building Shared Memories]]
					- [[Social Outcomes/Shared Reminiscence]]
					- [[Social Outcomes/Subverting Expectations]]
					- [[Finding Commonalities]]
						- How is this different from [[Parallel between Game and Life]]?
				- [[Learning Outcomes]] - probably irrelevant
				- [[Other Outcomes]]
					- encouraging grandpa to play for cognitive benefits
				- Personal aspects that affect experience
					- [[Personal Aspects/Skill Levels]]
					- [[Personal Aspects/Familiarity]]
				- [[Game Accessibility]] - in terms of providing access to games (not disabilities)
					- [[Game Accessibility/Cultural Terms]]
					- [[Game Accessibility/Content Suitability]]
					- [[Game Accessibility/Cost]]
				- Entry points for non-gamers - some overlap a bit
					- [[Entry Point/Interest in theme or narrative]]
					- [[Entry Point/Another Medium]]
					- [[Entry Point/Connection with past]]
		- ### Data description
			- Gaming together can take many forms
				- Many posts of family spectating
					- Some describe how the spectator would comment the gameplay
				- Other posts mention "playing together" single player games
			- Interactions are mainly organically occurring
				- Moments of experience sharing are typically not planned. For example, someone walked into or is simply sharing the gaming space.
					- In this sense, a shared gaming space (where a console typically is) provides an "interaction generator" (terrible name, describe it differently).
						- Jesse Schell calls this type of gaming space the "Hearth" in [The Art of Game Design: A Book of Lenses](https://www.amazon.com/Art-Game-Design-Lenses-Third-dp-1138632058/dp/1138632058)
			- These interactions can take many forms
				- They centered around aspects of the game itself (e.g. Narrative, visuals, gameplay). Some parents and children specifically mentioned how playing together created moments of bonding and promoted talking about things that would not be talked otherwise
				- See [[Shared Experiences]] hierarchy for details on what forms were found
		- ### Themes:
			- Is it possible to **categorise** what **social interactions** or dynamics **games can afford**?
			  collapsed:: true
				- For example (from the top of my mind): Stardew Valley is a relaxed game that gives you just enough to do to keep you focused on something, but not so much that it is the only reason for interaction. On the opposite side, something like League of Legends takes too much space in the conversation.
				- This ties in with the difficulty people have in selecting games
			- **Difficulty finding games** that can meet different people's preferences
			  collapsed:: true
				- A bit of a mouthful, but many posts are looking for a game to play with someone else, listing the preferences of each person, games they enjoyed or didn't (and some reasoning).
				- I'm not sure that there is any new information to add here, though. Besides that this problem exists.
				- {{query (property :tags [[Selecting Game]])}}
				  collapsed:: true
			- **Gaming stigma still prevalent** to some extent, but some are able to overcome it
			  collapsed:: true
				- {{query (property :tags [[Gaming Stigma]])}}
				  collapsed:: true
			- Many different ways to enjoy gaming (e.g. narrative, gameplay, visuals) provide **multiple entry points for "non-gamers"**
			  collapsed:: true
				- {{query (or (property :tags [[Entry Point]]) (property :tags [[Entry Point/Another Medium]]) (property :tags [[Entry Point/Interest in theme or narrative]]) (property :tags [[Entry Point/Connection with past]]) (property :tags [[Entry Point]]))}}
				  collapsed:: true
			- Games provide many **prompts for conversation**
			  collapsed:: true
				- How to design for this?
				- Can the length of games help?
					- Generally games are not finished in one play session, can that provide moments for discussion between players/spectators?
				- {{query (property :tags [[Shared Experiences/Shared Gaming Space]])}}
				  collapsed:: true
				- {{query (or (property :tags [[Social Outcomes]]) (property :tags [[Social Outcomes/Building Relationship]]) (property :tags [[Social Outcomes/Relationship Maintenance]]) (property :tags [[Social Outcomes/Building Shared Memories]]))}}
				  collapsed:: true
			- It is possible to play games (sequels, mostly) as a way of **remembering or paying homage to someone that has passed**
			  collapsed:: true
				- {{query (or (property :tags [[Affected by Family/Grief Affecting]]) (property :tags [[Social Outcomes/Sharing in Hard Times]]))(property :tags [[Affected by Family/Grief Affecting]])(property :tags [[Affected by Family/Grief Affecting]])}}
				  collapsed:: true
			- **Coping with hard times together** (or individually)
			  collapsed:: true
				- Not sure if I found escapism from toxic household?
				- {{query (property :tags [[Social Outcomes/Sharing in Hard Times]])}}
				  collapsed:: true
			- Gameplay is interrupted by family randomly, but **games do not acommodate spontaneous breaks**
			  collapsed:: true
				- This is especially relevant in singleplayer games, but also happens in multiplayer games (how to acommodate spontaneous breaks in a match of LoL?)
				- {{embed ((6450fa15-9f20-46c6-9bc3-6629b7c226aa))}}
				- {{query (or (property :tags [[Game Accessibility/Lack of Time]]) (property :tags [[Affected by Family/Stopping Gameplay]]))(property :tags [[Game Accessibility/Lack of Time]])(property :tags [[Game Accessibility/Lack of Time]])}}
				  collapsed:: true
			- **Reentry in gaming in old age**
			  collapsed:: true
				- {{query (and (property :tags [[Personal Aspects/Age]]) (or (property :tags [[Entry Point]]) (property :tags [[Entry Point/Another Medium]]) (property :tags [[Entry Point/Connection with past]]) (property :tags [[Entry Point/Interest in theme or narrative]])))}}
				  collapsed:: true
		- #### Questions & Doubts:
		  collapsed:: true
			- {{embed ((643d1855-0939-45ac-846b-b0e33d8ad185))}}
			- {{embed [[ljz9lu-gamingsuggestions]]}}
				- I'm not sure if this family dynamic is worth capturing. And if it is, I'm unsure of how to code it. I was thinking of something like escapism?
			- {{embed [[hwo728-thelastofus]]}}
				- I coded part of this post as [[Gaming Stigma]] because I couldn't figure out another name to give it. It is not stigma per se, but any other code that I'd create would just be merged. What should I call it then?
			- {{embed [[c97c4k-gaming]]}}
				- Is there something here that I'm not capturing? I'm not sure that these codes are enough to capture how the parent is affecting the child's game
			- {{embed ((6450ed16-b39c-4130-b1f0-6fd33977c065))}}
				- Would Amiibos fit into this code?
			-
		- #### Interesting Posts:
		  collapsed:: true
			- {{embed [[rujegi-skyrim]]}}
			- {{embed [[i1msn4-PS4]]}}
			- {{embed [[cpwmu4-xboxone]]}}
				- I think that wanting to talk without interrupting the game is something that many families go through. Especially with the rise of competitive games and how long they take to finish.
					- Personally, I know I've seen this issue many times in my household.
			- {{embed [[aowque-KingdomHearts]]}}
			-
# Limitations
	- No way to verify the content is real/true