DetectiveYou
~~~~~~~~~~~~~~~~~
This is a game I created on python.

>>> def welcome():
	print ('Welcome')
	print ('What is your name detective?')
	myName= input ()
	print ('It is good to meet you,' + myName)
	print ('Let me explain this game. It is an entirely word game.  In order to get the correct responses you must print the answer like how I typed it. Lets practice one!')
	print ('Ask "Hi, how are you?" or "What are you doing?" The answer to this is "Hi, how are you?", so type it as "Hi, how are you?"')
	myanswer= input()
	answer= 'Hi, how are you?'
	if answer == myanswer:
		print ('Awesome!! You understand.  Have fun and make smart choices!!!')
	else:
		print ('You have to type it exactly how it appears. Which for that question was Hi, how are you?. But do not fret you got this!!')

		
>>> def missingring():
	print ('A lady walks in, Hello name is Elisa or E.')
	print ('Ask "How may I help you?" or "What do you want?"')
	myanswer= input()
	answer = 'How may I help you?'
	if answer == myanswer:
		print ('E: You are sweet.')
	else:
		print ('E: You are so rude, but I need your help.')

		
>>> def hotel ():
	print ('She shows you a picture of her husband and the ring. E: I lost this ring.')
	print ('Where is the last place you had it?')
	print ('E: Um... *paces around your office* The last place was at the hotel')
	print ( 'Ask "And...what were you doing there??" or "What hotel?"')
	myanswer= input()
	answer= 'What hotel?'
	if answer == myanswer:
		print ('Shamrock hotel downtown')
	else:
		print ('Wouldnt you like to know? Can you just go to the Shamrock hotel downtown now and find my ring?')
	print ('You go to the hotel alone, because E has work.  After getting her room number from the clerk room 502, you go up to the room taking the elevator to the fifth floor.')
	print ('After entering the room, you smell something strange, "immediately leave" or "investigate?"')
	myanswer= input()
	answer= 'immediately leave'
	if answer == myanswer:
		print ('Good answer there is a gas leak')
	else:
		missingring()

		
>>> def hotelexplosion():
	print ('What do you do, "jump off" the balcony to land in the pool or "take off" running down the hall?')
	myanswer= input()
	answer= 'take off'
	if answer == myanswer:
		print ('You run down the hall and barely escape the explosion.  A couple of hair strands didnt but you are ok though!!')
	else:
		print ('You jumped off the 5th floor... and expected to live??')
		hotel()

>>> def cafe ():
	print ('E: Hello!! How is the investigation going?? Type "good" or "bad".')
	myanswer= input()
	answer= 'bad'
	if answer== myanswer:
		print ('E: I figured it would go like that... So what happened?')
	else:
		print ('Lying is bad... do not lie.')
	print ('After explaining what happened, E gets really stiff and makes an excuse to leave and runs out the cafe after paying for your coffee.')
	print ('Hmmm she was acting pretty weird... Time to see what she does.')
	print ('You follow her to an abandoned warehouse. Do you "stay outside" or "follow her" quietly with your tape recorder?')
	myanswer= input()
	answer= 'follow her'
	if answer == myanswer:
		print ('You follow her inside with your tape recorder.')
	else:
		print ('Why would you stay outside? What good can you really do from staying outside?? Inside we go!!')

		
>>> def awkwardmeeting():
	print ('After a couple of minutes of watching E nervously pacing back and forth, a man who is clearly not her husband walks in from the other entrance.')
	print ('E: Hey Josh!! E imbraces Josh (now will be known as J) ')
	print ('J kisses E. What is the big worry that you had to call me about?')
	print ('E: Well... I think my husband may be on to us... I lost my ring and hired a detective to find it and well.... he almost blew up.')
	print ('J: it will be ok. Just calm down and go home.  Just tell him you are getting the ring cleaned and I will help you look for it.')
	print ('E: Ok baby.')
	print ('E and J leave out of different exits after embracing each other.  You wait until you hear nothing and go out to your car.')
	print ('Do you "call E" and tell her what you know or do you "follow J"?')
	myanswer= input()
	answer= 'follow J'
	if answer == myanswer:
		print ('Awesome. No reason to let her know that I know what is going on.')
	else:
		print ('Why would you let her know that you know? So shw will know you were following her? There other was a better decision.')
	print ('You follow J and he goes to an empty parking lot.  You decide to not get too close so you do not get caught, and after 15 minutes other cars appear, about 13.')
	print ('Should you "get closer" to hear what is going on or should you "find another way"?')
	myanswer= input()
	answer= 'find another way'
	if answer == myanswer:
		print ('Yeah it is better not to risk being seen. There are 14 of them and only one of me.')
	else:
		print ('Do you have a deathwish?? Why would you go out there where there is 14 of them and only one of you?!')
		awkwardmeeting()

		
>>> def parkinglot():
	print ('To make up for not being able to go closer to them to hear what they are saying, you take out your trusty camera and start taking pictures.  However, we must make a decision, should you "focus on the faces" or "focus on the license plates"?')
	myanswer= input()
	answer= 'focus on the faces'
	if answer == myanswer:
		print ('Yeah it would toatlly be better to focus on the faces.')
	else:
		print ('It would be better to focus on the faces. So I will do that.')
	print ('After going to the hotel to get a copy of Josh and E together, you return to your office and run facial recogniton on the photos.  You end up identifying at least 10 of the 14 guys from peeople on the wanted list.  You even find out that Josh, is actually Josh Logan, who actually has a clean rap sheet, compared to everyone else.')
	print ('After making a line up photo sheet including Josh you call E and have her come to your office.')
	print ('E comes into your office. E:Hey what did you call me here about? did you find my ring?')
	print ('Tell her "you are on to her" little games or "take the lead of the converstation."')
	myanswer= input()
	answer= 'take the lead of the conversation'
	if answer == myanswer:
		print ('No reason to tell her how you know before she closes up.')
	else:
		print ('No! Do not confront her like this or she may leave asking if she is under arrest.')
		parkinglot()

>>> def gether():
	print ('I compiled a list of possible suspects who could have taken your ring.  You show her the photos one by one asking if she has ever seen them before.  She looked over all the photos for a bit except Josh who she quickly said no.')
	print ('Do you "leave this alone" or do you "press further" and show your evidence?')
	myanswer= input()
	answer= 'press further'
	if answer == myanswer:
		print ('Yes do not let her get away.')
	else:
		print ('Why would you let her lie. Time for our evidence!')
	print ('In fact I do know that you know this person Elisa.  In fact his name is Josh.  I am pretty sure you would not forget the name of your partner.')
	print ('E: You better have some strong evidence to accuse me of cheating on my husband!')
	print ('I am a detective! Of course I know to get concrete evidence!!')
	print ('You play the voice recording from the abandoned warehouse.')
	print ('E: That could be entirely anyone talking that doesnt mean it was me.')
	print ('Well you clearly said you did not know him, but this video shows differently.')
	print ('You show her the video from the hotel of her and Josh coming in together and leaving together.')
	print ('Any more lies you would like to tell?')
	print ('E blushes a deep red very embarrassed.')
	print ('Thanks for your time Elisa. I am going to need to keep you here for a bit and do not worry you do not have cell phone reception in this room.')
	print ('You call Josh, should you tell him the "real reason" you are calling or tell him "it is about E"?')
	myanswer= input()
	answer= 'it is about E'
	if answer == myanswer:
		print ('He will respond better if it is about E.')
	else:
		print('I would not even come if someone told me it was to be interrogated about who I hang around and if I have the ring.  Do not scare him off.')

		
>>> def J():
	print ('After interrogating J when he came in, he tells you about all the people he work with and how he does not have the ring but has to look for it or his boss will have his head on a silver platter.')
	print ('Should you "tap J phone" or should you put a "tracker on his car".')
	myanswer= input()
	answer= 'tap J phone'
	if answer == myanswer:
		print ('Cool! Ready to see who he calls and his contacts.')
	else:
		print ('Why put a tracker on his car? We can track him and look through his phone, just by tapping his phone.')
		J()

		
>>> def poison():
	print ('After they leave, you tap his phone.  Surely enough not too long after releasing them E and J talk and J calls many other people, however the conversations were a bit confusing.')
	print ('5 hours later, E husband ends up dead by a drive by and you rememmber a part of the conversation from J and the other gang members that said "bang chest head" which is exactly where E husband was shot.')
	print ('After the coroner (will now be known as C) finished the report, you are called down to the lab.')
	print ('C: I would not normally call you for something like this.  But he was not only shot in the head and chest, he was also poisoned.')
	print ('Ok, what type of poison is it and whwere is it from?')
	print ('C: It is naphthalene, which is common in some mothballs, but specifically they are from older mothballs because they stopped putting that chemical in them a while ago, so the mothballs would be expired by now.  If ingested it can cause nausea, abdominal pain and even seizures. From my tox screen, it looks like the mothballs were melted so definitely look into what he last ate.')
	print ('Thank you.')
	print ('Should you "get a warrant" or "break into his house"?')
	myanswer= input()
	answer= 'get a warrant'
	if answer == myanswer:
		print ('Yes, lets not get arrested.')
	else:
		print ('YOU GOIN TO JAIL NOW!!! Jk but wrong choice.')
		J()

>>> def emergency():
	print ('Before you could go to his house, E called and asked you to come to he hospital quickly.')
	print ('After rushing to the hospital, E greets you at the entrance.')
	print ('E: I am so scared! I did not know who else to turn to!! Josh is here for abdominal pain and nausea.  I called because this is the exact thing that happened to my husband the day before he got shot.  But, he thought that it was just that he drunk some milk because he is lactose intolerant, but he did not have milk or dairy at all.')
	print ('Oh my gosh! I think I know what is going on!!')
	print ('After gettting J room number you run in and ask him about food places he visited. You pull up the places E husband ate before and find the exact same resauraunt, named Sicilian.')
	print ('Should you "get a warrant" or "go undercover" (hopefully you learned your lesson since last time.')
	myanswer= input()
	answer= 'get a warrant'
	if answer == myanswer:
		print ('YAY!! I am so proud of you doing things the legal way!')
	else:
		print ('Dang... you did not learn....')
		poison()

>>> def concluding():
	print ('After getting your warrant you go to Sicilian which is owned by Al, J boss.  You find some mothballs in his office after picking the lock.  You take a couple of mothballs and stuff them in your pocket so Al does not think you are on to him.  You also find a gun in his desk, you take it telling him that we need to check to see if he has a permit on it.')
	print ('After leaving, you go over to the lab and ask them to compare the sample you took to the sample that was found in E husband and you bring them Al gun to see if it is the same type used to murder E husband.')
	print ('After an hour, your beliefs were confirmed, the mothballs used to kill E husband are the same ones that were found in Al office. You also deduce that this same poison is the one that has J in the hospital. You also find that the gun found, was the one to kill E husband, and the only fingerprints on it were Al.')
	print ('Is this enough information to arrest Al, "yes" or "no"?')
	myanswer= input()
	answer= 'yes'
	if answer == myanswer:
		print ('AWESOME LETS GO GET HIM!')
	else:
		print ('I do not see why not...')
	print ('The next day, you arrest Al for the murder of E husband and the attempted murder of J.')
	print ('The only thing Al says, "No one can have Elisa but me.')
	print ('This was a crime of passion.  Al wanted Elisa money at first but then fell in love with her.  This is why he had to go after her husband to get him out of the picture.  But, he remembered she was having an affair with J who he actually hired to steal from E.  The only issue is that J actually started having real feelings for E, so he had to go as well.  The ring in fact, was taken by another member of J gang.')
	print ('Thank you for being such an amazing Detective, ' +myName)

	
>>> 
