# StarCraft(Brood War) AI

Quick Building Now.

StarCraft(Brood War) AI, a way to try to be the strongest player. Now, the goal is to beat PRO human player. At the same time, SC is also an RTS game under incomplete information. So 'how to create a "final weapon" AI' is a fancy challenge.

In this repository, you will find many:

1. [API&Extensions](#API&Extensions)
2. Tournaments (big3 SSAIT/CIG/AIIDE)
3. Papers
5. Others(researcher list; platform or others i cant remember now )

**I would continue add more items to the repository. If you have any suggests or comments, just pull requests or let me know(rhoninyoung@gmail.com).**

Just enjoy it!

---

# API&Extensions


- BWAPI [[Link]](https://bwapi.github.io/) [[github]](https://github.com/bwapi/bwapi) a free and open source C++ framework that is used to interact with the popular Real Time Strategy (RTS) game Starcraft: Broodwar.
  
  - BWMirror [[Link]](http://bwmirror.jurenka.sk/)  [[github]](https://github.com/vjurenka/BWMirror) [[Document]](http://vjurenka.github.io/BWMirror/javadoc/)  BWMirror API is a Java wrapper for BWAPI. 
  
    - Atlantis [[github]](https://github.com/Ravaelles/Atlantis)

  - JNIBWAPI [[github]](https://github.com/JNIBWAPI/JNIBWAPI) a Java interface for the Brood War API (BWAPI) using Java Native Interface

  - CyBW [[bitbucket]](https://bitbucket.org/ratiotile/cybw/src/master/) CyBW is a Python language wrapper for BWAPI implemented in Cython.

  - GOAL [[Link]](https://github.com/eishub/Starcraft)

## Extensions/Addons

- BWEM [[Link]](http://bwem.sourceforge.net/) Brood War Easy Map is a C++ library that analyses Brood War's maps and provides relevant information such as areas, choke points and base locations. 


- BWTA [[Link]](https://code.google.com/archive/p/bwta/) Broodwar Terrain Analyzer (BWTA) is a add-on for BWAPI which analyzes the current starcraft map and returns the set of expansion locations, regions, and choke points.

- BWTA2 [[Link]](https://bitbucket.org/auriarte/bwta2/src/master/) [[Wiki]](https://bitbucket.org/auriarte/bwta2/wiki/Getting%20Started) BWTA2 is a fork of BWTA, an add-on for BWAPI that analyzes the map and computes the regions, chokepoints, and base locations. 

- SparCraft [[git-wiki]](https://github.com/davechurchill/ualbertabot/wiki/SparCraft-Home) SparCraft is an open source StarCraft combat simulation package.

- Boss [[git-wiki]](https://github.com/davechurchill/ualbertabot/wiki) The StarCraft Build Order Search System (BOSS) is a StarCraft: BroodWar build order search and simulation package used to plan all build orders in UAlbertaBot.

- DropLauncher A BWAPI bot launcher for human vs bot games. [[github]](https://github.com/adakitesystems/DropLauncher) 



# Tournaments

- SSCAIT Student StarCraft AI Tournament [[Link]](https://sscaitournament.com/) [[wiki]](http://www.starcraftai.com/wiki/SSCAIT)

- CIG Computational Intelligence in Games [[Link]](http://www.ieee-cig.org/) [[Facebook]](https://www.facebook.com/groups/1407585199570926/permalink/1653888654940578/)

- AIIDE Artificial Intelligence and Interactive Digital Entertainment [[Link]](http://www.aaai.org/Library/AIIDE/aiide-library.php) [[Link]](https://www.cs.mun.ca/~dchurchill/starcraftaicomp/)



# Bot Zoo

- **UAlbertaBot** [[github]](https://github.com/davechurchill/ualbertabot) Slayer.Boxer in opensource StarCraft AI Bot made by davechurchill, with tools(BOSS/SparCraft) & Installaion Guides. [[youtube]](https://www.youtube.com/watch?v=lSmkDjFm3Tw)

  - **AKBot** [[github]](https://github.com/kant2002/ualbertabot)

  - **Steamhammer** [[Link]](http://satirist.org/ai/starcraft/steamhammer/) A BWAPI bot playing zerg in StarCraft Brood War, made by [Jay Scott](http://satirist.org/), he has a StarCraft AI [Blog](http://satirist.org/ai/starcraft/blog/)

  - **LetaBot** [[github]](https://github.com/MartinRooijackers/LetaBot) Wall-in/Optimized mineral gather/ MCTS Terren Bot.



- **ZZZKBot** [[github]](https://github.com/chriscoxe/ZZZKBot)



- **Overkill** [[github]](https://github.com/sijiaxu/Overkill)[[wiki]](https://github.com/sijiaxu/Overkill/wiki) A machine learning Zerg Bot by Sijia Xu.



- **PurpleWave** [[github]](https://github.com/dgant/PurpleWave) Can play all races and a large variety of strategies written in Scala.

- **KaonBot** [[github]](https://github.com/m-khan/KaonBot) Terren Bot based on BWMirror

- **TorchCraft** [[github]](https://github.com/TorchCraft/TorchCraft) A bridge between Torch and StarCraft.




# Papers

https://github.com/SKTBrain/awesome-starcraftAI

https://github.com/bwapi/bwapi/wiki/Academics

https://github.com/Eric-Wallace/starcraft-research-papers

## Research Papers
### Surveys
- S. Ontañón, G. Synnaeve, A. Uriarte, F. Richoux, D. Churchill, M. Preuss, A survey of real-time strategy game ai research and competition in starcraft, IEEE TCIAIG, 2013. [[Survey]](https://hal.inria.fr/file/index/docid/871001/filename/survey.pdf)
- S. Ontañón, G. Synnaeve, A. Uriarte, F. Richoux, D. Churchill, M. Preuss, RTA AI Problems and Techniques, Springer Encyclopedia of Computer Graphics and Games, 2015. [[Survey]](http://richoux.fr/publications/ecgg15_chapter-rts_ai.pdf)
- D. Churchill, M. Preuss, F. Richoux, G. Synnaeve, A. Uriarte, S. Ontañón, M. Certický, StarCraft Bots and Competitions, Springer Encyclopedia of Computer Graphics and Games, 2016. [[Survey]](http://richoux.fr/publications/ecgg16_chapter-sc_competitions.pdf)
- R. Lara-Cabrera, C. Cotta, A. Fernandez-Leiva, A review of computational intelligence in RTS games, IEEE FOCI, 2013. [[Survery]](http://www.lcc.uma.es/~ccottap/papers/lara13review.pdf)

### Benchmark
- A. Uriarte, S. Ontãñón, A Benchmark for StarCraft Intelligent Agents, AAAI AIIDE, 2015. [[Paper]](https://pdfs.semanticscholar.org/bbe4/2896225a4202754a95cca76252313413a342.pdf)

### Thesis
- G. Synnaeve, Bayesian programming and learning for multi-player video games: application to RTS AI, Ph.D. Thesis, INPG, 2012. [[Thesis]](https://tel.archives-ouvertes.fr/tel-00780635/document)
- J. Hagelback, Multi-Agent Potential Field Based Architectures for Real-Time Strategy Game Bots, Ph.D. Thesis, BIT, 2012. [[Thesis]](http://www.bth.se/tek/jhg.nsf/bilagor/jhg_phd_thesis_cr_pdf/$file/jhg.phd.thesis.cr.pdf)
- D. Churchill, Heuristic Search Techniques for Real-Time Strategy Games, Ph.D. Thesis, U. Alberta, 2016. [[Thesis]](http://www.cs.mun.ca/~dchurchill/pdf/DavidChurchill_phd_thesis.pdf)

### Dataset
- G. Synnaeve, P. Bessiere, A Dataset for StarCraft AI & an Example of Armies Clustering, arXiv, 2012. [[Paper]](https://arxiv.org/pdf/1211.4552.pdf)
- G. Robertson, I. Watson, An Improved Dataset and Extraction Process for Starcraft AI, FLAIRS, 2014. [[Paper]](https://pdfs.semanticscholar.org/1bb9/3ae33a6367ef12c9a4b7a025710495167046.pdf)
- Z. Lin, J. Gehring, V. Khalidov, G. Synnaeve, STARDATA: A StarCraft AI Research Dataset, arXiv, 2017. [[Paper]](https://arxiv.org/abs/1708.02139)

### Bayesian Approach
- G. Synnaeve, P. Bessiere, A bayesian model for opening prediction in rts games with application to starcraft, IEEE CIG, 2011. [[Paper]](https://hal.archives-ouvertes.fr/hal-00607277/file/OpeningPrediction.pdf)
- G. Synnaeve, P. Bessiere, A Bayesian model for RTS units control applied to StarCraft, IEEE CIG, 2011. [[Paper]](https://hal.archives-ouvertes.fr/file/index/docid/607281/filename/BayesianUnit.pdf)
- G. Synnaeve, P. Bessiere, Special tactics: A bayesian approach to tactical decision-making, IEEE CIG, 2012. [[Paper]](https://hal.archives-ouvertes.fr/hal-00752841/file/SpecialTactics.pdf)

### Satisfaction and Optimization
- M. Certický, Implementing a Wall-In Building Placement in StarCraft with Declarative Programming, arXiv, 2013. [[Paper]](https://arxiv.org/pdf/1306.4460.pdf)
- J. Fradin, F. Richoux,  Robustness and Flexibility of GHOST, AIIDE Third Workshop on Artificial Intelligence in Adversarial Real-Time Games, 2015. [[Paper]](http://richoux.fr/publications/aiide15.pdf)
- F. Richoux, A. Uriarte, J.-F. Baffier, GHOST: A Combinatorial Optimization Framework for Real-Time Problems, IEEE TCIAIG, 2016. [[Paper]](http://richoux.fr/publications/tciaig16.pdf)
- F. Richoux, A. Uriarte, S. Ontañón, Walling in Strategy Games via Constraint Optimization, AAAI AIIDE, 2014. [[Paper]](http://richoux.fr/publications/aiide14.pdf)

### Planning
- B. Weber. M. Mateas, Case-Based Reasoning for Build Order in Real-Time Strategy Games, AAAI AIIDE, 2009. [[Paper]](https://games.soe.ucsc.edu/sites/default/files/bweber_aiide_09.pdf)
- B. Weber, M. Mateas, A. Jhala, Applying Goal-Driven Autonomy to StarCraft, AAAI AIIDE, 2010. [[Paper]](http://alumni.soe.ucsc.edu/~bweber/pubs/gda_aiide2010.pdf)
- D. Churchill, M. Buro, Build Order Optimization in StarCraft, AAAI AIIDE, 2011. [[Paper]](https://pdfs.semanticscholar.org/dfd9/1e739bd979c08485a75fd11c501a6ec05118.pdf)
- D. Churchill, M. Buro, Incorporating Search Algorithms into RTS Game Agents, AAAI AIIDE Workshop, 2012. [[Paper]](http://musicweb.ucsd.edu/~sdubnov/Mu270d/AIIDE12/03/WS12-15-005.pdf)
- M. Stanescu, N. Barriga, M. Buro, Hierarchical Adversarial Search Applied to Real-Time Strategy Games, AAAI AIIDE, 2014. [[Paper]](https://pdfs.semanticscholar.org/1ea1/20c8ad129f4984a4bee95096efa4115e8f62.pdf)
- N. Justesen, S. Risi, Continual Online Evolutionary Planning for In-Game Build Order Adaptation in StarCraft, ACM GECCO, 2017. [[Paper]](https://njustesen.files.wordpress.com/2017/04/njustesen-gecco-2017-continual-online-evolutionary.pdf)

### Prediction
- B. Weber, M. Mateas, A Data mining approach to strategy prediction, IEEE CIG, 2009. [[Paper]](http://alumni.soe.ucsc.edu/~bweber/pubs/cig_2009.pdf)
- H. Park, H. Cho, K. Lee, K. Kim, Prediction of Early Stage Opponents Strategy for StarCraft AI using Scouting and Machine Learning, Workshop at SIGGRAPH Asia, 2012. [[Paper]](https://pdfs.semanticscholar.org/0805/94e9ae896d1b1df508575e8dc8546c26e938.pdf)
- H. Cho, K. Kim, S. Cho, Replay-based Strategy Prediction and Build Order Adaptation for StarCraft AI Bots, IEEE CIG, 2013. [[Paper]](http://cilab.sejong.ac.kr/home/lib/exe/fetch.php?media=public:paper:cig_2013.pdf)
- M. Stanescu, S. Hernandez, G. Erickson, R. Greiner, M. Buro, Predicting Army Combat Outcomes in StarCraft, AAAI AIIDE, 2013. [[Paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.696.7272&rep=rep1&type=pdf)
- Y. N. Ravari, S. Bakkes, P. Spronck, StarCraft Winner Prediction, AAAI AIIDE, 2016. [[Paper]](https://pure.uvt.nl/portal/files/13692982/NorouzzadehRavari.pdf)

### Control
- B. Weber, M. Mateas, A. Jhala, A Particle Model for State Estimation in Real-Time Strategy Games, AAAI AIIDE, 2011. [[Paper]](http://alumni.soe.ucsc.edu/~bweber/pubs/weber_aiide11.pdf)
- A. Shantia, E. Begue, M. Wiering, Connectionist Reinforcement Learning for Intelligent Unit Micro Management in StarCraft, IJCNN, 2011. [[Paper]](http://www.ai.rug.nl/~mwiering/GROUP/ARTICLES/StarCraft.pdf)
- D. Churchill, A. Saffidine, M. Buro, Fast Heuristic Search for RTS Game Combat Scenarios, AAAI AIIDE, 2012. [[Paper]](http://musicweb.ucsd.edu/~sdubnov/Mu270d/AIIDE12/01/AIIDE12-027.pdf)
- D. Churchill, M. Buro, Incorporating Search Algorithms into RTS Game Agents, AAAI AIIDE Workshop, 2012. [[Paper]](http://musicweb.ucsd.edu/~sdubnov/Mu270d/AIIDE12/03/WS12-15-005.pdf)
- S. Wender, I. Watson, Applying Reinforcement Learning to Small Scale Combat in the Real-Time Strategy Game StarCraft: Broodwar, IEEE CIG, 2012. [[Paper]](https://pdfs.semanticscholar.org/1308/c8326203caec91a7c44ffd1dfe86dd227c7f.pdf)
- D. Churchill, M. Buro, Portfolio Greedy Search and Simulation for Large-Scale Combat in StarCraft, IEEE CIG, 2013. [[Paper]](https://pdfs.semanticscholar.org/9fcc/5d4c04db820a7ca5197285cded68fed29f65.pdf)
- K. Nguyen, Z. Wang, R. Thawonmas, Potential Flows for Controlling Scout Units in StarCraft, IEEE CIG, 2013. [[Paper]](http://eldar.mathstat.uoguelph.ca/dashlock/CIG2013/papers/paper_87.pdf)
- N. Justesen, S. Risi, Script-and Cluster-Based UCT for StarCraft, IEEE CIG, 2014. [[Paper]](https://njustesen.files.wordpress.com/2017/02/njustesen2014script.pdf)
- N. Usunier, G. Synnaeve, Z. Lin, S. Chintala, Episodic Exploration for Deep Deterministic Policies: an Application to StarCraft Micromanagement Tasks, arXiv, 2016. [[arXiv]](https://arxiv.org/pdf/1609.02993v3.pdf) [[ICLR 2017 Submission]](https://openreview.net/pdf?id=r1LXit5ee)

### Full Game Play
- B. Weber, M. Mateas, A. Jhala, Building Human-Level AI for Real-Time Strategy Games, AAAI ACS 2011. [[Paper]](https://games.soe.ucsc.edu/sites/default/files/weber-acs2011.pdf)
- J. Young, F. Smith, C. Atkinson, K. Poyner, T. Chothia, SCAIL: An integrated Starcrat AI system, IEEE CIG, 2012. [[Paper]](http://geneura.ugr.es/cig2012/papers/paper103.pdf)

### Learning from Demonstration
- B. Weber, S. Ontañón, Using Automated Replay Annotation for Case-Based Planning in Games, ICCBR-Games Workshop, 2010. [[Paper]](https://games.soe.ucsc.edu/sites/default/files/iccbr-cg.pdf)
- B. Weber, M. Mateas, A. Jhala, Learning from Demonstration for Goal-Driven Autonomy, AAAI, 2012. [[Paper]](http://alumni.soe.ucsc.edu/~bweber/pubs/Weber-AAAI-2012.pdf)
- J. Young, N. Hawes, Learning Micro-Management Skills in RTS Games by Imitating Experts, AAAI AIIDE, 2014. [[Paper]](https://pdfs.semanticscholar.org/0a51/c01c7a3ff9c73c0e518e6eef51f30f71f4ba.pdf)
- N. Justesen, S. Risi, Learning Macromanagement in StarCraft from Replays using Deep Learning, IEEE CIG, 2017. [[Paper]](Learning Macromanagement in StarCraft from Replays using Deep Learning)

### Miscellaneous 
- W. Gong, E. Lim, P. Achananuparp, F. Zhu, D. Lo, F. Chua, In-Game Action List Segmentation and Labeling in Real-Time Strategy Games, IEEE CIG, 2012. [[Paper]](http://www.mysmu.edu/faculty/fdzhu/paper/CIG'12.pdf)
- H. Alburg, F. Brynfors, F. Minges, B. Mattson, J. Svensson, Making and Acting on Predictions in StarCraft: Brood War, Bachelors Thesis, University of Gothenburg, 2014. [[Theis]](http://publications.lib.chalmers.se/records/fulltext/203120/203120.pdf)
- M. Leece, A. Jhala, Sequential Pattern Mining in StarCraft: Brood War for Short and Long-Term Goals, AAAI AIIDE Workshop, 2014. [[Paper]](http://www.aaai.org/ocs/index.php/AIIDE/AIIDE14/paper/viewFile/9082/9011)
- G. Erickson, M. Buro, Global State Evaluation in StarCraft, AAAI AIIDE, 2014. [[Paper]](https://www.skatgame.net/mburo/ps/GlobalStateEval-AIIDE-2014.pdf)

## Reports
- J. Lewis, P. Trinh, D. Kirsh, A Corpus Analysis of Strategy Video Game Play in Starcraft: Brood War, COGSCI, 2011. [[Paper]](http://mindmodeling.org/cogsci2011/papers/0138/paper0138.pdf)
- M. Buro, D. Churchill, Real-Time Strategy Game Competitions, AI Magazine, 2012. [[Report]](https://pdfs.semanticscholar.org/9acf/46f89bc944dea9fd44ffb2722aef2b34688a.pdf)
- G. Robertson, I. Watson, A Review of Real-time Strategy Game AI, AI Magazine, 2014. [[Report]](http://www.aaai.org/ojs/index.php/aimagazine/article/view/2478/2457)
- M. Kim, S. Kim, K. Kim, A. Dey, Evaluation of StarCraft Artificial Intelligence Competition Bots by Experienced Human Players, CHI, 2016. [[Report]](http://www.cs.cmu.edu/~sjunikim/publications/CHI2016_LBW_Starcraft.pdf)




- Review
  - M. Čertický, D. Churchill. The Current State of StarCraft AI Competitions and Bots. In Proceedings of the AIIDE 2017 Workshop on Artificial Intelligence for Strategy Games. 2017. [[PDF]](http://agents.fel.cvut.cz/~certicky/files/publications/aiide17-certicky-churchill.pdf)

  - D. Churchill, M. Preuss, F. Richoux, G. Synnaeve, A. Uriarte, S. Ontanón, M. Čertický. StarCraft Bots and Competitions. Chapter in Encyclopedia of Computer Graphics and Games (ECGG). Springer International Publishing. ISBN: 978-3-319-08234-9. 2016. [[PDF]](http://agents.fel.cvut.cz/~certicky/files/publications/ecgg15_chapter-competitions.pdf)

  - A survey of real-time strategy game ai research and competition in starcraft. 2013. [[PDF]](https://hal.archives-ouvertes.fr/file/index/docid/871001/filename/survey.pdf)


  - Multi-Agent Systems in StarCraft. H.J. Griffioen and D. Plenge. 2016. [[PDF]](https://repository.tudelft.nl/islandora/object/uuid:14f3a259-b440-49e2-8106-aad0ee387a10/datastream/OBJ/download) A bechlor project based on GOAL, an agent programming language for programming cognitive agents. [[GOAL]](https://goalapl.atlassian.net/wiki/spaces/GOAL/overview?mode=global)






## Researcher / University / Group / Team

- Researcher

  - [Alberto Uriarte](http://nova.wolfwork.com/about.html) RA/TA, PhD candidate in 

  - [D. Churchill](http://www.cs.mun.ca/~dchurchill/) Assistant Professor of Computer Science at Memorial University
  - [Gabriel Synnaeve](https://research.fb.com/people/synnaeve-gabriel/) project leader of the CherryPi Bot and researcher at Facebook

  - [Dan Gant](https://github.com/dgant) Anthor of PurpleWave Bot

  - [Junge Zhang](https://scholar.google.com/citations?user=gbStvusAAAAJ&hl=en)

  - [Zhentao Tang](https://www.researchgate.net/profile/Zhentao_Tang)


  - [G&S Reserach Group](http://gas.fel.cvut.cz/) AI Research Group, Czech Technical University in Prague

  (https://sites.google.com/site/santiagoontanonvillar/)




# Replays

http://reps.ru/replays.php

http://bwreplays.com/


## Others

- SSCAI Map Pack [[Collection]](https://sscaitournament.com/index.php?action=maps) [[Downloard]](https://sscaitournament.com/files/sscai_map_pack.zip)

- StarCraft AI, a StarCraft AI resource page.(SC wiki) [[Link]](http://www.starcraftai.com/wiki/Main_Page)


- Improving mineral gathering rate in Brood War (using BWAPI) [[Link]](http://www.teamliquid.net/forum/brood-war/484849-improving-mineral-gathering-rate-in-brood-war)

[BWAI_Universities](https://liquipedia.net/starcraft/Category:BWAI_Universities)

Memorial University

Technische Universiteit Delft

University of Maastricht (Netherlands)

University of Southern California (USA)

 Technical University of Denmark (Denmark)

 https://cis.ieee.org/games-tc.html

 
http://www.starcraftai.com/wiki/StarCraft_AI_Benchmarks

[[StarCraft: Brood War's Mechanics]](http://www.starcraftai.com/wiki/Main_Page) Ctrl+F+Mechanics

[[BW order timings]](https://docs.google.com/document/d/1a-6NqHI3Leqe6FOZph_K5NLWx27VG1sa87bRSdjQotU/edit)

[[StarCraft WeaponType Data]](https://docs.google.com/spreadsheets/d/1YWFzY0_MEE4fOy9HrvZCYSpRqjgSBdCeRYVxB6zmJpQ/edit#gid=0)

[[StarCraft TechType Data]](https://docs.google.com/spreadsheets/d/1FpB8e7VJYubaqTtMLoc457a319Wu8yT8jTM6hPq6pT8/edit#gid=0)

[[StarCraft UnitType Data]](https://docs.google.com/spreadsheets/d/1jlYDkXW2pQey1oGJlQRBiGjdMs0kfrdHAwzVI2zAjrU/edit#gid=0)


[[Unusual Unit Morphs]](https://github.com/nturley/bwapi-notes)


https://www.researchgate.net/profile/Zhentao_Tang/publication/324686165_Recent_progress_of_deep_reinforcement_learningfrom_AlphaGo_to_AlphaGo_Zero/links/5adc9332a6fdcc29358aaa2a/Recent-progress-of-deep-reinforcement-learningfrom-AlphaGo-to-AlphaGo-Zero.pdf

# todolinks

https://zhuanlan.zhihu.com/p/29986506

https://zhuanlan.zhihu.com/p/35356234

http://www.starcraftai.com/wiki/StarCraft_AI_Benchmarks

http://www.starcraftai.com/wiki/StarCraft_Brood_War_Data_Mining

http://blogs.cornell.edu/info2040/2011/10/31/game-theory-applied-to-starcraft-ii/

http://www.goliathdesigns.com/2011/02/starcraft_ai/

http://www.starcraftai.com/wiki/Why_not_StarCraft_2

- StarCraft II AI Blog, by Matt Fisher. [[Blog]](https://graphics.stanford.edu/~mdfisher/GameAIs.html)




# Something about SCII

- StarCraft II API - Technical Design, Blizzard. [[Link]](http://us.battle.net/forums/en/sc2/topic/20751114921)

