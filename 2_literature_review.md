---
bibliography: bibliography.bib
indent: true
---

#  Joining the Conversation: Phones in Networked Music Performance

## Research Problem
<!-- Independently and expertly constructs a clear, succinct and insightful statement about a complex problem or research hypothesis with evidence of relevant contextual factors. -->


## Search Strategies
<!-- Accesses information using effective and sophisticated search strategies and draws on the most appropriate information sources. Demonstrates the ability to locate high-quality, credible, relevant sources to support and develop novel ideas. -->

I searched using the RMIT Library search portal, however, I was finding that a lot of the relevant articles were not showing up there, so I also used Google search and manual searches through the proceedings of New Interfaces for Musical Expression, Web Audio Conference, and Computer Music conferences.

### Search String

```
(distribut* OR network* OR connect* OR decentralis* OR link* OR 
dispers* OR shared OR participa* OR collaborat* OR interact*) 

AND 

(synthesis* OR orchestra* OR "sound design" OR "sound generation"
OR perform* OR improvisat* OR music* OR "musical expression" OR 
"musical input" or "musical output" OR "musical interaction" OR 
"musical control") 

AND 

("mobile device" OR "cellular phone" OR "mobile computer" OR 
"pocket computer" OR "smart device" OR "touchscreen phone" OR 
"portable device" OR "mobile terminal" OR "phablet" OR "personal 
gadget" OR "wearable" OR "mobile tech" OR "connected device" OR 
"personal electronics" OR "handheld device" OR "pocket device" 
OR "smart gadget")
```

## Research Questions

<!-- Clearly articulates one or more well-formed research questions about a complex problem or research topic, presented in a way that is easily identifiable to reviewers. -->

- In what way do the design problematics of co-located networked music performance interface with the field of:
  - music?
  - web development?
  - education?
  - politics / ethics?
  - aesthetics?
- What approaches to distributed synthesis can creatively harness audiences' phones' capacity:
  - to act as a speaker array?
  - for digital signal processing?
  - for massive polyphony?
  - for networked communication?
  - for singing synthesis?
  - for machine learning?


## Literature

<!-- Information is taken from source(s) with a high level of interpretation/evaluation to develop a comprehensive critical analysis or synthesis. Systematically and methodically discriminates between assertion or personal opinion and information substantiated by robust evidence. Critically analyses, reflects on, synthesises and evaluates relevant literature and identifies gaps in knowledge that lead to the research question/s -->

As the practice of co-located networked music performance (NMP) involves a lot of moving parts, including music composition, which is itself sprawling field of research, I have, for the sake of brevity and sanity, attempted to limit the scope of this review to only the articles most relevant to my practice, in the fields of web audio, NMP, and which deal with the compositional practice of *distributed music*. [@taylorHistoryAudienceSpeaker2017]

### Distributed Music

<!-- history -->
Although Boutwell mentions the work of the "League of Automatic Music Composers" in San Francisco between the years 1978-1983 as being some of the first to explore the musical possibilities of networked computers -- a practice that would evolve to become the contemporary laptop ensemble [-@boutwellLeagueAutomaticMusic2009a], we can trace the history of *distributed music* (the practice of employing the audience as some kind of speaker array) back to the compositional use of radios in John Cage's 1951 piece “Imaginary Landscape No. 4” [@renaudNetworkedMusicPerformance2012], which set the stage for Jose Maceda's massive-scale, 1974 participatory work "Ugnayan", which commandeered 37 of Manilla's radio stations and which encouraged "... residents of the city to take their radios out into the streets and turn them up". [@taylorHistoryAudienceSpeaker2017] As an often overlooked friend and contemporary of Xanakis, Varèse, and Schaeffer, Maceda's work presents an alternative compositional paradigm which is of particular interest to my sonic practice. [@ondaEverywhereOnceJose2019]

Since *Ugnayan*, examples of distributed music include Heath Bunting's 1994 work "Cybercafe", which employed pay phones in London's Kings Cross train station [@buntingCybercafeNetArt1994]; The Flaming Lips' 1996 work "The Parking Lot Experiments", which employed participants' car stereos via distributed cassette tapes [@lemayFlamingLips20]; Brown and Galindo's "Transmission" series of performances, which distributed audio to audiences' handheld radios via a low-powered DIY FM-radio transmitter; Thomson and Craighead's 2000 interactive art installation "Telephony" [@hopeSoundArtMobile2005]; Hrubesch's 2001 installation "Handywolke" [@levinInformalCatalogueMobile2020]; "Dialtones: A Telesymphony", a 2001 composition by Levin, Shakar, and Gibbons, which distributed custom ringtones to audience's mobile phones which the performers would trigger via phone calls [@levinDialtonesTelesymphony2020]; the 2010 Stanford Mobile Orchestra performance [@wangAudienceParticipationTechniques]; JODI glitch art collective's 2012 "ZYX" -- an art installation which employed a mobile phone app to instruct audience participants to perform surreal body gestures through the gallery space; OK GO rock band's 2012 collaboration with National Public Radio "Needing / Getting", composed for a live broadcast of the radio show "This American Life", in which participants used three buttons on a mobile app to play along to a visual score, in the style of a handbell ensemble, coordinated across 300 theatres throughout America; Sang Wong Lee's 2012 Echobo, in which the audience's noodling on a custom made web app musical instrument creates a background harmonic texture for the performers on stage; and Xavier Garcia's 2014 piece "Belzelbuth", in which audiences participate in the sonification of the work via physical gestures, as picked up by their phones gyroscopic sensors, and sonified by a custom phone app. [@taylorHistoryAudienceSpeaker2017]

### Web Audio

Since 2016 there has been glut of interest in distributed music with an emphasis on web audio, driven by updates in javascript specification and broadening implementation of various web audio and commuication application protocol interfaces (APIs), making the prospect of distributed music more accessible to composers and performers, and more frictionless for audiences. [@taylorHistoryAudienceSpeaker2017]  Much of the research during this time took place at the Web Audio Conference, and many of the themes discussed during the years 2016-2019 remain relevant to my practice.

<!-- phones as speaker array -->
Projects which deployed audience phones as a speaker array include [@crettiWebWallWhispers2018], in which audiences' phones were operationalised for multi-modal output and interaction in the context of a sound-art installation; and [@carsonMorePerfectUnion2018], describing a long-form creative work that uses the genetic algorithm to interpolate audience intractions into a slowly evolving piece of algorithmic music as sonified by audiences' phones.

<!-- messaging protocols -->
On the theme of communication protocols, [@bownSupportingCreativePractice2021] discuss the virtues of media multiplicity systems which use a fine-grained control stream that reduces the decision-making required by the end-device, and the benefits of broadcasting global states rather than unicasting individual states; [@clesterComposingNetworkStreams2021] discuss the pros and cons of using the UDP versus TCP for various types of control message; and [@dannenbergCommunicationRealTimeMusic2021] describes a communication protocol for musical control that extends on Open Sound Control (OSC), and which includes a bridge application that allows for communication over WebSockets.

<!-- latency -->
The issue of latency is especially important for NMPs incorporating socially isolated musicians [@iorwerthApplicationNetworkedMusic2019]; [@lakiotakisApplicationnetworkCollaborationUsing2017] goes so far as to define NMP as a "... class of ultra-low delay sensitive applications ...", but neglect the possibility of co-located NMP; [@rottondiOverviewNetworkedMusic2016] discuss the importancy of low latency, among other factors, in NMP;
[@mitchellMakingMostWiFi2014] discusses methods for drastically reducing latency; [@dannenbergO2NetworkProtocol2019] discuss the issues of unreliable internet connection and latency.  The issue of latency remains a central problematic in this field.

<!-- pedagogy -->
The theme of pedagogy arose several times, as there seems to be some intuition that web audio can improve students' intrinsic motivation to study computer science [@binMuseumBrowserTranslating2019]; [@hollerwegerStreaaamFullyAutomated2021] describes the creation of a pedagogically oriented, creative hub for audio works; [@alexandrakiMusiCoLabModularArchitecture2022] describes the creation of a music-oriented, synchronous / asyncronous online learning management system.  This topic is very important to my practice, for reasons which must fall outside the scope of this essay.

<!-- Web Audio Plugins -->
A handful of projects pertained to the task of porting existing digital signal processing (DSP) technologies to the browser, including [@letzFAUSTOnlineIDE2019], who employed AudioWorklet to create a web application that allow users to write Web Audio plugins using FAUST; and [@kleimolaNativeWebAudio2018], who describes a technique for providing continuity between existing desktop digital audio workstation (DAW)-based plug-ins and web audio. 

<!-- WebRTC -->
One particularly pertinent topic was the Web Real Time Communication (WebRTC) API, which I am planning on implementing into my instrument's server structure over summer. [@sacchettoJackTripWebRTCNetworkedMusic2021] describe a project that uses WebRTC and AudioWorklet to instantiate an uncompressed audio transmission over the internet; and [@sticklandDesignRealtimeMultiparty2019] used WebRTC API to build a collaborative online digital audio workstation (DAW).

<!-- singing synthesiser -->
One of my investigative threads includes singing synthesis, so [@goverChoirSingersPilot2021]'s description, using VoSyn to instantiate a neural-parametric singing synthesiser in their choir-practice web application was particularly relevant.

<!-- WebVR -->
The topic of virtual reality came up a couple of times, and I would imagine with more activity to come as the hardware gets better and more accessible in the years to come.  [@manassehPlayPlaceExperiencing2021] describe a technique for generating binaural impulse response approximations from digital 3D models for the purposes of creating realistic sounding WebVR acoustic environments; and [@cakmakComposingSpatialMusic2019] describe a method for using ambisonics and binaural rendering techniques with Web Audio for the purposes of making multi-channel sonic works available over the internet via WebVR.

<!-- machine learning -->
Machine learning continues to be an important theme, although exactly how or whether I will incorporate this into my sonic practice remains a question.  One of the clearest use cases is for music information retrieval [@correyaEssentiaTensorFlowModels2021]; while [@carsonSoundsAwareMobile2019] used machine learning and web audio to distinguish between man-made ambient sounds (anthrophony), natural ambient sounds (biophony), and geophysical sounds (geophony), for the purposes of covering up anthrophony with artificial biophony and geophony, to "encourage environmental awareness".

<!-- live coding -->
Research projects which dealt with the practice of live-coding included [@robertsBringingTidalCyclesMinilanguage2019], who used AudioWorklet to port TidalCycles to the browser; [@clesterKilobeatLowlevelCollaborative2021], who describe the creation of a collaborative, low-level live-coding web-application built with AudioWorklet and WebSockets; a project that implemented a live-coding REPL in the browser console using using AudioWorklet, [@lanGlicolGraphorientedLive2021]; and a meta framework built with AudioWorklet for the creation of live-coding languages [@bernardoAudioWorkletbasedSignalEngine2019].

<!-- alternate programming paradigms for web audio -->
Criticisms of Web Audio API's verbose, imperative, object-oriented style have produced some interesting remedies: [@renBuildWebAudioJavaScript2021], for example, used AudioWorklet to create a visual programming language web application that mimics MaxMSP; [@inkinDeclarativeWebAudio2021] describes the creation of a javascript library which allows for a declarative approach to web audio; and [@solomonFunctionalReactiveProgramming2021] describe the creation of a javascript library that allows for functional approach to coding web audio.

<!-- misc -->
<!-- 
Web Audio API is even being used for bio-feedback sonification in therapeutic contexts. [@baumannBodyMovementSonification2018]
[@turchetInternetSoundsConvergent2023] the authors are adamant that IoS requires *dedicated* devices for DSP - a claim that is demonstrably untrue.  My sonic arts practice predominately uses mobile phones for this purpose, which are *not* dedicated devices.
[@bevilacquaDesigningComposingPerforming2021] discuss ways we might foreground the social implications of "networks of devices" in art installations and participatory NMP. -->


<!-- glitch -->

### Frameworks

Recent scholarship attempting to frame the field of NMP has undergone what Braidotti might call a *proliferation of neologisms*. [-@braidottiTheoreticalFrameworkCritical2019]  For example, in 2018, the Internet of Things (IoT), the concept which describes a network of "smart" devices connected to the internet, gave birth to the Internet of Musical Things (IoMusT), a subcategory of IoT replete with its own vision statement [@turchetInternetMusicalThings2018], ethics [@brusseauEthicsFrameworkInternet2024], semantics [@turchetSemanticWebMusical2023], and "ontology" [@turchetSmartMusicalInstruments2022], and which lies at the intersection of IoT, "... homan-computer interaction, ubiquitous music, artificial intelligence, gaming, virtual reality and particpatory art through device multiplicity" [@fraiettaTransparentCommunicationMultiplicities2020].  The same year, the Internet of *Audio* Things (IoAuT) was described [@matuszewskiWebAudioThings2018; @turchetInternetAudioThings2020], generating the need for two fields (IoMusT and IoAuT) to become unified under the super-subcategory, Internet of Sounds (IoS). [@turchetInternetSoundsConvergent2023]

We can see a somewhat parallel development at work in the prior progression from ubiquitous computing (ubicomp) [@weiserComputer21stCentury2002], to ubiquitous music (ubimus) [@kellerUbiquitousMusic2014], which foregrounds the pervasiveness and invisibility of computing and networked musical technology [@lazzariniUbiquitousMusicEcologies2020].  Similarly, we might note a burgeoning field of Smart Musical Instruments (SMIs), novel musical instruments characterised by "embedded intelligence", such as the smart mandolin [@turchetSmartMandolinAutobiographical2018], smart cajón [@turchetRealTimeHitClassification2018], smart guitar [@turchetExamplesUseCases2017], smart synthesiser @turchetMakingPhysicalControl2020, and with its own, seperate "ontology" [@turchetSmartMusicalInstruments2022].  


## Discussion
<!-- a brief discussion of how your research will address a significant gap in the literature OR offer a new interpretation of existing knowledge OR develop, adapt, and implement research methods appropriate to the research question OR generate original theoretical insights OR extend existing theoretical insights by applying them in new ways -->

To my disappointment, the word "ontology" appears to mean "taxonomy" in these contexts, which is a significant opportunity loss considering how the field of music instrument design necessarily *instrumentalises* technology in music performance rituals, which we could argue are the living cultural vestiges of normativity and complicity *par excellence*, and that because of this material coupling, philosophy and music instrument design stand to gain considerably from a deeply held, fundumental engagement.  In fact, it is upon exactly this hypothesis that my whole creative practice as a sonic artist is predicated.

A cynical reading might attribute this proliferation of superficial, descriptive neologisms to what Loveless refers to as the careerist, bibliometric university culture of the contemporary neoliberal university. [-@lovelessHowMakeArt2019]  We might even find some supporting evidence for this cynicism in several of Luca Turchet's articles, which both declare no competing interests, and cite the SENSUS Smart Guitar as a prime example of a "smart" musical device belonging to the IoMusT [@turchetRelationFieldsNetworked2023; @turchetSmartMusicalInstruments2022; @turchetInternetSoundsConvergent2023], despite this being a commercial product being sold for profit by Elk, a company Turchet is involved with as a founding member. [@turchetBiography]  A cursory glance at that product's promotional material (which can be found [here](https://youtu.be/fqzEQnsSIoY)) may serve as a warning about the kind of aesthetic cul-de-sac a critically unengaged music instrument design practice can lead to. [@elkSENSUSSmartGuitar2016]

Despite these cynicisms, it is clearly evident from this neologistic activity, where every four or five years a new set of nomenclature is taken up, that the field is in a way, attempting to grapple with its own productivity.  There appears to be so much work to be done here that researchers are collectively scrambling to find some external points of purchase to help make sense of what this work should actually look like.  It is with this in mind that I would like to include some texts from outside the field of NMP in this literature review, with which we might construct a more useful frame of reference for music instrument design.

<!-- Brandom's re-interpolation of Kant's insight that we, as concept users, are constituted by our commitments [@brandomArticulatingReasonsIntroduction2009], might serve as a starting point for speculation about the role music (in the prosody of our initial care-givers, in the music we listen to as adolescents, etc.) might play in establishing the primeval sense of correctness upon which our subjectivity is predicated, for example.  Brandom's inferentialism more generally, is useful for understanding the processes by which implicit conceptual content becomes explicated after the fact [-@brandomArticulatingReasonsIntroduction2009], which can be deployed in the context of music instrument design to understand how audiences always, eventually, get more than simply what was made explicit within the parameters of the music performance ritual.  In other words, every facet of the design process informs what the new musical instrument will eventually come to mean.  All inferential relations become fodder for the Brandomian mill -- *there is no hiding*.  We might find further assistance in understanding music performance's relation to discourse in Lacan's theory of the four discourses [@lacanOtherSidePsychoanalysis2007], a topic about which a full extrapolation must fall outside the scope of this current essay.

With regard to music instrument design's relation to technology, we might find some useful guidance in Heidegger's idea about technology being essentially a mode of revealing [-@heideggerQuestionConcerningTechnology2008], or in Stiegler's insistance that in order to understand our predicament properly, we must first acknowledge *technê* as the ontologically constitutive attribute of human *being* [@stieglerTechnicsTime1998].  Tomlinson deploys a similar line of thought, but emphasises the breadth of "musicking" practices and their relation to technology, in terms relating to co-evolutionary feedback and cognition, as described through the history of the emergence of modernism. [-@tomlinsonMillionYearsMusic2015]  Yuk Hui's concept of *cosmotechnics* builds off the work of Heidegger and Stiegler in a way which destabilises the nature versus technology dichotomy central to the Eurocentric conception of modernism, and employs the ideas of several modern Eastern thinkers to demonstrate the possibility of a freer, more open relation to technology [-@huiQuestionConcerningTechnology2016a] -- should this not be exactly the aim of music instrument design in the age of NMP?

One explanation for the absence of cultural theory and philosophical speculation from the journal literature on NMP could be that all such discussions are removed in order to pass the peer-review process, which to me indicates a field of study that is ostensibly concerned with cultivating new creative forms, but which is still very much caught in a sufficatingly post-positivist mentality that aims at a context-independent view of everything from nowhere - what Haraway terms the "god trick". [-@harawaySituatedKnowledgesScience1988]  Another possible explanation for this might be via the veneration of Pierre Schaeffer's concept of "reduced listening" as a seminal, canonical idea in the field - that the virtuous way to listen to sound in the new era of recorded audio is to listen to sound "in-itself", without the help of spontaneous identifications regarding what or where the sound came from, instantiating exactly the kind of ahistorical, objective vantagepoint that Haraway et al. found so problematic in the human sciences, but in the domain of music composition. [@kanePierreSchaefferSound2014] -->

Whatever the cause, the omission of deeper critical or theoretical engagement comes with an immense opportunity loss.  We could draw on Hempton for inspiration about how we are immediately, spontaneously, fundamentally connected to world via our ears [-@hemptonOneSquareInch2010], or to McLuhan, who speculates that we are much more "irrational" when we are listening than when we are looking [-@mcluhanUnderstandingMediaExtensions1994a], both notions with which I wholeheartedly agree. Similarly, if we draw on Wark [-@warkCapitalDeadThis2021] and Fisher [-@fisherPostcapitalistDesireFinal2020; -@fisherCapitalistRealismThere2022] to help diagnose our current condition we might note that music instrument design, as a field, may be uniquely placed to interevene. If theory belongs anywhere, it is exactly here, in sonic practice!

<!-- Movements in the direction of critical posthumanism can be seen in the exogeses of composers Barratt [-@barrettSoundCriticalMusic2016; -@barrettExperimentingHumanArt2023], and Mattin [-@mattinSocialDissonance2022] -->

\newpage 

## References