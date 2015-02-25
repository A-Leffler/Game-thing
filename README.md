Let's make a game!
        -Game Developer :3
        -by me
        -version 1
 
Settings :
        -prices increase by 100%
        -selling gives back 100%
        -resources are hidden by default
        -clickables are hidden by default
        -buildings are hidden by default
        -upgrades are hidden by default
        -achievements are hidden by default
        -show log
	-custom stylesheet : http://pastebin.com/raw.php?i=tnc4Z5Cx
        -text color : #00FF00
        -fonts : Kavoon
        -boxes : main (resources, clickables); stats (achievements); store (upgrades, buildings)
 
Resources :
	*menu1
	-named --------YOUR RESOURCES--------
	-starts at 1
	-displayed as %r

        *code
        -named line of code
        -visible

	*totalCode
	-named progress
	-visible

	*nothing
	-abstract

	*lel
	-named ignore

	*lel2
	-named ignore

	*lel3
	-named ignore

	*lel4
	-named ignore

	*lel5
	-named ignore

	*lel6
	-named ignore

	*lel7
	-named ignore

	*lel101
	-named ignore

        *popularity
        -named major game series overtaken
	-displayed as Popularity Level: %a

	*positiveReview
	-named positive review|positive reviews
	-visible

	*game2
	-named game produced|games produced

	*magicPoint
	-named magic point|magic points

	*buildings
	-named total buildings
	-visible
	
	*eggGem
	-named unstable gem
	-visible

	*menu2
	-named -------CODE FROM THINGS-------
	-displayed as %r
	-visible
 
        *manualWritten
        -named code manually written

	*fastMenResearch
	-named fast men research

	*unimplemented
	-named This feature is not implemented yet.
 
        *codeWriterWritten
        -named code written by code writers
        *objectWritten
        -named code from objects
        *enemyWritten
        -named code from enemies
        *playerWritten
        -named code from players
        *levelWritten
        -named code from levels
        *gameWritten
        -named code from games
        *fanbaseWritten
        -named code from fanbases
        *forumWritten
        -named code from forums
        *advertiseWritten
        -named code from advertisements
        *studioWritten
        -named code from studios
	*magicWritten
	-named code written by magic code writers
	*gameSeriesWritten
	-named code from game series
	*maganiumWritten
	-named code from ultra-magic generators
	*popularYoutuberWritten
	-named code from popular YouTubers
	*finalityWritten
	-named code from The Finality

	*menu3
	-named ------------OTHERS-----------
	-displayed as %r
	-starts at 1
	-visible

	*conversion
	-named conversions

	*time
	-named seconds played

	*researchTime
	-named research time

	*researchTime2
	-named magic research time

	*researchTime3
	-named ultra-magic time

	*researchTime4
	-named finality research time

	*breakthrough
	-named research breakthrough|research breakthroughs

	*orb
	-named ultra-magic orbs
	
	*manualResearch
	-named research done manually

	*boxDamage
	-named damage done to golden box

	*resets
	-named times reset

	*prestige
	-named godly lines of code

	*stoneBuilding
-abstract
 
 
Clickables :
        *writeCode
        -gives 1 code
        -gives 1 totalCode
        -gives 1 manualWritten
        -named Write Code
	-picture : http://i.imgur.com/UsWtgdU.png
	*theBox1
	-gives 1 boxDamage, 1 magicPoint for 20000 code
	-unlocks theBox2
	-locks theBox1
	-picture : http://i.imgur.com/cX4R1DE.png
	*theBox2
	-gives 1 boxDamage, 2 magicPoint for 2000000 code
	-unlocks theBox3
	-locks theBox2
	-picture : http://i.imgur.com/znwugCm.png
	*theBox3
	-gives 1 boxDamage, 4 magicPoint for 4e+8 code
	-unlocks theBox4
	-locks theBox3
	-picture : http://i.imgur.com/YppW8uH.png
	*theBox4
	-gives 1 boxDamage, 10 magicPoint for 1e+11 code
	-unlocks theBox5
	-locks theBox4
	-picture : http://i.imgur.com/y5Mt78v.png
	*theBox5
	-gives 1 boxDamage, 100 magicPoint for 5e+13 code
	-unlocks theBox6
	-locks theBox5
	-picture : http://i.imgur.com/waxJO2o.png
	*theBox6
	-gives 1 boxDamage, 1000 magicPoint for 1e+16 code
	-unlocks theBox7
	-locks theBox6
	-picture : http://i.imgur.com/xAdFwVS.png
	*theBox7
	-gives 1 boxDamage, 100000 magicPoint for 1e+19 code
	-unlocks theBox8
	-locks theBox7
	-picture : http://i.imgur.com/xTcpu0Q.png
	*theBox8
	-gives 1 boxDamage, 10000000 magicPoint for 2e+22 code
	-unlocks theBox9
	-locks theBox8
	-picture : http://i.imgur.com/I7J5lDC.png
	*theBox9
	-gives 1 boxDamage, 1000000000 magicPoint for 5e+25 code
	-unlocks theBox10
	-locks theBox9
	-picture : http://i.imgur.com/xj5s3Ry.png
	*theBox10
	-gives 1 boxDamage, 100000000000 magicPoint for 1e+28 code
	-unlocks theBox11
	-locks theBox10
	-picture : http://i.imgur.com/UsfBQ7L.png
	*theBox11
	-gives 1 boxDamage, 10000000000000 magicPoint for 2e+29 code
	-unlocks theBox12
	-locks theBox11
	-picture : http://i.imgur.com/z1f2muF.png
	*theBox12
	-gives 1 boxDamage, 1000000000000000 magicPoint for 3e+30 code
	-unlocks theBox13
	-locks theBox12
	-picture : http://i.imgur.com/95u1W7l.png
	*theBox13
	-multiplies code 200%
	-multiplies totalCode 110%
	-converts code into totalCode
	-locks theBox13
	-picture : http://i.imgur.com/dOS5ibQ.png
	*speedResearch
	-gives 2 researchTime
	-gives 2 manualResearch
	-named Speed up research
	-picture : http://i.imgur.com/qic8V5N.png
	*speedResearch2
	-gives 2 researchTime2
	-gives 2 manualResearch
	-named Speed up magic research
	-picture : http://i.imgur.com/qoSQUBp.png
	*speedResearch3
	-gives 2 researchTime3
	-gives 2 manualResearch
	-named Speed up ultra-magic research
	-picture : http://i.imgur.com/dINKRVx.png
	*speedResearch4
	-gives 2 researchTime4
	-gives 2 manualResearch
	-named Speed up finality research
	-picture : http://i.imgur.com/zAvei2K.png
	*convertGame1
	-gives 100000 code, 100000 totalCode, 1 conversion for 1 game2
	-named Convert 1 game into 100,000 code
	*convertGame2
	-gives 1200000 code, 1200000 totalCode, 10 conversion for 10 game2
	-named Convert 10 games into 1,200,000 code
	*convertGame3
	-gives 15000000 code, 15000000 totalCode, 100 conversion for 100 game2
	-named Convert 100 games into 15,000,000 code
	*convertGame4
	-gives 200000000 code, 200000000 totalCode, 1000 conversion for 1000 game2
	-named Convert 1,000 games into 200,000,000 code
	*convertGame5
	-gives 2500000000 code, 2500000000 totalCode, 10000 conversion for 10000 game2
	-named Convert 10,000 games into 2,500,000,000 code
	*convertGame6
	-gives 200000 code, 200000 totalCode, 1 conversion for 1 game2
	-named Convert 1 game into 200,000 code
	*convertGame7
	-gives 2400000 code, 2400000 totalCode, 10 conversion for 10 game2
	-named Convert 10 games into 2,400,000 code
	*convertGame8
	-gives 30000000 code, 30000000 totalCode, 100 conversion for 100 game2
	-named Convert 100 games into 30,000,000 code
	*convertGame9
	-gives 400000000 code, 400000000 totalCode, 1000 conversion for 1000 game2
	-named Convert 1,000 games into 400,000,000 code
	*convertGame10
	-gives 5000000000 code, 5000000000 totalCode, 10000 conversion for 10000 game2
	-named Convert 10,000 games into 5,000,000,000 code
	*convertGame11
	-gives 60000000000 code, 60000000000 totalCode, 100000 conversion for 100000 game2
	-named Convert 100,000 games into 60,000,000,000 code
	*convertGame12
	-gives 750000000000 code, 750000000000 totalCode, 1000000 conversion for 1000000 game2
	-named Convert 1,000,000 games into 750,000,000,000 code
	*convertGame13
	-gives 25000000000 code, 25000000000 totalCode, 10000 conversion for 10000 game2
	-named Convert 10,000 games into 25,000,000,000 code
	*convertGame14
	-gives 300000000000 code, 300000000000 totalCode, 100000 conversion for 100000 game2
	-named Convert 100,000 games into 300,000,000,000 code
	*convertGame15
	-gives 3750000000000 code, 3750000000000 totalCode, 1000000 conversion for 1000000 game2
	-named Convert 1,000,000 games into 3,750,000,000,000 code
	*convertGame16
	-gives 50000000000000 code, 50000000000000 totalCode, 10000000 conversion for 10000000 game2
	-named Convert 10,000,000 games into 50,000,000,000,000 code
	*convertGame17
	-gives 600000000000000 code, 600000000000000 totalCode, 100000000 conversion for 100000000 game2
	-named Convert 100,000,000 games into 600,000,000,000,000 code
	*convertGame18
	-gives 7000000000000000 code, 7000000000000000 totalCode, 1000000000 conversion for 1000000000 game2
	-named Convert 1,000,000,000 games into 7,000,000,000,000,000 code
	*convertGame19
	-gives 8e+16 code, 8e+16 totalCode, 10000000000 conversion for 10000000000 game2
	-named Convert 10,000,000,000 games into 80,000,000,000,000,000 code
	*convertGame20
	-gives 9e+17 code, 9e+17 totalCode, 100000000000 conversion for 100000000000 game2
	-named Convert 100,000,000,000 games into 900,000,000,000,000,000 code
	*convertGame21
	-gives 1e+19 code, 1e+19 totalCode, 1000000000000 conversion for 1000000000000 game2
	-named Convert 1,000,000,000,000 games into 10,000,000,000,000,000,000 code
	*convertGame22
	-multiplies game2 500000000%
	-converts game2 to code
	-named Convert all games into code (1 game converts into 5,000,000 code)
	*convertGame23
	-multiplies game2 500000000%
	-converts game2 to totalCode
	-named Convert all games into progress (1 game converts into 5,000,000 progress)
	*convertGame24
	-multiplies game2 1000000000%
	-converts game2 to code
	-named Convert all games into code (1 game converts into 10,000,000 code)
	*convertGame25
	-multiplies game2 1000000000%
	-converts game2 to totalCode
	-named Convert all games into progress (1 game converts into 10,000,000 progress)
	*convertGame26
	-multiplies game2 2000000000%
	-converts game2 to code
	-named Convert all games into code (1 game converts into 20,000,000 code)
	*convertGame27
	-multiplies game2 2000000000%
	-converts game2 to totalCode
	-named Convert all games into progress (1 game converts into 20,000,000 progress)
	*reset
	-gives 1 eggGem
	-gives 1 resets
	-converts code to nothing
	-multiplies totalCode 0.0000000000000000001%
	-converts totalCode to prestige
	-converts popularity to nothing
	-converts positiveReview to nothing
	-converts game2 to nothing
	-converts manualWritten to nothing
	-converts codeWriterWritten to nothing
	-converts objectWritten to nothing
	-converts enemyWritten to nothing
	-converts playerWritten to nothing
	-converts levelWritten to nothing
	-converts gameWritten to nothing
	-converts fanbaseWritten to nothing
	-converts forumWritten to nothing
	-converts advertiseWritten to nothing
	-converts studioWritten to nothing
	-converts magicWritten to nothing
	-converts gameSeriesWritten to nothing
	-converts popularYoutuberWritten to nothing
	-converts maganiumWritten to nothing
	-converts finalityWritten to nothing
	-converts magicPoint to nothing
	-converts research to nothing
	-converts research2 to nothing
	-converts research3 to nothing
	-converts research4 to nothing
	-converts breakthroughbuilding to nothing
	-converts boxDamage to nothing
	-multiplies researchTime 50%
	-multiplies researchTime2 50%
	-multiplies researchTime3 50%
	-multiplies researchTime4 50%
	-converts magicPointBuilding to nothing
	-converts menu1 to nothing
	-converts menu2 to nothing
	-converts menu3 to nothing
	-converts breakthrough to nothing
	-locks researchUnlock
	-locks researchUnlock2
	-locks researchUnlock3
	-locks researchUnlock4
	-locks reset
	-locks overtake2
	-locks overtake3
	-locks overtake4
	-locks overtake5
	-locks overtake6
	-locks overtake7
	-locks overtake8
	-locks overtake9
	-locks overtake10
	-locks overtake11
	-locks overtake12
	-locks overtake13
	-locks overtake14
	-locks overtake15
	-locks overtake16
	-locks overtake17
	-locks overtake18
	-locks overtake19
	-locks overtake20
	-locks overtake21
	-locks overtake22
	-locks overtake23
	-locks overtake24
	-locks overtake25
	-locks overtake26
	-locks overtake27
	-locks overtake28
	-locks overtake29
	-locks overtake30
	-locks overtake31
	-locks overtake32
	-locks overtake33
	-locks overtake34
	-locks overtake35
	-locks overtake36
	-locks overtake37
	-locks overtake38
	-locks overtake39
	-locks overtake40
	-locks overtake41
	-locks overtake42
	-locks overtake43
	-locks overtake44
	-locks overtake45
	-locks overtake46
	-locks overtake47
	-locks overtake48
	-locks overtake49
	-locks overtake50
	-locks overtake51
	-locks overtake52
	-locks overtake53
	-locks overtake54
	-locks overtake55
	-locks overtake56
	-locks overtake57
	-locks overtake58
	-locks overtake59
	-locks overtake60
	-locks overtake61
	-locks overtake62
	-locks overtake63
	-locks overtake64
	-locks overtake65
	-locks overtake66
	-locks overtake67
	-locks overtake68
	-locks overtake69
	-locks overtake70
	-converts overtake51 to nothing
	-converts overtake52 to nothing
	-converts overtake53 to nothing
	-converts overtake54 to nothing
	-converts overtake55 to nothing
	-converts overtake56 to nothing
	-converts overtake57 to nothing
	-converts overtake58 to nothing
	-converts overtake59 to nothing
	-converts overtake60 to nothing
	-converts overtake61 to nothing
	-converts overtake62 to nothing
	-converts overtake63 to nothing
	-converts overtake64 to nothing
	-converts overtake65 to nothing
	-converts overtake66 to nothing
	-converts overtake67 to nothing
	-converts overtake68 to nothing
	-converts overtake69 to nothing
	-converts overtake70 to nothing
	-locks alternateUniverseReset
	-locks goldenBoxUnlock
	-locks theBox1
	-locks theBox2
	-locks theBox3
	-locks theBox4
	-locks theBox5
	-locks theBox6
	-locks theBox7
	-locks theBox8
	-locks theBox9
	-locks theBox10
	-locks theBox11
	-locks theBox12
	-locks theBox13
	-unlocks overtake1
	-converts maganiumGenerator to nothing
	-converts finality to nothing
	-converts codeWriter to nothing
	-converts object to nothing
	-converts enemy to nothing
	-converts player to nothing
	-converts level to nothing
	-converts game to nothing
	-converts gameProducer to nothing
	-converts fanbase to nothing
	-converts forum to nothing
	-converts advertise to nothing
	-converts studio to nothing
	-converts magic to nothing
	-converts gameSeries to nothing
	-converts popularYoutuber to nothing
	-converts bonus to nothing
	-converts stone1 to nothing
	-converts stone2 to nothing
	-converts stone3 to nothing
	-converts theBread to nothing
	-converts overtake1 to nothing
	-converts overtake2 to nothing
	-converts overtake3 to nothing
	-converts overtake4 to nothing
	-converts overtake5 to nothing
	-converts overtake6 to nothing
	-converts overtake7 to nothing
	-converts overtake8 to nothing
	-converts overtake9 to nothing
	-converts overtake10 to nothing
	-converts overtake11 to nothing
	-converts overtake12 to nothing
	-converts overtake13 to nothing
	-converts overtake14 to nothing
	-converts overtake15 to nothing
	-converts overtake16 to nothing
	-converts overtake17 to nothing
	-converts overtake18 to nothing
	-converts overtake19 to nothing
	-converts overtake20 to nothing
	-converts overtake21 to nothing
	-converts overtake22 to nothing
	-converts overtake23 to nothing
	-converts overtake24 to nothing
	-converts overtake25 to nothing
	-converts overtake26 to nothing
	-converts overtake27 to nothing
	-converts overtake28 to nothing
	-converts overtake29 to nothing
	-converts overtake30 to nothing
	-converts overtake31 to nothing
	-converts overtake32 to nothing
	-converts overtake33 to nothing
	-converts overtake34 to nothing
	-converts overtake35 to nothing
	-converts overtake36 to nothing
	-converts overtake37 to nothing
	-converts overtake38 to nothing
	-converts overtake39 to nothing
	-converts overtake40 to nothing
	-converts overtake41 to nothing
	-converts overtake42 to nothing
	-converts overtake43 to nothing
	-converts overtake44 to nothing
	-converts overtake45 to nothing
	-converts overtake46 to nothing
	-converts overtake47 to nothing
	-converts overtake48 to nothing
	-converts overtake49 to nothing
	-converts overtake50 to nothing
	-converts highReviewer to nothing
	-converts buildings to nothing
	-converts magicCore to nothing
	-converts orb to nothing
	-named Go to Alternate Universe (you lose all buildings and resources except godly lines of code and research. Research is halved. You get 1 godly line of code for every 1 zetta/sextillion lines of code)
	
 
Buildings :
        *overtake1
        -"Overtake Final Fantasy in popularity. Your video game company is now a success!"
        -costs 10101010101010 totalCode
	-gives 10101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Final Fantasy
        -locks overtake1
        -unlocks overtake2
	-unlocks researchUnlock
	-classed objective
	-visible
	-picture : http://i.imgur.com/zt3sei6.png
        *overtake2
        -"Overtake Call of Duty in popularity. Climbing up the ranks!"
        -costs 151515151515151 totalCode
	-gives 101515151515151 code when bought
        -gives 1 popularity when bought
        -named Overtake Call of Duty
        -locks overtake2
        -unlocks overtake3
	-unlocks researchUnlock2
	-classed objective
	-picture : http://i.imgur.com/3y9cZnH.png
        *overtake3
        -"Overtake Tetris in popularity. Your company is becoming even more successful. You're very rich now!"
        -costs 2020202020202020 totalCode
	-gives 1010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Tetris
        -locks overtake3
        -unlocks overtake4
	-unlocks goldenBoxUnlock
	-classed objective
	-picture : http://i.imgur.com/Sb9CGWt.png
        *overtake4
        -"Overtake Sonic in popularity."
        -costs 25252525252525252 totalCode
	-gives 10101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Sonic
        -locks overtake4
        -unlocks overtake5
	-classed objective
	-picture : http://i.imgur.com/akXfLr0.png
        *overtake5
        -"Overtake Need For Speed in popularity. Everyone at school is now playing it on their handheld devices!"
        -costs 303030303030303030 totalCode
        -gives 101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Need For Speed
        -locks overtake5
        -unlocks overtake6
	-classed objective
	-picture : http://i.imgur.com/591hTy3.png
        *overtake6
        -"Overtake Grand Theft Auto in popularity."
        -costs 3535353535353535353 totalCode
        -gives 1010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake GTA
        -locks overtake6
        -unlocks overtake7
	-unlocks researchUnlock3
	-classed objective
	-picture : http://i.imgur.com/3Q5de2b.png
        *overtake7
        -"Overtake The Sims in popularity. Popular YouTubers are now playing your games!"
        -costs 40404040404040404040 totalCode
        -gives 10101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake The Sims
        -locks overtake7
        -unlocks overtake8
	-classed objective
	-picture : http://i.imgur.com/Dc0M631.png
        *overtake8
        -"Overtake the Wii series in popularity. You're almost there!"
        -costs 454545454545454545454 totalCode
        -gives 101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Wii
        -locks overtake8
        -unlocks overtake9
	-classed objective
	-picture : http://i.imgur.com/0j9UNeG.png
        *overtake9
        -"Overtake Pokémon in popularity. You're almost there!"
        -costs 5050505050505050505050 totalCode
        -gives 1010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Pokémon
        -locks overtake9
        -unlocks overtake10
	-classed objective
	-picture : http://i.imgur.com/cS9dPwm.png
        *overtake10
        -"Overtake Mario in popularity. Nobody has not heard about your games now."
        -costs 60606060606060606060606 totalCode
        -gives 10101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Mario
        -locks overtake10
	-unlocks overtake11
	-unlocks alternateUniverseReset
	-unlocks researchUnlock4
	-classed finalobjective
	-picture : http://i.imgur.com/49VbGpu.png
        *overtake11
        -"After the other game series ascended, they become more popular than your games again. Overtake Ascended Final Fantasy in popularity."
        -costs 707070707070707070707070 totalCode
        -gives 101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Final Fantasy
        -locks overtake11
	-unlocks overtake12
	-classed objective
	-picture : http://i.imgur.com/qsbEerI.png
        *overtake12
        -"Overtake Ascended Call of Duty in popularity."
        -costs 8080808080808080808080808 totalCode
        -gives 1010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Call of Duty
        -locks overtake12
	-unlocks overtake13
	-classed objective
	-picture : http://i.imgur.com/OzcDLXi.png
        *overtake13
        -"Overtake Ascended Tetris in popularity."
        -costs 90909090909090909090909090 totalCode
        -gives 10101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Tetris
        -locks overtake13
	-unlocks overtake14
	-classed objective
	-picture : http://i.imgur.com/yeZOc9D.png
        *overtake14
        -"Overtake Ascended Sonic in popularity."
        -costs 1010101010101010101010101010 totalCode
        -gives 101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Sonic
        -locks overtake14
	-unlocks overtake15
	-classed objective
	-picture : http://i.imgur.com/ChHH6v8.png
        *overtake15
        -"Overtake Ascended Need For Speed in popularity."
        -costs 15151515151515151515151515151 totalCode
        -gives 1010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Need For Speed
        -locks overtake15
	-unlocks overtake16
	-classed objective
	-picture : http://i.imgur.com/7yNrYQq.png
        *overtake16
        -"Overtake Ascended Grand Theft Auto in popularity."
        -costs 202020202020202020202020202020 totalCode
        -gives 10101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended GTA
        -locks overtake16
	-unlocks overtake17
	-classed objective
	-picture : http://i.imgur.com/T0RDEOq.png
        *overtake17
        -"Overtake Ascended The Sims in popularity. <br><i>We all hate EA. Right?</i>"
        -costs 2525252525252525252525252525252 totalCode
        -gives 101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended The Sims
        -locks overtake17
	-unlocks overtake18
	-classed objective
	-picture : http://i.imgur.com/PdA3xyR.png
        *overtake18
        -"Overtake Ascended Wii in popularity. <br><i></i>"
        -costs 30303030303030303030303030303030 totalCode
        -gives 1010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Wii
        -locks overtake18
	-unlocks overtake19
	-classed objective
	-picture : http://i.imgur.com/G2RV5MF.png
        *overtake19
        -"Overtake Ascended Pokémon in popularity. <br><i>Gotta beat 'em all!</i>"
        -costs 353535353535353535353535353535353 totalCode
        -gives 10101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Pokémon
        -locks overtake19
	-unlocks overtake20
	-classed objective
	-picture : http://i.imgur.com/f9mycYs.png
        *overtake20
        -"Overtake Ascended Mario in popularity. <br><i>All done... right?</i>"
        -costs 4040404040404040404040404040404040 totalCode
        -gives 101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Mario
        -locks overtake20
	-unlocks overtake21
	-unlocks stoneUnlock1
	-classed finalobjective
	-picture : http://i.imgur.com/hhCgKXy.png
        *overtake21
        -"Overtake Final Fantasy EX in popularity. <br><i>We were wrong.</i>"
        -costs 45454545454545454545454545454545454 totalCode
        -gives 1010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Final Fantasy EX
        -locks overtake21
	-unlocks overtake22
	-classed objective
	-picture : http://i.imgur.com/NIDrXUO.png
        *overtake22
        -"Overtake Call of Duty EX in popularity. <br><i></i>"
        -costs 505050505050505050505050505050505050 totalCode
        -gives 10101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Call of Duty EX
        -locks overtake22
	-unlocks overtake23
	-classed objective
	-picture : http://i.imgur.com/bou9RFU.png
        *overtake23
        -"Overtake Tetris EX in popularity. <br><i></i>"
        -costs 5555555555555555555555555555555555555 totalCode
        -gives 101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Tetris EX
        -locks overtake23
	-unlocks overtake24
	-classed objective
	-picture : http://i.imgur.com/wjHHmQ1.png
        *overtake24
        -"Overtake Sonic EX in popularity. <br><i></i>"
        -costs 60606060606060606060606060606060606060 totalCode
        -gives 1010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Sonic EX
        -locks overtake24
	-unlocks overtake25
	-classed objective
	-picture : http://i.imgur.com/PNxB633.png
        *overtake25
        -"Overtake Need For Speed EX in popularity. <br><i></i>"
        -costs 656565656565656565656565656565656565656 totalCode
        -gives 10101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Need For Speed EX
        -locks overtake25
	-unlocks overtake26
	-classed objective
	-picture : http://i.imgur.com/DISD0Rr.png
        *overtake26
        -"Overtake Grand Theft Auto EX in popularity. <br><i></i>"
        -costs 7070707070707070707070707070707070707070 totalCode
        -gives 101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake GTA EX
        -locks overtake26
	-unlocks overtake27
	-classed objective
	-picture : http://i.imgur.com/Cm0Xghn.png
        *overtake27
        -"Overtake The Sims EX in popularity. <br><i></i>"
        -costs 75757575757575757575757575757575757575757 totalCode
        -gives 1010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake The Sims EX
        -locks overtake27
	-unlocks overtake28
	-classed objective
	-picture : http://i.imgur.com/Zd8UbJi.png
        *overtake28
        -"Overtake Wii EX in popularity. <br><i>Wii would like to play...</i>"
        -costs 808080808080808080808080808080808080808080 totalCode
        -gives 10101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Wii EX
        -locks overtake28
	-unlocks overtake29
	-classed objective
	-picture : http://i.imgur.com/ybIMwRM.png
        *overtake29
        -"Overtake Pokémon EX in popularity. <br><i></i>"
        -costs 8585858585858585858585858585858585858585858 totalCode
        -gives 101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Pokémon EX
        -locks overtake29
	-unlocks overtake30
	-classed objective
	-picture : http://i.imgur.com/kF7laVA.png
        *overtake30
        -"Overtake Mario EX in popularity. <br><i>Surely the last one.</i>"
        -costs 90909090909090909090909090909090909090909090 totalCode
        -gives 1010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Mario EX
        -locks overtake30
	-unlocks overtake31
	-classed finalobjective
	-picture : http://i.imgur.com/1ygBTmo.png
        *overtake31
        -"Overtake Final Fantasy EX Ultra in popularity. <br><i>How wrong we were. </i>"
        -costs 959595959595959595959595959595959595959595959 totalCode
        -gives 10101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Final Fantasy EX Ultra
        -locks overtake31
	-unlocks overtake32
	-classed objective
	-picture : http://i.imgur.com/1lGbBez.png
        *overtake32
        -"Overtake Call of Duty EX Ultra in popularity. <br><i> </i>"
        -costs 10101010101010101010101010101010101010101010101 totalCode
        -gives 101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Call of Duty EX Ultra
        -locks overtake32
	-unlocks overtake33
	-classed objective
	-picture : http://i.imgur.com/JZTONHe.png
        *overtake33
        -"Overtake Tetris EX Ultra in popularity. <br><i> </i>"
        -costs 121212121212121212121212121212121212121212121212 totalCode
        -gives 1010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Tetris EX Ultra
        -locks overtake33
	-unlocks overtake34
	-classed objective
	-picture : http://i.imgur.com/7WZsFAo.png
        *overtake34
        -"Overtake Sonic EX Ultra in popularity. <br><i>SANIC!11111!!!!11!one!111 </i>"
        -costs 1414141414141414141414141414141414141414141414141 totalCode
        -gives 10101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Sonic EX Ultra
        -locks overtake34
	-unlocks overtake35
	-classed objective
	-picture : http://i.imgur.com/TZYNzam.png
        *overtake35
        -"Overtake Need For Speed EX Ultra in popularity. <br><i></i>"
        -costs 16161616161616161616161616161616161616161616161616 totalCode
        -gives 101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Need For Speed EX Ultra
        -locks overtake35
	-unlocks overtake36
	-classed objective
	-picture : http://i.imgur.com/ED67FI5.png
        *overtake36
        -"Overtake Grand Theft Auto EX Ultra in popularity. <br><i></i>"
        -costs 181818181818181818181818181818181818181818181818181 totalCode
        -gives 1010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake GTA EX Ultra
        -locks overtake36
	-unlocks overtake37
	-classed objective
	-picture : http://i.imgur.com/p5WiWiZ.png
        *overtake37
        -"Overtake The Sims EX Ultra in popularity. <br><i></i>"
        -costs 2020202020202020202020202020202020202020202020202020 totalCode
        -gives 10101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake The Sims EX Ultra
        -locks overtake37
	-unlocks overtake38
	-classed objective
	-picture : http://i.imgur.com/lC2qQBm.png
        *overtake38
        -"Overtake Wii EX Ultra in popularity. <br><i></i>"
        -costs 22222222222222222222222222222222222222222222222222222 totalCode
        -gives 101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Wii EX Ultra
        -locks overtake38
	-unlocks overtake39
	-classed objective
	-picture : http://i.imgur.com/TD8njoC.png
        *overtake39
        -"Overtake Pokémon EX Ultra in popularity. <br><i></i>"
        -costs 242424242424242424242424242424242424242424242424242424 totalCode
        -gives 1010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Pokémon EX Ultra
        -locks overtake39
	-unlocks overtake40
	-classed objective
	-picture : http://i.imgur.com/ad9v9kN.png
        *overtake40
        -"Overtake Mario EX Ultra in popularity. <br><i>Probably not the last one.</i>"
        -costs 2626262626262626262626262626262626262626262626262626262 totalCode
        -gives 10101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Mario EX Ultra
        -locks overtake40
	-unlocks overtake41
	-unlocks stoneUnlock2
	-classed finalobjective
	-picture : http://i.imgur.com/yNpYuqN.png
        *overtake41
        -"Overtake Ascended Final Fantasy Type Alpha in popularity. <br><i>Here we go...</i>"
        -costs 28282828282828282828282828282828282828282828282828282828 totalCode
        -gives 101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Final Fantasy Type Alpha
        -locks overtake41
	-unlocks overtake42
	-classed objective
	-picture : http://i.imgur.com/iO7SqdO.png
        *overtake42
        -"Overtake Ascended Call of Duty Type Alpha in popularity. <br><i></i>"
        -costs 303030303030303030303030303030303030303030303030303030303 totalCode
        -gives 1010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Call of Duty Type Alpha
        -locks overtake42
	-unlocks overtake43
	-classed objective
	-picture : http://i.imgur.com/7vFhN4N.png
        *overtake43
        -"Overtake Ascended Tetris Type Alpha in popularity. <br><i></i>"
        -costs 3232323232323232323232323232323232323232323232323232323232 totalCode
        -gives 10101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Tetris Type Alpha
        -locks overtake43
	-unlocks overtake44
	-classed objective
	-picture : http://i.imgur.com/kdiPb7e.png
        *overtake44
        -"Overtake Ascended Sonic Type Alpha in popularity. <br><i></i>"
        -costs 34343434343434343434343434343434343434343434343434343434343 totalCode
        -gives 101010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Sonic Type Alpha
        -locks overtake44
	-unlocks overtake45
	-classed objective
	-picture : http://i.imgur.com/CGFypIu.png
        *overtake45
        -"Overtake Ascended Need for Speed Type Alpha in popularity. <br><i></i>"
        -costs 363636363636363636363636363636363636363636363636363636363636 totalCode
        -gives 1010101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Need for Speed Type Alpha
        -locks overtake45
	-unlocks overtake46
	-classed objective
	-picture : http://i.imgur.com/ojmzBAE.png
        *overtake46
        -"Overtake Ascended Grand Theft Auto Type Alpha in popularity. <br><i>How?</i>"
        -costs 3838383838383838383838383838383838383838383838383838383838383 totalCode
        -gives 10101010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended GTA Type Alpha
        -locks overtake46
	-unlocks overtake47
	-classed objective
	-picture : http://i.imgur.com/BdmvSpu.png
	*overtake47
        -"Overtake Ascended The Sims Type Alpha in popularity. <br><i>Why?</i>"
        -costs 40404040404040404040404040404040404040404040404040404040404040 totalCode
        -gives 101010101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended The Sims Type Alpha
        -locks overtake47
	-unlocks overtake48
	-classed objective
	-picture : http://i.imgur.com/Xw12Bjm.png
	*overtake48
        -"Overtake Ascended Wii Type Alpha in popularity. <br><i>Why are you still playing?</i>"
        -costs 424242424242424242424242424242424242424242424242424242424242424 totalCode
        -gives 1010101010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Wii Type Alpha
        -locks overtake48
	-unlocks overtake49
	-classed objective
	-picture : http://i.imgur.com/M3SJ07k.png
	*overtake49
        -"Overtake Ascended Pokémon Type Alpha in popularity. <br><i>How do you even got this far?</i>"
        -costs 4444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 10101010101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Pokémon Type Alpha
        -locks overtake49
	-unlocks overtake50
	-classed objective
	-picture : http://i.imgur.com/R9PHE61.png
	*overtake50
        -"Overtake Ascended Mario Type Alpha in popularity. <br><i>Do you even have a life?</i>"
        -costs 44444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 101010101010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Mario Type Alpha
        -locks overtake50
        -unlocks overtake51
	-classed finalobjective
	-picture : http://i.imgur.com/5GwaUfT.png
	*overtake51
        -"Overtake Ascended Final Fantasy Type Beta in popularity. <br><i></i>"
        -costs 444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 1010101010101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Final Fantasy Type Beta
        -locks overtake51
	-unlocks overtake52
	-classed objective
	-picture : http://i.imgur.com/iO7SqdO.png
        *overtake52
        -"Overtake Ascended Call of Duty Type Beta in popularity. <br><i></i>"
        -costs 4444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 10101010101010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Call of Duty Type Beta
        -locks overtake52
	-unlocks overtake53
	-classed objective
	-picture : http://i.imgur.com/7vFhN4N.png
        *overtake53
        -"Overtake Ascended Tetris Type Beta in popularity. <br><i></i>"
        -costs 44444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 101010101010101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Tetris Type Beta
        -locks overtake53
	-unlocks overtake54
	-classed objective
	-picture : http://i.imgur.com/kdiPb7e.png
        *overtake54
        -"Overtake Ascended Sonic Type Beta in popularity. <br><i></i>"
        -costs 444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 1010101010101010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Sonic Type Beta
        -locks overtake54
	-unlocks overtake55
	-classed objective
	-picture : http://i.imgur.com/CGFypIu.png
        *overtake55
        -"Overtake Ascended Need for Speed Type Beta in popularity. <br><i></i>"
        -costs 4444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 10101010101010101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Need for Speed Type Beta
        -locks overtake55
	-unlocks overtake56
	-classed objective
	-picture : http://i.imgur.com/ojmzBAE.png
        *overtake56
        -"Overtake Ascended Grand Theft Auto Type Beta in popularity. <br><i></i>"
        -costs 44444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 101010101010101010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended GTA Type Beta
        -locks overtake56
	-unlocks overtake57
	-classed objective
	-picture : http://i.imgur.com/BdmvSpu.png
	*overtake57
        -"Overtake Ascended The Sims Type Beta in popularity. <br><i></i>"
        -costs 444444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 1010101010101010101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended The Sims Type Beta
        -locks overtake57
	-unlocks overtake58
	-classed objective
	-picture : http://i.imgur.com/Xw12Bjm.png
	*overtake58
        -"Overtake Ascended Wii Type Beta in popularity. <br><i></i>"
        -costs 4444444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 10101010101010101010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Wii Type Beta
        -locks overtake58
	-unlocks overtake59
	-classed objective
	-picture : http://i.imgur.com/M3SJ07k.png
	*overtake59
        -"Overtake Ascended Pokémon Type Beta in popularity. <br><i></i>"
        -costs 44444444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 101010101010101010101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Pokémon Type Beta
        -locks overtake59
	-unlocks overtake60
	-classed objective
	-picture : http://i.imgur.com/R9PHE61.png
	*overtake60
        -"Overtake Ascended Mario Type Beta in popularity. <br><i></i>"
        -costs 444444444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 1010101010101010101010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Mario Type Beta
        -locks overtake60
	-unlocks overtake61
	-unlocks stoneUnlock3
	-classed finalobjective
	-picture : http://i.imgur.com/5GwaUfT.png
        *overtake61
        -"Overtake Ascended Final Fantasy Type Gamma in popularity. <br><i></i>"
        -costs 4444444444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 10101010101010101010101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Final Fantasy Type Gamma
        -locks overtake61
	-unlocks overtake62
	-classed objective
	-picture : http://i.imgur.com/iO7SqdO.png
        *overtake62
        -"Overtake Ascended Call of Duty Type Gamma in popularity. <br><i></i>"
        -costs 44444444444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 101010101010101010101010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Call of Duty Type Gamma
        -locks overtake62
	-unlocks overtake63
	-classed objective
	-picture : http://i.imgur.com/7vFhN4N.png
        *overtake63
        -"Overtake Ascended Tetris Type Gamma in popularity. <br><i></i>"
        -costs 444444444444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 1010101010101010101010101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Tetris Type Gamma
        -locks overtake63
	-unlocks overtake64
	-classed objective
	-picture : http://i.imgur.com/kdiPb7e.png
        *overtake64
        -"Overtake Ascended Sonic Type Gamma in popularity. <br><i></i>"
        -costs 4444444444444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 10101010101010101010101010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Sonic Type Gamma
        -locks overtake64
	-unlocks overtake65
	-classed objective
	-picture : http://i.imgur.com/CGFypIu.png
        *overtake65
        -"Overtake Ascended Need for Speed Type Gamma in popularity. <br><i></i>"
        -costs 44444444444444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 101010101010101010101010101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Need for Speed Type Gamma
        -locks overtake65
	-unlocks overtake66
	-classed objective
	-picture : http://i.imgur.com/ojmzBAE.png
        *overtake66
        -"Overtake Ascended Grand Theft Auto Type Gamma in popularity. <br><i></i>"
        -costs 444444444444444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 1010101010101010101010101010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended GTA Type Gamma
        -locks overtake66
	-unlocks overtake67
	-classed objective
	-picture : http://i.imgur.com/BdmvSpu.png
	*overtake67
        -"Overtake Ascended The Sims Type Gamma in popularity. <br><i></i>"
        -costs 4444444444444444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 10101010101010101010101010101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended The Sims Type Gamma
        -locks overtake67
	-unlocks overtake68
	-classed objective
	-picture : http://i.imgur.com/Xw12Bjm.png
	*overtake68
        -"Overtake Ascended Wii Type Gamma in popularity. <br><i></i>"
        -costs 44444444444444444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 101010101010101010101010101010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Wii Type Gamma
        -locks overtake68
	-unlocks overtake69
	-classed objective
	-picture : http://i.imgur.com/M3SJ07k.png
	*overtake69
        -"Overtake Ascended Pokémon Type Gamma in popularity. <br><i></i>"
        -costs 444444444444444444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 1010101010101010101010101010101010101010101010101010101010101010101010101010101010 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Pokémon Type Gamma
        -locks overtake69
	-unlocks overtake70
	-classed objective
	-picture : http://i.imgur.com/R9PHE61.png
	*overtake70
        -"Overtake Ascended Mario Type Gamma in popularity. <br><i></i>"
        -costs 4444444444444444444444444444444444444444444444444444444444444444444444444444444444444 totalCode
        -gives 1010101010101010101010101010101010101010101010101010101010101010101010101 code when bought
        -gives 1 popularity when bought
        -named Overtake Ascended Mario Type Gamma
        -locks overtake70
	-unlocks overtake71
	-classed finalobjective
	-picture : http://i.imgur.com/5GwaUfT.png
	*win
	-"Win the game (easy). Requires every 200 upgrade unlocked.
	-costs 1e+27 code
	-requires 200 codeWriter
	-requires 200 object
	-requires 200 enemy
	-requires 200 player
	-requires 200 level
	-requires 200 game
	-requires 200 fanbase
	-requires 200 forum
	-requires 200 advertise
	-requires 200 studio
	-requires 200 magic
	-requires 200 gameSeries
	-requires 200 popularYoutuber
	-requires 200 bonus
	-requires 200 maganiumGenerator
	-requires 200 finality
	-locks win
	-unlocks win2
	-classed win
	-named WIN THE GAME (easy)
	*win2
	-"Win the game (hard). Requires every 300 upgrade unlocked.
	-costs 1e+30 code
	-requires 300 codeWriter
	-requires 300 object
	-requires 300 enemy
	-requires 300 player
	-requires 300 level
	-requires 300 game
	-requires 300 fanbase
	-requires 300 forum
	-requires 300 advertise
	-requires 300 studio
	-requires 300 magic
	-requires 300 gameSeries
	-requires 300 popularYoutuber
	-requires 300 bonus
	-requires 300 maganiumGenerator
	-requires 300 finality
	-locks win2
	-unlocks win3
	-classed win
	-named WIN THE GAME (hard)
	*win3
	-"Win the game (very hard). Requires every 400 upgrade unlocked.
	-costs 1e+33 code
	-requires 400 codeWriter
	-requires 400 object
	-requires 400 enemy
	-requires 400 player
	-requires 400 level
	-requires 400 game
	-requires 400 fanbase
	-requires 400 forum
	-requires 400 advertise
	-requires 400 studio
	-requires 400 magic
	-requires 400 gameSeries
	-requires 400 popularYoutuber
	-requires 400 bonus
	-requires 400 maganiumGenerator
	-requires 400 finality
	-locks win3
	-unlocks win4
	-classed win
	-named WIN THE GAME (very hard)
	*win4
	-"Win the game (extreme). Requires 500 of every building.
	-costs 1e+40 code
	-requires 500 codeWriter
	-requires 500 object
	-requires 500 enemy
	-requires 500 player
	-requires 500 level
	-requires 500 game
	-requires 500 fanbase
	-requires 500 forum
	-requires 500 advertise
	-requires 500 studio
	-requires 500 magic
	-requires 500 gameSeries
	-requires 500 popularYoutuber
	-requires 500 bonus
	-requires 500 maganiumGenerator
	-requires 500 finality
	-locks win4
	-unlocks win5
	-classed win
	-named WIN THE GAME (extreme)
	*win5
	-"Win the game (super extreme). Requires 600 of every building.
	-costs 2.25e+44 code
	-requires 600 codeWriter
	-requires 600 object
	-requires 600 enemy
	-requires 600 player
	-requires 600 level
	-requires 600 game
	-requires 600 fanbase
	-requires 600 forum
	-requires 600 advertise
	-requires 600 studio
	-requires 600 magic
	-requires 600 gameSeries
	-requires 600 popularYoutuber
	-requires 600 bonus
	-requires 600 maganiumGenerator
	-requires 600 finality
	-locks win5
	-unlocks win6
	-classed win
	-named WIN THE GAME (super extreme)
	*win6
	-"Win the game (uber extreme). Requires 700 of every building.
	-costs 1e+49 code
	-requires 700 codeWriter
	-requires 700 object
	-requires 700 enemy
	-requires 700 player
	-requires 700 level
	-requires 700 game
	-requires 700 fanbase
	-requires 700 forum
	-requires 700 advertise
	-requires 700 studio
	-requires 700 magic
	-requires 700 gameSeries
	-requires 700 popularYoutuber
	-requires 700 bonus
	-requires 700 maganiumGenerator
	-requires 700 finality
	-classed win
	-locks win6
	-unlocks win7
	-named WIN THE GAME (uber extreme)
	*win7
	-"Win the game (insane). Requires 800 of every building.
	-costs 1e+53 code
	-requires 800 codeWriter
	-requires 800 object
	-requires 800 enemy
	-requires 800 player
	-requires 800 level
	-requires 800 game
	-requires 800 fanbase
	-requires 800 forum
	-requires 800 advertise
	-requires 800 studio
	-requires 800 magic
	-requires 800 gameSeries
	-requires 800 popularYoutuber
	-requires 800 bonus
	-requires 800 maganiumGenerator
	-requires 800 finality
	-locks win7
	-unlocks win8
	-classed win
	-named WIN THE GAME (insane)
	*win8
	-"Win the game (legendary). Requires 900 of every building.
	-costs 1e+57 code
	-requires 900 codeWriter
	-requires 900 object
	-requires 900 enemy
	-requires 900 player
	-requires 900 level
	-requires 900 game
	-requires 900 fanbase
	-requires 900 forum
	-requires 900 advertise
	-requires 900 studio
	-requires 900 magic
	-requires 900 gameSeries
	-requires 900 popularYoutuber
	-requires 900 bonus
	-requires 900 maganiumGenerator
	-requires 900 finality
	-locks win8
	-unlocks win9
	-classed win
	-named WIN THE GAME (legendary)
	*win9
	-"Win the game (impossible?) Requires 1000 of every building.
	-costs 1e+61 code
	-requires 1000 codeWriter
	-requires 1000 object
	-requires 1000 enemy
	-requires 1000 player
	-requires 1000 level
	-requires 1000 game
	-requires 1000 fanbase
	-requires 1000 forum
	-requires 1000 advertise
	-requires 1000 studio
	-requires 1000 magic
	-requires 1000 gameSeries
	-requires 1000 popularYoutuber
	-requires 1000 bonus
	-requires 1000 maganiumGenerator
	-requires 1000 finality
	-locks win9
	-unlocks win10
	-classed win
	-named WIN THE GAME (impossible?)
	*win10
	-"Win the game (IMPOSSIBLE!) Requires 1200 of every building.
	-costs 1e+69 code
	-requires 1200 codeWriter
	-requires 1200 object
	-requires 1200 enemy
	-requires 1200 player
	-requires 1200 level
	-requires 1200 game
	-requires 1200 fanbase
	-requires 1200 forum
	-requires 1200 advertise
	-requires 1200 studio
	-requires 1200 magic
	-requires 1200 gameSeries
	-requires 1200 popularYoutuber
	-requires 1200 bonus
	-requires 1200 maganiumGenerator
	-requires 1200 finality
	-locks win10
	-classed objective
	-named WIN THE GAME (impossible!)
	

	*startGame
	-"Starts the game. <br> <i> Let's make a game! </i>
	-gives 1 time
	-gives 0.00000000 positiveReview
	-named Start the game!
	-visible
	-unlocks writeCode
	-locks startGame
	-gives 1 eggGem when bought
	-gives 0 menu1
	-gives 0 menu2
	-gives 0 menu3
	-picture : http://i.imgur.com/IaCbOwO.png
 
        *codeWriter
        -"Writes <b>0.11</b> line of code per second.<br><i>Writes code, albeit slowly.</i>
        -costs 10 code
        -gives 0.11 code
        -gives 0.11 totalCode
        -gives 0.11 codeWriterWritten
	-represents 1 buildings
        -named Code Writer
        -visible
	-picture : http://i.imgur.com/q2brSfo.png

        *object
        -"Gives <b>1</b> code per second.<br><i>Platforms, houses, goals etc.</i>
        -costs 125 code
        -gives 1 code
        -gives 1 totalCode
        -gives 1 objectWritten
	-represents 1 buildings
        -named Object
        -visible
	-picture : http://i.imgur.com/soAy44Z.png
 
        *enemy
        -"Gives <b>4</b> code per second.<br><i>An obstacle in your game to give it some difficulty.</i>
        -costs 600 code
        -gives 4 code
        -gives 4 totalCode
        -gives 4 enemyWritten
	-represents 1 buildings
        -named Enemy
        -visible
	-picture : http://i.imgur.com/dul6RbM.png
 
        *player
        -"Gives <b>25</b> code per second.<br><i>A controllable player in your game. The game's not much good without one!</i>
        -costs 8000 code
        -gives 25 code
        -gives 25 totalCode
        -gives 25 playerWritten
	-represents 1 buildings
        -named Player
        -visible
	-picture : http://i.imgur.com/alSiEHx.png
 
        *level
        -"Gives <b>300</b> code per second.<br><i>Not the other type of level. A level in your game.</i>
        -costs 100000 code
        -gives 300 code
        -gives 300 totalCode
        -gives 300 levelWritten
	-represents 1 buildings
        -named Level
        -visible
	-picture : http://i.imgur.com/tLr6c0S.png

        *game
        -"Gives <b>5,000</b> code per second.<br><i>You've now released a game! People are now playing and reviewing your games.</i>
        -costs 3000000 code
        -gives 5000 code
	-gives 0.01 game2
        -gives 5000 totalCode
        -gives 5000 gameWritten
	-represents 1 buildings
        -named Game
        -visible
	-unlocks fanbase
	-picture : http://i.imgur.com/0TdiTef.png

        *gameProducer
        -"Gives <b>0.5</b> games per second.<br><i>This person makes games fast like a men.</i>
        -costs 30000000 code
	-gives 0.5 game2
        -named Game Producer
	-represents 1 buildings
	-picture : http://i.imgur.com/4usmcO4.png

        *fanbase
        -"Gives <b>60,000</b> code per second.<br><i>Your game now has a fanbase. This fanbase will attract the attention of more people, resulting on more people playing.</i>
        -costs 50000000 code
        -gives 60000 code
        -gives 60000 totalCode
        -gives 60000 fanbaseWritten
	-unlocks forum
	-represents 1 buildings
        -named Fanbase
	-picture : http://i.imgur.com/lGyXtZ7.png

        *forum
        -"Gives <b>2,000,000</b> code per second.<br><i>An official forum for your game. People talk about your game, give tips and tricks and even release mods!</i>
        -costs 3000000000 code
	-costs 6 game2
        -gives 2000000 code
        -gives 2000000 totalCode
        -gives 2000000 forumWritten
	-unlocks advertise
	-represents 1 buildings
        -named Forum
	-picture : http://i.imgur.com/4kZwAEs.png

        *advertise
        -"Gives <b>30,000,000</b> code per second.<br><i>Advertisements for your game. More and more people are hearing about your games.</i>
        -costs 50000000000 code
	-costs 100 game2
        -gives 30000000 code
        -gives 30000000 totalCode
        -gives 30000000 advertiseWritten
	-gives 0.0002 positiveReview
	-unlocks studio
	-represents 1 buildings
        -named Advertisement
	-picture : http://i.imgur.com/DyLWEx0.png

	*highReviewer
	-"Gives <b>1</b> positive review every ten seconds.<br><i>They frequently come and give us positive reviews, so that's good.</i>
	-costs 500000000000 code
	-costs 2500 game2
	-gives 0.1 positiveReview
	-named Positive Reviewer
	-represents 1 buildings
	-picture : http://i.imgur.com/zm50EuS.png

        *studio
        -"Gives <b>500,000,000</b> code per second.<br><i>A game studio for your company. People are hired from around the world to help you create games.</i>
        -costs 999999999999 code
	-costs 1500 game2
        -gives 500000000 code
        -gives 500000000 totalCode
        -gives 500000000 studioWritten
	-represents 1 buildings
        -named Game Studio
	-picture : http://i.imgur.com/pEqMQEs.png

        *magic
        -"Gives <b>4,000,000,000</b> code and <b>1</b> magic point per second.<br><i>A magic code writer that produces code at immense speeds.</i>
        -costs 10000000000000 code
	-costs 1 magicPoint
        -gives 4000000000 code
        -gives 4000000000 totalCode
        -gives 4000000000 magicWritten
	-gives 1 magicPoint
	-represents 1 buildings
        -named Magic Code Writer
	-picture : http://i.imgur.com/saGhIEc.png

	*magicCore
	-"This building makes ultra-magic generators <b>5%</b> more efficient. This building has a <b>1 in 50,000</b> chance every second of giving ultra-magic orbs, which make magic code writers <b>1%</b> more efficient. The more magic cores you have, the more ultra-magic orbs you get.<i><br>Magic Code Writers use orbs to enhance their spells.</i>
	-costs 1 magicPoint
	-unlocks at 8 popularity
        -gives 1 orb 0.002% of the time
	-named Magic Core
	-represents 1 buildings
	-price increases by 300%
	-selling gives back 0%
	-picture : http://i.imgur.com/5Rmdb17.png

        *gameSeries
        -"Gives <b>40,000,000,000</b> code per second.<br><i>A game series. This rapidly boosts popularity.</i>
        -costs 200000000000000 code
	-costs 25000 game2
        -gives 40000000000 code
        -gives 40000000000 totalCode
        -gives 40000000000 gameSeriesWritten
	-gives 0.1 positiveReview
	-gives 1 game2
	-represents 1 buildings
        -named Game Series
        -unlocks at 3 popularity
	-picture : http://i.imgur.com/QpBn0Ml.png

        *maganiumGenerator
        -"Gives <b>200,000,000,000</b> code and <b>50</b> magic points per second.<br><i>An ultra-magic generator. Powered by magic. Generates ridiculous amounts of code.</i>
        -costs 1600000000000000 code
	-costs 5005005 magicPoint
	-gives 50 magicPoint
        -gives 200000000000 code
        -gives 200000000000 totalCode
        -gives 200000000000 maganiumWritten
	-represents 1 buildings
        -named Ultra-magic Generator
        -unlocks at 5 popularity
	-picture : http://i.imgur.com/9HEJ2EG.png

        *popularYoutuber
        -"Gives <b>800,000,000,000</b> code per second.<br><i>Popular YouTubers are now playing your game. </i>
        -costs 9000000000000000000 code
	-costs 300000 game2
        -gives 800000000000 code
        -gives 800000000000 totalCode
        -gives 800000000000 popularYoutuberWritten
	-represents 1 buildings
        -named Popular YouTuber
	-picture : http://i.imgur.com/FNQq42J.png

        *finality
        -"Gives <b>32,641,282,565,120</b> code per second.<br><i>The Finality has arrived. The finality is a secret organisation that plans to dominate the world. As a bonus, it generates insane amounts of code. </i>
        -costs 1000000000000000000000 code
        -gives 32641282565120 code
        -gives 32641282565120 totalCode
        -gives 32641282565120 finalityWritten
	-represents 1 buildings
	-unlocks at 10 popularity
        -named Finality
	-picture : http://i.imgur.com/kmiEhVD.png

	*magicPointBuilding
	-"Gives <b>4</b> magic points per second. <br><i>These give you more magic points. Great.<br>Magic code writer upgrades also boost Magic Point Converters.</b>
	-costs 6600000000000000 code
	-gives 4 magicPoint
	-represents 1 buildings
	-unlocks at 3 popularity
	-named Magic Point Converter
	-picture : http://i.imgur.com/Z05oUIM.png

	*bonus
	-"Unlocks a variety of bonuses."
	-costs 1010101010101010 code
	-costs 1 positiveReview
	-named Bonus
	-unlocks at 6 popularity
	-represents 1 buildings
	-price increases by 109%
	-picture : http://i.imgur.com/PY8diwI.png

	*theBread
	-"Makes all other buildings more efficient.<i><br>Doesn't make sense, but who cares? It's a god-damn idle game!</i>
	-costs 1 code
	-named Bread
	-represents 1 buildings
	-price increases by 1000%
	-selling gives back 0%
        -picture : http://i.imgur.com/JCpbvcX.png
	
	*stone1
	-"Makes everything <b>0.2%</b> more efficient.<i><br>A strange stone, found in a cave. It has a mysterious effect that makes everything more powerful.</i>
	-costs 1e+30 code
	-named Stone of Time
	-represents 1 buildings
	-represents 1 stoneBuilding
	-picture : http://i.imgur.com/pDweRnc.png

	*stone2
	-"Makes everything <b>0.4%</b> more efficient.<i><br>Odd stones found in the galaxy. We can put them to use.</i>
	-costs 1e+50 code
	-named Stone of Space
	-represents 1 buildings
	-represents 1 stoneBuilding
	-picture : http://i.imgur.com/dmzd9TA.png

	*stone3
	-"Makes everything <b>1%</b> more efficient.<i><br>Combining the Stone of Time and the Stone of Space is very difficult. However Synergy Stones are insanely powerful.</i>
	-costs 1e+70 code
	-named Synergy Stone
	-represents 1 buildings
	-represents 1 stoneBuilding
	-picture : http://i.imgur.com/V17pFnb.png

	*stone4
	-"Makes everything <b>0.25%</b> more efficient per other stone owned.<i><br>Nothing is known about this stone.</i>
	-costs 1e+90 code
	-named Mystery Stone
	-represents 1 buildings
	-represents 1 stoneBuilding
	-picture : http://i.imgur.com/pOKnsU6.png

	*research
	-"Researches new upgrades!"
	-costs 1616161616161 code
	-represents 1 buildings
	-represents 1 breakthroughbuilding
	-named Research Lab
	-gives 1 researchTime
	-gives 0 menu1
	-gives 0 menu2
	-gives 0 menu3
	-locks research
	-picture : http://i.imgur.com/ZkDA9xl.png

	*research2
	-"Researches new magic upgrades!"
	-costs 16161616161616 code
	-represents 1 buildings
	-represents 1 breakthroughbuilding2
	-named Magic Research Lab
	-gives 1 researchTime2
	-gives 1000 magicPoint
	-gives 0 menu1
	-gives 0 menu2
	-gives 0 menu3
	-locks research2
	-picture : http://i.imgur.com/il7N2lE.png

	*research3
	-"Researches new ultra-magic upgrades!"
	-costs 16161616161616161 code
	-represents 1 buildings
	-represents 1 breakthroughbuilding3
	-named Ultra-magic Research Lab
	-gives 1 researchTime3
	-gives 10000000 magicPoint
	-gives 0 menu1
	-gives 0 menu2
	-gives 0 menu3
	-locks research3
	-picture : http://i.imgur.com/WAeJo1f.png

	*research4
	-"Unlocks the ability to enhance your secret organisation."
	-costs 16161616161616161616 code
	-represents 1 buildings
	-represents 1 breakthroughbuilding4
	-named Secret Organisation Building
	-gives 1 researchTime4
	-gives 0 menu1
	-gives 0 menu2
	-gives 0 menu3
	-locks research4
	-picture : http://i.imgur.com/VRhbwO1.png


	*breakthroughbuilding
	-costs 1 unimplemented
        -gives 1 breakthrough 0.006666666666666% of the time

	*breakthroughbuilding2
	-costs 1 unimplemented
        -gives 1 breakthrough 0.006666666666666% of the time

	*breakthroughbuilding3
	-costs 1 unimplemented
        -gives 1 breakthrough 0.006666666666666% of the time

	*breakthroughbuilding4
	-costs 1 unimplemented
        -gives 1 breakthrough 0.006666666666666% of the time

Upgrades :
        *cheat
        -"Click here to cheat. You dirty cheater. Gives infinity everything (used for testing purposes)"
	-costs 1 code
        -gives 99999999999999999999999999 code
	-gives 99999999999999999999999999 totalCode
	-gives 99999 positiveReview
        -named Cheat
	-unlocks at 1999999 codeWriter
	-picture : http://i.imgur.com/uwcdty9.png

	*siStuff
        -"This game uses <b>SI prefixes</b> in places. Si prefixes used in game:<br>peta = quadrillion<br>exa = quintillion<br>zetta = sextillion<br>yotta = septillion<br>xatta = 1 octillion<br>vitta = 1 nonillion</i>"
        -unlocks at 0 codeWriter
        -named SI prefixes
	-picture : http://i.imgur.com/v3UN7Rk.png

	*story1
	-"Everything is <b>3%</b> more efficient.<br><i>Upon travelling to an alternate universe, we found a book lying around in one of our game studios. It's as if there was a mysterious entity that was somehow helping us and following us around, that has written this book. It appears to be unfinished. It doesn't seem to open; we ended up blowing it up. When we blew it up, the pages went everywhere, somehow still intact. The pages only seem to activate when people give us enough good reviews.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Mysterious Book
	-unlocks at 1 resets
	-unlocks story2
	-costs 1 positiveReview
	-picture : http://i.imgur.com/E0Z3wV0.png
	*story2
	-"Everything is <b>3%</b> more efficient.<br><i>It was a fine morning when one person had the urge to create a game. The person wrote some code, then began hiring some code writers to help this person code.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 1
	-unlocks story3
	-costs 10 positiveReview
	-picture : http://i.imgur.com/ZTFFPP8.png
	*story3
	-"Everything is <b>3%</b> more efficient.<br><i>I was there the whole time, helping them, but they didn't know of my presence. We wrote objects, then enemies, and we gradually progressed...</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 2
	-unlocks story4
	-costs 100 positiveReview
	-costs 1 magicPoint
	-picture : http://i.imgur.com/ZTFFPP8.png
	*story4
	-"Everything is <b>3%</b> more efficient.<br><i>As we went on, we corrected mistakes. We fixed AI, controls, bugs, and eventually went on to release our first game. After a few games, fanbases started appearing, and they even made forums.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 3
	-unlocks story5
	-costs 1e+3 positiveReview
	-costs 1e+5 magicPoint
	-picture : http://i.imgur.com/tU5eQ3B.png
	*story5
	-"Everything is <b>3%</b> more efficient.<br><i>We made things better. We got better code writers, we teamed up, we made special enemies, improved gameplay, moderated the forums, and we started getting advertisements and game studios.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 4
	-unlocks story6
	-costs 1e+4 positiveReview
	-costs 1e+6 magicPoint
	-picture : http://i.imgur.com/tU5eQ3B.png
	*story6
	-"Everything is <b>3%</b> more efficient.<br><i>We kept going on. We built better studios, and the one person that started it all was gaining power. A strange substance that hadn't even been tested was used by that one person, and our popularity built up, enough to be regarded as a major game company. We were making money.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 5
	-unlocks story7
	-costs 1e+5 positiveReview
	-costs 1e+7 magicPoint
	-picture : http://i.imgur.com/x3u0VgU.png
	*story7
	-"Everything is <b>3%</b> more efficient.<br><i>We went on to try and become the best developers ever. As we became more and more popular, we started to become a lot more powerful. We were recruiting wizards, and eventually, we were making entire game series. With our great power, we researched new things, and became technologically advanced.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 6
	-unlocks story8
	-costs 1e+6 positiveReview
	-costs 1e+8 magicPoint
	-picture : http://i.imgur.com/x3u0VgU.png
	*story8
	-"Everything is <b>3%</b> more efficient.<br><i>One by one, we overtook series in popularity. Need for Speed went down, GTA didn't stand a chance, and things were greatly improving. Games were improving greatly. We were selling lots of games, the games had great music and sounds, enemies were very advanced, we did things that others have never done before. We even gained the power of FASTER MENNER.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 7
	-unlocks story9
	-costs 1e+7 positiveReview
	-costs 1e+9 magicPoint
	-picture : http://i.imgur.com/eQfz8Rf.png
	*story9
	-"Everything is <b>3%</b> more efficient.<br><i>Time went on. We became more intelligent, we had experienced engineers, we were researching a powerful thing known as ultra-magic, building generators that use ultra-magic, and we were even earning popular YouTubers.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 8
	-unlocks story10
	-costs 1e+8 positiveReview
	-costs 1e+10 magicPoint
	-picture : http://i.imgur.com/eQfz8Rf.png
	*story10
	-"Everything is <b>3%</b> more efficient.<br><i>Eventually, our games became more popular than Mario, and therefore our games were the most popular games ever made. We had become masters of technology, and we were able to travel to alternate universes.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 9
	-unlocks story11
	-costs 1e+9 positiveReview
	-costs 1e+11 magicPoint
	-picture : http://i.imgur.com/6cmxsgT.png
	*story11
	-"Everything is <b>3%</b> more efficient.<br><i>In the alternate universes, we ascended, and gained great power. The Finality was starting, and it was slowly taking over the world. The Ascended game series awaited us. Overcoming them was quite hard.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 10
	-unlocks story12
	-requires 10 popularity
	-costs 1e+10 positiveReview
	-costs 1e+12 magicPoint
	-picture : http://i.imgur.com/6cmxsgT.png
	*story12
	-"Everything is <b>3%</b> more efficient.<br><i>We gained the power of bread, and our code writers, and objects, were ascending. Our game studios were very powerful, and our creations were extraordinary. We started finding things that were previously unknown to man.<br><br>They do not know me. I know what happens before it happens. I can predict the future correctly.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 11
	-unlocks story13
	-requires 12 popularity
	-costs 1e+12 positiveReview
	-costs 1e+14 magicPoint
	-picture : http://i.imgur.com/wrLt1IW.png
	*story13
	-"Everything is <b>3%</b> more efficient.<br><i>We gained insane amounts of power, and we were doing things that had never been done before. We were enhancing things to great power, and the Finality was starting to control the world.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 12
	-unlocks story14
	-requires 15 popularity
	-costs 1e+14 positiveReview
	-costs 1e+16 magicPoint
	-picture : http://i.imgur.com/wrLt1IW.png
	*story14
	-"Everything is <b>3%</b> more efficient.<br><i>It seems to stop there. But searching in the secret underground of the game studio seems to reveal some more pages, and a door that requires a passcode. We read the second set of pages.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named The Other Pages
	-unlocks story15
	-costs 1e+18 positiveReview
	-costs 1e+20 magicPoint
	-requires 22 popularity
	-picture : http://i.imgur.com/9gnRphg.png
	*story15
	-"Everything is <b>3%</b> more efficient.<br><i>We went really far. The Finality was wiping out every other game series, we had discovered The Unknown, we had descended into Hell, and even went to the Moon.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 13
	-unlocks story16
	-costs 1e+22 positiveReview
	-costs 1e+24 magicPoint
	-requires 30 popularity
	-picture : http://i.imgur.com/2mQrxzD.png
	*story16
	-"Everything is <b>3%</b> more efficient.<br><i>We had pretty much dominated the world. And we also successfully went to Mars and back.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 14
	-unlocks story17
	-costs 1e+26 positiveReview
	-costs 1e+28 magicPoint
	-requires 35 popularity
	-picture : http://i.imgur.com/0SqajdO.png
	*story17
	-"Everything is <b>3%</b> more efficient.<br><i>We had ascended really far, we were super-advanced in technology, and we had been to odd places in the galaxy.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 15
	-unlocks story18
	-costs 1e+30 positiveReview
	-costs 1e+32 magicPoint
	-requires 35 popularity
	-picture : http://i.imgur.com/0yipcjp.png
	*story18
	-"Everything is <b>3%</b> more efficient.<br><i>We had even breached reality. We had been to the edges of the universe, and had discovered new worlds.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 16
	-unlocks story19
	-costs 1e+35 positiveReview
	-costs 1e+37 magicPoint
	-requires 45 popularity
	-picture : http://i.imgur.com/5pOaIJz.png
	*story19
	-"Everything is <b>3%</b> more efficient.<br><i>...and we won a cookie. CODE TO THE DOOR: 2336669109</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Page 17
	-unlocks story20
	-costs 1e+40 positiveReview
	-costs 1e+42 magicPoint
	-requires 50 popularity
	-picture : http://i.imgur.com/9hoahEz.png
	*story20
	-"Everything is <b>50%</b> more efficient.<br><i>We inputted the code into the door. We finally met this mysterious entity. It seemed to be made out of the Unknown. He pressed a switch, and its power of the Unknown seemed to spread everywhere, greatly enhancing everything we had.</i><br><br>
	-multiplies efficiency of writeCode by 150%
	-multiplies efficiency of codeWriter by 150%
	-multiplies efficiency of object by 150%
	-multiplies efficiency of enemy by 150%
	-multiplies efficiency of player by 150%
	-multiplies efficiency of level by 150%
	-multiplies efficiency of game by 150%
	-multiplies efficiency of fanbase by 150%
	-multiplies efficiency of forum by 150%
	-multiplies efficiency of advertise by 150%
	-multiplies efficiency of studio by 150%
	-multiplies efficiency of magic by 150%
	-multiplies efficiency of gameSeries by 150%
	-multiplies efficiency of popularYoutuber by 150%
	-multiplies efficiency of gameProducer by 150%
	-multiplies efficiency of highReviewer by 150%
	-multiplies efficiency of maganiumGenerator by 150%
	-multiplies efficiency of finality by 150%
	-multiplies efficiency of magicPointBuilding by 150%
	-named Encountering the Mysterious Entity
	-costs 1e+50 positiveReview
	-costs 1e+52 magicPoint
	-requires 50 popularity, 1e+70 totalCode
	-gives 1 lel101
	-picture : http://i.imgur.com/gZZcTLJ.png
	*story21
	-"Everything is <b>50%</b> more efficient.<br><i>After doing extensive research on Developer Bakanium, it was revealed that his original name was Johnson, before he received some kind of name change.<br><br> Further research shows that he came from a universe about destroying walls, and the other people were sick of Johnson so they used what's called a "Reality Compromiser" to change his name to Bakanium, (not very successfully) alter his brain, and send him to a random alternate universe, which happened to be this one.<br><br>After doing more research on how Bakanium acted in the world of destroying walls, we decided to use our own "Reality Compromiser" to banish him to another alternate universe, and he now has to spend the rest of his miserable life locked up in a cell.<br><br>"laaaaaaaaame" -4chan anonymous</i><br><br>
	-multiplies efficiency of writeCode by 150%
	-multiplies efficiency of codeWriter by 150%
	-multiplies efficiency of object by 150%
	-multiplies efficiency of enemy by 150%
	-multiplies efficiency of player by 150%
	-multiplies efficiency of level by 150%
	-multiplies efficiency of game by 150%
	-multiplies efficiency of fanbase by 150%
	-multiplies efficiency of forum by 150%
	-multiplies efficiency of advertise by 150%
	-multiplies efficiency of studio by 150%
	-multiplies efficiency of magic by 150%
	-multiplies efficiency of gameSeries by 150%
	-multiplies efficiency of popularYoutuber by 150%
	-multiplies efficiency of gameProducer by 150%
	-multiplies efficiency of highReviewer by 150%
	-multiplies efficiency of maganiumGenerator by 150%
	-multiplies efficiency of finality by 150%
	-multiplies efficiency of magicPointBuilding by 150%
	-named The Truth about Developer Bakanium
	-costs 1e+60 positiveReview
	-costs 1e+62 magicPoint
	-unlocks at 1 lel101
	-picture : http://i.imgur.com/UnRCZlM.png

	*trophy1
	-"Everything is <b>1%</b> more efficient.<br><i>How do you make a trophy out of sand?</i><br><br>Every trophy has a requirement. Buying the trophy costs nothing, and should be done when you unlock it, but each trophy requires you to have a certain amount of code (not progress).<br><br>The next trophy unlocks at 1,000 code.
	-multiplies efficiency of writeCode by 101%
	-multiplies efficiency of codeWriter by 101%
	-multiplies efficiency of object by 101%
	-multiplies efficiency of enemy by 101%
	-multiplies efficiency of player by 101%
	-multiplies efficiency of level by 101%
	-multiplies efficiency of game by 101%
	-multiplies efficiency of fanbase by 101%
	-multiplies efficiency of forum by 101%
	-multiplies efficiency of advertise by 101%
	-multiplies efficiency of studio by 101%
	-multiplies efficiency of magic by 101%
	-multiplies efficiency of gameSeries by 101%
	-multiplies efficiency of popularYoutuber by 101%
	-multiplies efficiency of gameProducer by 101%
	-multiplies efficiency of highReviewer by 101%
	-multiplies efficiency of maganiumGenerator by 101%
	-multiplies efficiency of finality by 101%
	-multiplies efficiency of magicPointBuilding by 101%
	-named Sand Trophy
	-unlocks at 100 code
	-picture : http://i.imgur.com/l6zsQuG.png
	*trophy2
	-"Everything is <b>1%</b> more efficient.<br><i>Jokes related to this trophy are generally pretty dirty.</i><br><br>The next trophy unlocks at 10,000 code.
	-multiplies efficiency of writeCode by 101%
	-multiplies efficiency of codeWriter by 101%
	-multiplies efficiency of object by 101%
	-multiplies efficiency of enemy by 101%
	-multiplies efficiency of player by 101%
	-multiplies efficiency of level by 101%
	-multiplies efficiency of game by 101%
	-multiplies efficiency of fanbase by 101%
	-multiplies efficiency of forum by 101%
	-multiplies efficiency of advertise by 101%
	-multiplies efficiency of studio by 101%
	-multiplies efficiency of magic by 101%
	-multiplies efficiency of gameSeries by 101%
	-multiplies efficiency of popularYoutuber by 101%
	-multiplies efficiency of gameProducer by 101%
	-multiplies efficiency of highReviewer by 101%
	-multiplies efficiency of maganiumGenerator by 101%
	-multiplies efficiency of finality by 101%
	-multiplies efficiency of magicPointBuilding by 101%
	-named Dirt Trophy
	-unlocks at 1e+3 code
	-picture : http://i.imgur.com/0bAqCY0.png
	*trophy3
	-"Everything is <b>1%</b> more efficient.<br><i>"WOOD! So funny!" ~Developer Bakanium<br><br>"Not THAT kind of "wood"." ~Every other developer</i><br><br>The next trophy unlocks at 100,000 code. Every trophy requires 10 times the code the previous one required.
	-multiplies efficiency of writeCode by 101%
	-multiplies efficiency of codeWriter by 101%
	-multiplies efficiency of object by 101%
	-multiplies efficiency of enemy by 101%
	-multiplies efficiency of player by 101%
	-multiplies efficiency of level by 101%
	-multiplies efficiency of game by 101%
	-multiplies efficiency of fanbase by 101%
	-multiplies efficiency of forum by 101%
	-multiplies efficiency of advertise by 101%
	-multiplies efficiency of studio by 101%
	-multiplies efficiency of magic by 101%
	-multiplies efficiency of gameSeries by 101%
	-multiplies efficiency of popularYoutuber by 101%
	-multiplies efficiency of gameProducer by 101%
	-multiplies efficiency of highReviewer by 101%
	-multiplies efficiency of maganiumGenerator by 101%
	-multiplies efficiency of finality by 101%
	-multiplies efficiency of magicPointBuilding by 101%
	-named Wood Trophy
	-unlocks at 1e+4 code
	-picture : http://i.imgur.com/3wuCJtO.png
	*trophy4
	-"Everything is <b>1%</b> more efficient.<br><i>The people making trophies aren't using very good materials.</i><br><br>
	-multiplies efficiency of writeCode by 101%
	-multiplies efficiency of codeWriter by 101%
	-multiplies efficiency of object by 101%
	-multiplies efficiency of enemy by 101%
	-multiplies efficiency of player by 101%
	-multiplies efficiency of level by 101%
	-multiplies efficiency of game by 101%
	-multiplies efficiency of fanbase by 101%
	-multiplies efficiency of forum by 101%
	-multiplies efficiency of advertise by 101%
	-multiplies efficiency of studio by 101%
	-multiplies efficiency of magic by 101%
	-multiplies efficiency of gameSeries by 101%
	-multiplies efficiency of popularYoutuber by 101%
	-multiplies efficiency of gameProducer by 101%
	-multiplies efficiency of highReviewer by 101%
	-multiplies efficiency of maganiumGenerator by 101%
	-multiplies efficiency of finality by 101%
	-multiplies efficiency of magicPointBuilding by 101%
	-named Paper Trophy
	-unlocks at 1e+5 code
	-picture : http://i.imgur.com/ZFq51CM.png
	*trophy5
	-"Everything is <b>1%</b> more efficient.<br><i>"How about... plastic? Is that good?" ~Trophy Designer</i><br><br>
	-multiplies efficiency of writeCode by 101%
	-multiplies efficiency of codeWriter by 101%
	-multiplies efficiency of object by 101%
	-multiplies efficiency of enemy by 101%
	-multiplies efficiency of player by 101%
	-multiplies efficiency of level by 101%
	-multiplies efficiency of game by 101%
	-multiplies efficiency of fanbase by 101%
	-multiplies efficiency of forum by 101%
	-multiplies efficiency of advertise by 101%
	-multiplies efficiency of studio by 101%
	-multiplies efficiency of magic by 101%
	-multiplies efficiency of gameSeries by 101%
	-multiplies efficiency of popularYoutuber by 101%
	-multiplies efficiency of gameProducer by 101%
	-multiplies efficiency of highReviewer by 101%
	-multiplies efficiency of maganiumGenerator by 101%
	-multiplies efficiency of finality by 101%
	-multiplies efficiency of magicPointBuilding by 101%
	-named Plastic Trophy
	-unlocks at 1e+6 code
	-picture : http://i.imgur.com/zi3mGqc.png
	*trophy6
	-"Everything is <b>1%</b> more efficient.<br><i>Please do not throw stones. This includes this trophy.</i><br><br>
	-multiplies efficiency of writeCode by 101%
	-multiplies efficiency of codeWriter by 101%
	-multiplies efficiency of object by 101%
	-multiplies efficiency of enemy by 101%
	-multiplies efficiency of player by 101%
	-multiplies efficiency of level by 101%
	-multiplies efficiency of game by 101%
	-multiplies efficiency of fanbase by 101%
	-multiplies efficiency of forum by 101%
	-multiplies efficiency of advertise by 101%
	-multiplies efficiency of studio by 101%
	-multiplies efficiency of magic by 101%
	-multiplies efficiency of gameSeries by 101%
	-multiplies efficiency of popularYoutuber by 101%
	-multiplies efficiency of gameProducer by 101%
	-multiplies efficiency of highReviewer by 101%
	-multiplies efficiency of maganiumGenerator by 101%
	-multiplies efficiency of finality by 101%
	-multiplies efficiency of magicPointBuilding by 101%
	-named Stone Trophy
	-unlocks at 1e+7 code
	-picture : http://i.imgur.com/kB0C8Fe.png
	*trophy7
	-"Everything is <b>1%</b> more efficient.<br><i>"Painting the trophies different colours surely makes them better."~ Trophy Designer #36</i><br><br>
	-multiplies efficiency of writeCode by 101%
	-multiplies efficiency of codeWriter by 101%
	-multiplies efficiency of object by 101%
	-multiplies efficiency of enemy by 101%
	-multiplies efficiency of player by 101%
	-multiplies efficiency of level by 101%
	-multiplies efficiency of game by 101%
	-multiplies efficiency of fanbase by 101%
	-multiplies efficiency of forum by 101%
	-multiplies efficiency of advertise by 101%
	-multiplies efficiency of studio by 101%
	-multiplies efficiency of magic by 101%
	-multiplies efficiency of gameSeries by 101%
	-multiplies efficiency of popularYoutuber by 101%
	-multiplies efficiency of gameProducer by 101%
	-multiplies efficiency of highReviewer by 101%
	-multiplies efficiency of maganiumGenerator by 101%
	-multiplies efficiency of finality by 101%
	-multiplies efficiency of magicPointBuilding by 101%
	-named Red Trophy
	-unlocks at 1e+8 code
	-picture : http://i.imgur.com/bXsZWG0.png
	*trophy8
	-"Everything is <b>1%</b> more efficient.<br><i>*insert 8-bit achievement noise*</i><br><br>
	-multiplies efficiency of writeCode by 101%
	-multiplies efficiency of codeWriter by 101%
	-multiplies efficiency of object by 101%
	-multiplies efficiency of enemy by 101%
	-multiplies efficiency of player by 101%
	-multiplies efficiency of level by 101%
	-multiplies efficiency of game by 101%
	-multiplies efficiency of fanbase by 101%
	-multiplies efficiency of forum by 101%
	-multiplies efficiency of advertise by 101%
	-multiplies efficiency of studio by 101%
	-multiplies efficiency of magic by 101%
	-multiplies efficiency of gameSeries by 101%
	-multiplies efficiency of popularYoutuber by 101%
	-multiplies efficiency of gameProducer by 101%
	-multiplies efficiency of highReviewer by 101%
	-multiplies efficiency of maganiumGenerator by 101%
	-multiplies efficiency of finality by 101%
	-multiplies efficiency of magicPointBuilding by 101%
	-named Blue Trophy
	-unlocks at 1e+9 code
	-picture : http://i.imgur.com/TsEZdP5.png
	*trophy9
	-"Everything is <b>1%</b> more efficient.<br><i>There was a bit of debate about which was the best of red, green, and blue. Green got the most votes.</i><br><br>
	-multiplies efficiency of writeCode by 101%
	-multiplies efficiency of codeWriter by 101%
	-multiplies efficiency of object by 101%
	-multiplies efficiency of enemy by 101%
	-multiplies efficiency of player by 101%
	-multiplies efficiency of level by 101%
	-multiplies efficiency of game by 101%
	-multiplies efficiency of fanbase by 101%
	-multiplies efficiency of forum by 101%
	-multiplies efficiency of advertise by 101%
	-multiplies efficiency of studio by 101%
	-multiplies efficiency of magic by 101%
	-multiplies efficiency of gameSeries by 101%
	-multiplies efficiency of popularYoutuber by 101%
	-multiplies efficiency of gameProducer by 101%
	-multiplies efficiency of highReviewer by 101%
	-multiplies efficiency of maganiumGenerator by 101%
	-multiplies efficiency of finality by 101%
	-multiplies efficiency of magicPointBuilding by 101%
	-named Green Trophy
	-unlocks at 1e+10 code
	-picture : http://i.imgur.com/KDBGQaR.png
	*trophy10
	-"Everything is <b>1%</b> more efficient.<br><i>*insert a joke about irony here*<br><br>"People that make jokes about irony are stupid people. I hate stupid people." ~Develope Bakanium<br><br>"The irony. THE FUCKING IRONY." ~Developer Kezelwal</i><br><br>
	-multiplies efficiency of writeCode by 101%
	-multiplies efficiency of codeWriter by 101%
	-multiplies efficiency of object by 101%
	-multiplies efficiency of enemy by 101%
	-multiplies efficiency of player by 101%
	-multiplies efficiency of level by 101%
	-multiplies efficiency of game by 101%
	-multiplies efficiency of fanbase by 101%
	-multiplies efficiency of forum by 101%
	-multiplies efficiency of advertise by 101%
	-multiplies efficiency of studio by 101%
	-multiplies efficiency of magic by 101%
	-multiplies efficiency of gameSeries by 101%
	-multiplies efficiency of popularYoutuber by 101%
	-multiplies efficiency of gameProducer by 101%
	-multiplies efficiency of highReviewer by 101%
	-multiplies efficiency of maganiumGenerator by 101%
	-multiplies efficiency of finality by 101%
	-multiplies efficiency of magicPointBuilding by 101%
	-named Iron Trophy
	-unlocks at 1e+11 code
	-picture : http://i.imgur.com/VTRpStc.png
	*trophy11
	-"Everything is <b>1%</b> more efficient.<br><i>Developer Bakanium tried to STEEL this trophy. But it didn't work.</i><br><br>
	-multiplies efficiency of writeCode by 101%
	-multiplies efficiency of codeWriter by 101%
	-multiplies efficiency of object by 101%
	-multiplies efficiency of enemy by 101%
	-multiplies efficiency of player by 101%
	-multiplies efficiency of level by 101%
	-multiplies efficiency of game by 101%
	-multiplies efficiency of fanbase by 101%
	-multiplies efficiency of forum by 101%
	-multiplies efficiency of advertise by 101%
	-multiplies efficiency of studio by 101%
	-multiplies efficiency of magic by 101%
	-multiplies efficiency of gameSeries by 101%
	-multiplies efficiency of popularYoutuber by 101%
	-multiplies efficiency of gameProducer by 101%
	-multiplies efficiency of highReviewer by 101%
	-multiplies efficiency of maganiumGenerator by 101%
	-multiplies efficiency of finality by 101%
	-multiplies efficiency of magicPointBuilding by 101%
	-named Steel Trophy
	-unlocks at  1e+12 code
	-picture : http://i.imgur.com/fyZd7Mr.png
	*trophy12
	-"Everything is <b>1%</b> more efficient.<br><i>If you kill someone with that trophy, I'm calling the cops.</i><br><br>
	-multiplies efficiency of writeCode by 101%
	-multiplies efficiency of codeWriter by 101%
	-multiplies efficiency of object by 101%
	-multiplies efficiency of enemy by 101%
	-multiplies efficiency of player by 101%
	-multiplies efficiency of level by 101%
	-multiplies efficiency of game by 101%
	-multiplies efficiency of fanbase by 101%
	-multiplies efficiency of forum by 101%
	-multiplies efficiency of advertise by 101%
	-multiplies efficiency of studio by 101%
	-multiplies efficiency of magic by 101%
	-multiplies efficiency of gameSeries by 101%
	-multiplies efficiency of popularYoutuber by 101%
	-multiplies efficiency of gameProducer by 101%
	-multiplies efficiency of highReviewer by 101%
	-multiplies efficiency of maganiumGenerator by 101%
	-multiplies efficiency of finality by 101%
	-multiplies efficiency of magicPointBuilding by 101%
	-named Copper Trophy
	-unlocks at 1e+13 code
	-picture : http://i.imgur.com/l622Isn.png
	*trophy13
	-"Everything is <b>2%</b> more efficient.<br><i>Hey look, the trophy designers are getting better at making trophies!</i><br><br>
	-multiplies efficiency of writeCode by 102%
	-multiplies efficiency of codeWriter by 102%
	-multiplies efficiency of object by 102%
	-multiplies efficiency of enemy by 102%
	-multiplies efficiency of player by 102%
	-multiplies efficiency of level by 102%
	-multiplies efficiency of game by 102%
	-multiplies efficiency of fanbase by 102%
	-multiplies efficiency of forum by 102%
	-multiplies efficiency of advertise by 102%
	-multiplies efficiency of studio by 102%
	-multiplies efficiency of magic by 102%
	-multiplies efficiency of gameSeries by 102%
	-multiplies efficiency of popularYoutuber by 102%
	-multiplies efficiency of gameProducer by 102%
	-multiplies efficiency of highReviewer by 102%
	-multiplies efficiency of maganiumGenerator by 102%
	-multiplies efficiency of finality by 102%
	-multiplies efficiency of magicPointBuilding by 102%
	-named Bronze Trophy
	-unlocks at 1e+14 code
	-picture : http://i.imgur.com/eIS39os.png
	*trophy14
	-"Everything is <b>2%</b> more efficient.<br><i>"Silver! Second place, right?" ~Miner #42</i><br><br>
	-multiplies efficiency of writeCode by 102%
	-multiplies efficiency of codeWriter by 102%
	-multiplies efficiency of object by 102%
	-multiplies efficiency of enemy by 102%
	-multiplies efficiency of player by 102%
	-multiplies efficiency of level by 102%
	-multiplies efficiency of game by 102%
	-multiplies efficiency of fanbase by 102%
	-multiplies efficiency of forum by 102%
	-multiplies efficiency of advertise by 102%
	-multiplies efficiency of studio by 102%
	-multiplies efficiency of magic by 102%
	-multiplies efficiency of gameSeries by 102%
	-multiplies efficiency of popularYoutuber by 102%
	-multiplies efficiency of gameProducer by 102%
	-multiplies efficiency of highReviewer by 102%
	-multiplies efficiency of maganiumGenerator by 102%
	-multiplies efficiency of finality by 102%
	-multiplies efficiency of magicPointBuilding by 102%
	-named Silver Trophy
	-unlocks at 1e+15 code
	-picture : http://i.imgur.com/xXm8RBO.png
	*trophy15
	-"Everything is <b>2%</b> more efficient.<br><i>Sometimes, gold is 1st place. Not this time.<br><br>"Can't we use gold for pickaxes instead?" ~Developer Bakanium</i><br><br>
	-multiplies efficiency of writeCode by 102%
	-multiplies efficiency of codeWriter by 102%
	-multiplies efficiency of object by 102%
	-multiplies efficiency of enemy by 102%
	-multiplies efficiency of player by 102%
	-multiplies efficiency of level by 102%
	-multiplies efficiency of game by 102%
	-multiplies efficiency of fanbase by 102%
	-multiplies efficiency of forum by 102%
	-multiplies efficiency of advertise by 102%
	-multiplies efficiency of studio by 102%
	-multiplies efficiency of magic by 102%
	-multiplies efficiency of gameSeries by 102%
	-multiplies efficiency of popularYoutuber by 102%
	-multiplies efficiency of gameProducer by 102%
	-multiplies efficiency of highReviewer by 102%
	-multiplies efficiency of maganiumGenerator by 102%
	-multiplies efficiency of finality by 102%
	-multiplies efficiency of magicPointBuilding by 102%
	-named Gold Trophy
	-unlocks at 1e+16 code
	-picture : http://i.imgur.com/ocyfkFT.png
	*trophy16
	-"Everything is <b>2%</b> more efficient.<br><i>"Maybe if I make the gold trophy better, it will be 1st place, right?"<br><br>"...right?" ~Miner #66</i><br><br>
	-multiplies efficiency of writeCode by 102%
	-multiplies efficiency of codeWriter by 102%
	-multiplies efficiency of object by 102%
	-multiplies efficiency of enemy by 102%
	-multiplies efficiency of player by 102%
	-multiplies efficiency of level by 102%
	-multiplies efficiency of game by 102%
	-multiplies efficiency of fanbase by 102%
	-multiplies efficiency of forum by 102%
	-multiplies efficiency of advertise by 102%
	-multiplies efficiency of studio by 102%
	-multiplies efficiency of magic by 102%
	-multiplies efficiency of gameSeries by 102%
	-multiplies efficiency of popularYoutuber by 102%
	-multiplies efficiency of gameProducer by 102%
	-multiplies efficiency of highReviewer by 102%
	-multiplies efficiency of maganiumGenerator by 102%
	-multiplies efficiency of finality by 102%
	-multiplies efficiency of magicPointBuilding by 102%
	-named Bright Gold Trophy
	-unlocks at 1e+17 code
	-picture : http://i.imgur.com/k6tUdtg.png
	*trophy17
	-"Everything is <b>2%</b> more efficient.<br><i>"haha noob didnt you know that platinum is better than gold" ~Miner #97</i><br><br>
	-multiplies efficiency of writeCode by 102%
	-multiplies efficiency of codeWriter by 102%
	-multiplies efficiency of object by 102%
	-multiplies efficiency of enemy by 102%
	-multiplies efficiency of player by 102%
	-multiplies efficiency of level by 102%
	-multiplies efficiency of game by 102%
	-multiplies efficiency of fanbase by 102%
	-multiplies efficiency of forum by 102%
	-multiplies efficiency of advertise by 102%
	-multiplies efficiency of studio by 102%
	-multiplies efficiency of magic by 102%
	-multiplies efficiency of gameSeries by 102%
	-multiplies efficiency of popularYoutuber by 102%
	-multiplies efficiency of gameProducer by 102%
	-multiplies efficiency of highReviewer by 102%
	-multiplies efficiency of maganiumGenerator by 102%
	-multiplies efficiency of finality by 102%
	-multiplies efficiency of magicPointBuilding by 102%
	-named Platinum Trophy
	-unlocks at 1e+18 code
	-picture : http://i.imgur.com/NKpHSEg.png
	*trophy18
	-"Everything is <b>3%</b> more efficient.<br><i>"But we also agreed that gems > metals. Who's laughing now?" ~Miner #145</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Ruby Trophy
	-unlocks at 1e+19 code
	-picture : http://i.imgur.com/MYLcVtJ.png
	*trophy19
	-"Everything is <b>3%</b> more efficient.<br><i>There was a debate about whether ruby or sapphire was better. But as we agreed that green is better than blue which is better than red, we ranked this trophy higher.</i><br><br>Every trophy after this requires 100 times more code than the previous one.
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Sapphire Trophy
	-unlocks at 1e+20 code
	-picture : http://i.imgur.com/uDSPJHu.png
	*trophy20
	-"Everything is <b>3%</b> more efficient.<br><i>Jokes about gems are emerOLD, especially recycled jokes that have been used in other games than this.</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Emerald Trophy
	-unlocks at 1e+22 code
	-picture : http://i.imgur.com/aU5Q3D7.png
	*trophy21
	-"Everything is <b>3%</b> more efficient.<br><i>Developer Bakanium somehow managed to get this trophy higher ranked.</i><br><br>"THE FUCK? WHY ARE CRAPPY PEARLS RATED HIGHER THAN EMERALDS?" ~Miner #200, aka Rageman</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Pearl Trophy
	-unlocks at 1e+24 code
	-picture : http://i.imgur.com/2phlANz.png
	*trophy22
	-"Everything is <b>3%</b> more efficient.<br><i>"DIAMOND! That obviously wins!" ~Miner #200</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Diamond Trophy
	-unlocks at 1e+26 code
	-picture : http://i.imgur.com/uQC2oca.png
	*trophy23
	-"Everything is <b>3%</b> more efficient.<br><i>"WOAH! THESE DIAMONDS ARE AMAZING! OMGGGGGGG!!!!!!!!!" ~Miner #200</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Coloured Diamond Trophy
	-unlocks at 1e+28 code
	-picture : http://i.imgur.com/VCBvzeb.png
	*trophy24
	-"Everything is <b>3%</b> more efficient.<br><i>"lel, i win. i found this ancient mysterious stone and made a trophy out of it. I WIN" ~Miner #401<br><br>"FUCK THIS SHIT I'M QUITTING" ~Miner #200</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Rusting Trophy
	-unlocks at 1e+30 code
	-picture : http://i.imgur.com/AlW5fZS.png
	*trophy25
	-"Everything is <b>3%</b> more efficient.<br><i>We're sending our miners into alternate universes, where adamantium actually exists!</i><br><br>
	-multiplies efficiency of writeCode by 103%
	-multiplies efficiency of codeWriter by 103%
	-multiplies efficiency of object by 103%
	-multiplies efficiency of enemy by 103%
	-multiplies efficiency of player by 103%
	-multiplies efficiency of level by 103%
	-multiplies efficiency of game by 103%
	-multiplies efficiency of fanbase by 103%
	-multiplies efficiency of forum by 103%
	-multiplies efficiency of advertise by 103%
	-multiplies efficiency of studio by 103%
	-multiplies efficiency of magic by 103%
	-multiplies efficiency of gameSeries by 103%
	-multiplies efficiency of popularYoutuber by 103%
	-multiplies efficiency of gameProducer by 103%
	-multiplies efficiency of highReviewer by 103%
	-multiplies efficiency of maganiumGenerator by 103%
	-multiplies efficiency of finality by 103%
	-multiplies efficiency of magicPointBuilding by 103%
	-named Adamantium Trophy
	-unlocks at 1e+32 code
	-picture : http://i.imgur.com/hbiRKBK.png
	*trophy26
	-"Everything is <b>4%</b> more efficient.<br><i>"NO ONE CAN BEAT THIS!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!" ~Miner #1337</i><br><br>
	-multiplies efficiency of writeCode by 104%
	-multiplies efficiency of codeWriter by 104%
	-multiplies efficiency of object by 104%
	-multiplies efficiency of enemy by 104%
	-multiplies efficiency of player by 104%
	-multiplies efficiency of level by 104%
	-multiplies efficiency of game by 104%
	-multiplies efficiency of fanbase by 104%
	-multiplies efficiency of forum by 104%
	-multiplies efficiency of advertise by 104%
	-multiplies efficiency of studio by 104%
	-multiplies efficiency of magic by 104%
	-multiplies efficiency of gameSeries by 104%
	-multiplies efficiency of popularYoutuber by 104%
	-multiplies efficiency of gameProducer by 104%
	-multiplies efficiency of highReviewer by 104%
	-multiplies efficiency of maganiumGenerator by 104%
	-multiplies efficiency of finality by 104%
	-multiplies efficiency of magicPointBuilding by 104%
	-named Unobtainium Trophy
	-unlocks at 1e+34 code
	-picture : http://i.imgur.com/CrBxqs7.png
	*trophy27
	-"Everything is <b>4%</b> more efficient.<br><i>Our wizards are making trophies, and here's a basic trophy they made.</i><br><br>
	-multiplies efficiency of writeCode by 104%
	-multiplies efficiency of codeWriter by 104%
	-multiplies efficiency of object by 104%
	-multiplies efficiency of enemy by 104%
	-multiplies efficiency of player by 104%
	-multiplies efficiency of level by 104%
	-multiplies efficiency of game by 104%
	-multiplies efficiency of fanbase by 104%
	-multiplies efficiency of forum by 104%
	-multiplies efficiency of advertise by 104%
	-multiplies efficiency of studio by 104%
	-multiplies efficiency of magic by 104%
	-multiplies efficiency of gameSeries by 104%
	-multiplies efficiency of popularYoutuber by 104%
	-multiplies efficiency of gameProducer by 104%
	-multiplies efficiency of highReviewer by 104%
	-multiplies efficiency of maganiumGenerator by 104%
	-multiplies efficiency of finality by 104%
	-multiplies efficiency of magicPointBuilding by 104%
	-named Magic Trophy
	-unlocks at 1e+36 code
	-picture : http://i.imgur.com/tDkySwo.png
	*trophy28
	-"Everything is <b>4%</b> more efficient.<br><i>Using advanced magic, it's possible to make this.</i><br><br>
	-multiplies efficiency of writeCode by 104%
	-multiplies efficiency of codeWriter by 104%
	-multiplies efficiency of object by 104%
	-multiplies efficiency of enemy by 104%
	-multiplies efficiency of player by 104%
	-multiplies efficiency of level by 104%
	-multiplies efficiency of game by 104%
	-multiplies efficiency of fanbase by 104%
	-multiplies efficiency of forum by 104%
	-multiplies efficiency of advertise by 104%
	-multiplies efficiency of studio by 104%
	-multiplies efficiency of magic by 104%
	-multiplies efficiency of gameSeries by 104%
	-multiplies efficiency of popularYoutuber by 104%
	-multiplies efficiency of gameProducer by 104%
	-multiplies efficiency of highReviewer by 104%
	-multiplies efficiency of maganiumGenerator by 104%
	-multiplies efficiency of finality by 104%
	-multiplies efficiency of magicPointBuilding by 104%
	-named Ultra Magic Trophy
	-unlocks at 1e+38 code
	-picture : http://i.imgur.com/aFweQxw.png
	*trophy29
	-"Everything is <b>4%</b> more efficient.<br><i>This trophy is made out of a very rare "Rainbow Stone", that we found in an ancient ruin in a cave. It requires a lot of magic to make something out of Rainbow Stone.<br><br>"They should really rename this trophy "Rainbow Dash Trophy"." ~Developer Mlepfim</i><br><br>Every trophy after this one requires 1,000 times more code than the previous one.
	-multiplies efficiency of writeCode by 104%
	-multiplies efficiency of codeWriter by 104%
	-multiplies efficiency of object by 104%
	-multiplies efficiency of enemy by 104%
	-multiplies efficiency of player by 104%
	-multiplies efficiency of level by 104%
	-multiplies efficiency of game by 104%
	-multiplies efficiency of fanbase by 104%
	-multiplies efficiency of forum by 104%
	-multiplies efficiency of advertise by 104%
	-multiplies efficiency of studio by 104%
	-multiplies efficiency of magic by 104%
	-multiplies efficiency of gameSeries by 104%
	-multiplies efficiency of popularYoutuber by 104%
	-multiplies efficiency of gameProducer by 104%
	-multiplies efficiency of highReviewer by 104%
	-multiplies efficiency of maganiumGenerator by 104%
	-multiplies efficiency of finality by 104%
	-multiplies efficiency of magicPointBuilding by 104%
	-named Rainbow Trophy
	-unlocks at 1e+40 code
	-picture : http://i.imgur.com/pSV5EEH.png
	*trophy30
	-"Everything is <b>2%</b> more efficient.<br><i>A Wizard Master made this trophy. It's made out of pixels.</i><br><br>
	-multiplies efficiency of writeCode by 104%
	-multiplies efficiency of codeWriter by 104%
	-multiplies efficiency of object by 104%
	-multiplies efficiency of enemy by 104%
	-multiplies efficiency of player by 104%
	-multiplies efficiency of level by 104%
	-multiplies efficiency of game by 104%
	-multiplies efficiency of fanbase by 104%
	-multiplies efficiency of forum by 104%
	-multiplies efficiency of advertise by 104%
	-multiplies efficiency of studio by 104%
	-multiplies efficiency of magic by 104%
	-multiplies efficiency of gameSeries by 104%
	-multiplies efficiency of popularYoutuber by 104%
	-multiplies efficiency of gameProducer by 104%
	-multiplies efficiency of highReviewer by 104%
	-multiplies efficiency of maganiumGenerator by 104%
	-multiplies efficiency of finality by 104%
	-multiplies efficiency of magicPointBuilding by 104%
	-named RGB Trophy
	-unlocks at 1e+43 code
	-picture : http://i.imgur.com/WGXMpGH.png
	*trophy31
	-"Everything is <b>2%</b> more efficient.<br><i>Another Wizard Master made this trophy as well.</i><br><br>
	-multiplies efficiency of writeCode by 104%
	-multiplies efficiency of codeWriter by 104%
	-multiplies efficiency of object by 104%
	-multiplies efficiency of enemy by 104%
	-multiplies efficiency of player by 104%
	-multiplies efficiency of level by 104%
	-multiplies efficiency of game by 104%
	-multiplies efficiency of fanbase by 104%
	-multiplies efficiency of forum by 104%
	-multiplies efficiency of advertise by 104%
	-multiplies efficiency of studio by 104%
	-multiplies efficiency of magic by 104%
	-multiplies efficiency of gameSeries by 104%
	-multiplies efficiency of popularYoutuber by 104%
	-multiplies efficiency of gameProducer by 104%
	-multiplies efficiency of highReviewer by 104%
	-multiplies efficiency of maganiumGenerator by 104%
	-multiplies efficiency of finality by 104%
	-multiplies efficiency of magicPointBuilding by 104%
	-named CMY Trophy
	-unlocks at 1e+46 code
	-picture : http://i.imgur.com/lMrPFl4.png
	*trophy32
	-"Everything is <b>5%</b> more efficient.<br><i>Made by the second most powerful wizard, this trophy is darkness.</i><br><br>
	-multiplies efficiency of writeCode by 105%
	-multiplies efficiency of codeWriter by 105%
	-multiplies efficiency of object by 105%
	-multiplies efficiency of enemy by 105%
	-multiplies efficiency of player by 105%
	-multiplies efficiency of level by 105%
	-multiplies efficiency of game by 105%
	-multiplies efficiency of fanbase by 105%
	-multiplies efficiency of forum by 105%
	-multiplies efficiency of advertise by 105%
	-multiplies efficiency of studio by 105%
	-multiplies efficiency of magic by 105%
	-multiplies efficiency of gameSeries by 105%
	-multiplies efficiency of popularYoutuber by 105%
	-multiplies efficiency of gameProducer by 105%
	-multiplies efficiency of highReviewer by 105%
	-multiplies efficiency of maganiumGenerator by 105%
	-multiplies efficiency of finality by 105%
	-multiplies efficiency of magicPointBuilding by 105%
	-named Dark Trophy
	-unlocks at 1e+49 code
	-picture : http://i.imgur.com/Gzyh6pp.png
	*trophy33
	-"Everything is <b>5%</b> more efficient.<br><i>Another creation by the second most powerful wizard. It's pure light.</i><br><br>
	-multiplies efficiency of writeCode by 105%
	-multiplies efficiency of codeWriter by 105%
	-multiplies efficiency of object by 105%
	-multiplies efficiency of enemy by 105%
	-multiplies efficiency of player by 105%
	-multiplies efficiency of level by 105%
	-multiplies efficiency of game by 105%
	-multiplies efficiency of fanbase by 105%
	-multiplies efficiency of forum by 105%
	-multiplies efficiency of advertise by 105%
	-multiplies efficiency of studio by 105%
	-multiplies efficiency of magic by 105%
	-multiplies efficiency of gameSeries by 105%
	-multiplies efficiency of popularYoutuber by 105%
	-multiplies efficiency of gameProducer by 105%
	-multiplies efficiency of highReviewer by 105%
	-multiplies efficiency of maganiumGenerator by 105%
	-multiplies efficiency of finality by 105%
	-multiplies efficiency of magicPointBuilding by 105%
	-named Light Trophy
	-unlocks at 1e+52 code
	-picture : http://i.imgur.com/Gix6Ppf.png
	*trophy34
	-"Everything is <b>5%</b> more efficient.<br><i>Combining the two was a very tricky skill indeed. We have this trophy.It's amazing that making it is possible.<br><br>"Why not just paint a trophy black and white?" ~Developer Bakanium<br><br>"Damn just fuck up!" ~Developer VomitGhost</i><br><br>
	-multiplies efficiency of writeCode by 105%
	-multiplies efficiency of codeWriter by 105%
	-multiplies efficiency of object by 105%
	-multiplies efficiency of enemy by 105%
	-multiplies efficiency of player by 105%
	-multiplies efficiency of level by 105%
	-multiplies efficiency of game by 105%
	-multiplies efficiency of fanbase by 105%
	-multiplies efficiency of forum by 105%
	-multiplies efficiency of advertise by 105%
	-multiplies efficiency of studio by 105%
	-multiplies efficiency of magic by 105%
	-multiplies efficiency of gameSeries by 105%
	-multiplies efficiency of popularYoutuber by 105%
	-multiplies efficiency of gameProducer by 105%
	-multiplies efficiency of highReviewer by 105%
	-multiplies efficiency of maganiumGenerator by 105%
	-multiplies efficiency of finality by 105%
	-multiplies efficiency of magicPointBuilding by 105%
	-named Light and Dark Trophy
	-unlocks at 1e+55 code
	-picture : http://i.imgur.com/hivQA9L.png
	*trophy35
	-"Everything is <b>5%</b> more efficient.<br><i>The Wizard Lord awoke, and combined the power of the finality to make this trophy.</i><br><br>
	-multiplies efficiency of writeCode by 105%
	-multiplies efficiency of codeWriter by 105%
	-multiplies efficiency of object by 105%
	-multiplies efficiency of enemy by 105%
	-multiplies efficiency of player by 105%
	-multiplies efficiency of level by 105%
	-multiplies efficiency of game by 105%
	-multiplies efficiency of fanbase by 105%
	-multiplies efficiency of forum by 105%
	-multiplies efficiency of advertise by 105%
	-multiplies efficiency of studio by 105%
	-multiplies efficiency of magic by 105%
	-multiplies efficiency of gameSeries by 105%
	-multiplies efficiency of popularYoutuber by 105%
	-multiplies efficiency of gameProducer by 105%
	-multiplies efficiency of highReviewer by 105%
	-multiplies efficiency of maganiumGenerator by 105%
	-multiplies efficiency of finality by 105%
	-multiplies efficiency of magicPointBuilding by 105%
	-named Finality Trophy
	-unlocks at 1e+58 code
	-picture : http://i.imgur.com/iobThOK.png
	*trophy36
	-"Everything is <b>6%</b> more efficient.<br><i>The most powerful trophy to ever be made by a wizard. DON'T TOUCH IT. <br>GET AWAY, Developer Bakanium. It eats everything that touches it. That's why the wizard cast a levitation spell on it. Actually, do touch it. No one cares about you.</i><br><br>Every trophy after this requires 10,000 times more code than the previous one.
	-multiplies efficiency of writeCode by 106%
	-multiplies efficiency of codeWriter by 106%
	-multiplies efficiency of object by 106%
	-multiplies efficiency of enemy by 106%
	-multiplies efficiency of player by 106%
	-multiplies efficiency of level by 106%
	-multiplies efficiency of game by 106%
	-multiplies efficiency of fanbase by 106%
	-multiplies efficiency of forum by 106%
	-multiplies efficiency of advertise by 106%
	-multiplies efficiency of studio by 106%
	-multiplies efficiency of magic by 106%
	-multiplies efficiency of gameSeries by 106%
	-multiplies efficiency of popularYoutuber by 106%
	-multiplies efficiency of gameProducer by 106%
	-multiplies efficiency of highReviewer by 106%
	-multiplies efficiency of maganiumGenerator by 106%
	-multiplies efficiency of finality by 106%
	-multiplies efficiency of magicPointBuilding by 106%
	-named Unknown Trophy
	-unlocks at 1e+61 code
	-picture : http://i.imgur.com/zOCoDfl.png
	*trophy37
	-"Everything is <b>7%</b> more efficient.<br><i>The trophy that contains the power of all the ascends. Even a wizard couldn't make it.</i><br><br>Every trophy after this now requires 100,000 times more code than the previous one.
	-multiplies efficiency of writeCode by 107%
	-multiplies efficiency of codeWriter by 107%
	-multiplies efficiency of object by 107%
	-multiplies efficiency of enemy by 107%
	-multiplies efficiency of player by 107%
	-multiplies efficiency of level by 107%
	-multiplies efficiency of game by 107%
	-multiplies efficiency of fanbase by 107%
	-multiplies efficiency of forum by 107%
	-multiplies efficiency of advertise by 107%
	-multiplies efficiency of studio by 107%
	-multiplies efficiency of magic by 107%
	-multiplies efficiency of gameSeries by 107%
	-multiplies efficiency of popularYoutuber by 107%
	-multiplies efficiency of gameProducer by 107%
	-multiplies efficiency of highReviewer by 107%
	-multiplies efficiency of maganiumGenerator by 107%
	-multiplies efficiency of finality by 107%
	-multiplies efficiency of magicPointBuilding by 107%
	-named Ultimate Trophy
	-unlocks at 1e+65 code
	-picture : http://i.imgur.com/qDqCZfm.png
	*trophy38
	-"Everything is <b>8%</b> more efficient.<br><i>We won a cookie once, so why don't we make a trophy out of that?</i><br><br>
	-multiplies efficiency of writeCode by 108%
	-multiplies efficiency of codeWriter by 108%
	-multiplies efficiency of object by 108%
	-multiplies efficiency of enemy by 108%
	-multiplies efficiency of player by 108%
	-multiplies efficiency of level by 108%
	-multiplies efficiency of game by 108%
	-multiplies efficiency of fanbase by 108%
	-multiplies efficiency of forum by 108%
	-multiplies efficiency of advertise by 108%
	-multiplies efficiency of studio by 108%
	-multiplies efficiency of magic by 108%
	-multiplies efficiency of gameSeries by 108%
	-multiplies efficiency of popularYoutuber by 108%
	-multiplies efficiency of gameProducer by 108%
	-multiplies efficiency of highReviewer by 108%
	-multiplies efficiency of maganiumGenerator by 108%
	-multiplies efficiency of finality by 108%
	-multiplies efficiency of magicPointBuilding by 108%
	-named Cookie Trophy
	-unlocks at 1e+70 code
	-picture : http://i.imgur.com/HqdHSv9.png
	*trophy39
	-"Everything is <b>9%</b> more efficient.<br><i>Taking "egg" itself, cloning it, and making it into a trophy was indeed the most dangerous thing we've ever one. We dodged 132 lightning strikes, and all our game studios almost burnt down SEVEN TIMES! Was worth it, though.</i><br><br>
	-multiplies efficiency of writeCode by 109%
	-multiplies efficiency of codeWriter by 109%
	-multiplies efficiency of object by 109%
	-multiplies efficiency of enemy by 109%
	-multiplies efficiency of player by 109%
	-multiplies efficiency of level by 109%
	-multiplies efficiency of game by 109%
	-multiplies efficiency of fanbase by 109%
	-multiplies efficiency of forum by 109%
	-multiplies efficiency of advertise by 109%
	-multiplies efficiency of studio by 109%
	-multiplies efficiency of magic by 109%
	-multiplies efficiency of gameSeries by 109%
	-multiplies efficiency of popularYoutuber by 109%
	-multiplies efficiency of gameProducer by 109%
	-multiplies efficiency of highReviewer by 109%
	-multiplies efficiency of maganiumGenerator by 109%
	-multiplies efficiency of finality by 109%
	-multiplies efficiency of magicPointBuilding by 109%
	-named "egg" Trophy
	-unlocks at 1e+75 code
	-picture : http://i.imgur.com/D6WLF4g.png
	*trophy40
	-"Everything is <b>10%</b> more efficient.<br><i>This trophy spontaneously appeared without any logical explanation. It wasn't created by magic, it didn't transform from something else. This might mean one thing: Omega has arrived.</i><br><br>You're done.
	-multiplies efficiency of writeCode by 110%
	-multiplies efficiency of codeWriter by 110%
	-multiplies efficiency of object by 110%
	-multiplies efficiency of enemy by 110%
	-multiplies efficiency of player by 110%
	-multiplies efficiency of level by 110%
	-multiplies efficiency of game by 110%
	-multiplies efficiency of fanbase by 110%
	-multiplies efficiency of forum by 110%
	-multiplies efficiency of advertise by 110%
	-multiplies efficiency of studio by 110%
	-multiplies efficiency of magic by 110%
	-multiplies efficiency of gameSeries by 110%
	-multiplies efficiency of popularYoutuber by 110%
	-multiplies efficiency of gameProducer by 110%
	-multiplies efficiency of highReviewer by 110%
	-multiplies efficiency of maganiumGenerator by 110%
	-multiplies efficiency of finality by 110%
	-multiplies efficiency of magicPointBuilding by 110%
	-named Omega Trophy
	-unlocks at 1e+80 code
	-picture : http://i.imgur.com/GsWtNpV.png

	*goldenBoxUnlock
	-"Unlocks the golden box. <i>Legend has it that great rewards await the one that can open the legendary box...</i>
	-costs 1000000 code
	-unlocks theBox1
	-named Golden Box
	-unlocks at 1000000 totalCode
	-unlocks goldenBoxInfo1
	-unlocks goldenBoxInfo2
	-unlocks goldenBoxInfo3
	-picture : http://i.imgur.com/TkCSZup.png
	*goldenBoxInfo1
	-"Info part 1 <br> First box stage requires 20,000 code <br> 2: 2,000,000 code <br> 3: 400,000,000 code <br> 4: 100,000,000,000 <br> 5: 50,000,000,000,000 <br> 6: 10 peta"
	-named  
	-unlocks noEffect
	-picture : http://i.imgur.com/TkCSZup.png
	*goldenBoxInfo2
	-"Info part 2 <br> 7: 10 exa code <br> 8: 20 zetta code <br> 9: 50 yotta <br> 10: 10 xatta (octillion) <br> 11: 200 xatta (octillion) <br> 12: 3 vitta (nonillion)"
	-named  
	-unlocks noEffect
	-picture : http://i.imgur.com/TkCSZup.png
	*goldenBoxInfo3
	-"Info part 3 <br> The reward: [REDACTED]"
	-named  
	-unlocks noEffect
	-picture : http://i.imgur.com/TkCSZup.png
	*researchUnlock
	-"Unlocks the research lab. <br><i>Let's do some serious research, and discover new things!</i>
	-costs 1 code
	-named Research
	-unlocks research
	-unlocks at 1 popularity
	-picture : http://i.imgur.com/GS3JNtZ.png
	*researchUnlock2
	-"Unlocks the magic research lab. <br><i>We can do some research on magic, unlocking new things for our magic code writers.</i>
	-costs 1 code
	-named Magic Research
	-unlocks research2
	-unlocks at 2 popularity
	-picture : http://i.imgur.com/rpoCJIB.png
	*magicResearch1
	-"Unlocks the magic research clickable.<br><i></i>
	-costs 101 code
	-unlocks speedResearch2
	-unlocks at 1000 researchTime2
	-named Magic Research Speed Up
	-picture : http://i.imgur.com/rpoCJIB.png
	*magicResearch2
	-"Everything is <b>10%</b> more efficient.<br><i>Just magically enhance everything, it'll boost everything.</i>
	-costs 10101 code
	-unlocks at 2000 researchTime2
	-multiplies efficiency of writeCode by 110%
	-multiplies efficiency of codeWriter by 110%
	-multiplies efficiency of object by 110%
	-multiplies efficiency of enemy by 110%
	-multiplies efficiency of player by 110%
	-multiplies efficiency of level by 110%
	-multiplies efficiency of game by 110%
	-multiplies efficiency of fanbase by 110%
	-multiplies efficiency of forum by 110%
	-multiplies efficiency of advertise by 110%
	-multiplies efficiency of studio by 110%
	-multiplies efficiency of magic by 110%
	-multiplies efficiency of gameSeries by 110%
	-multiplies efficiency of popularYoutuber by 110%
	-multiplies efficiency of gameProducer by 110%
	-multiplies efficiency of highReviewer by 110%
	-multiplies efficiency of maganiumGenerator by 110%
	-multiplies efficiency of finality by 110%
	-multiplies efficiency of magicPointBuilding by 110%
	-picture : http://i.imgur.com/Sj4Afd4.png
	-named General Magic Enhancements
	*magicResearch3
	-"Manual code writing is <b>50%</b> more efficient.<br><i>After the wizards magically enhanced you, you can now spawn lots of code in.</i>
	-costs 10101010 code
	-unlocks at 4000 researchTime2
	-named Code Spawning
	-multiplies efficiency of writeCode by 150%
	-picture : http://i.imgur.com/Rf46N72.png
	*magicResearch4
	-"Games are <b>50%</b> more efficient.<br><i>The games are now magic, making them run a lot faster, and be able to handle a lot more before lagging.</i>
	-costs 10101010101 code
	-unlocks at 10000 researchTime2
	-multiplies efficiency of game by 150%
	-named Magic Games
	-picture : http://i.imgur.com/H2i3l2P.png
	*magicResearch5
	-"Studios are <b>50%</b> more efficient.<br><i>Just build studios out of magic. That way, things will be a lot faster, studios can't be damaged, and Developer Bakanium can't enter the studios. Usually.</i>
	-costs 10101010101010 code
	-multiplies efficiency of studio by 150%
	-unlocks at 30000 researchTime2
	-named Studios built with Magic
	-picture : http://i.imgur.com/OENk6zH.png
	*magicResearch6
	-"Everything is <b>10%</b> more efficient.<br><i>The code itself now replicates every so often, resulting in getting more code.</i>
	-costs 10101010101010101 code
	-unlocks at 80000 researchTime2
	-multiplies efficiency of writeCode by 110%
	-multiplies efficiency of codeWriter by 110%
	-multiplies efficiency of object by 110%
	-multiplies efficiency of enemy by 110%
	-multiplies efficiency of player by 110%
	-multiplies efficiency of level by 110%
	-multiplies efficiency of game by 110%
	-multiplies efficiency of fanbase by 110%
	-multiplies efficiency of forum by 110%
	-multiplies efficiency of advertise by 110%
	-multiplies efficiency of studio by 110%
	-multiplies efficiency of magic by 110%
	-multiplies efficiency of gameSeries by 110%
	-multiplies efficiency of popularYoutuber by 110%
	-multiplies efficiency of gameProducer by 110%
	-multiplies efficiency of highReviewer by 110%
	-multiplies efficiency of maganiumGenerator by 110%
	-multiplies efficiency of finality by 110%
	-multiplies efficiency of magicPointBuilding by 110%
	-named Replicating Code
	-picture : http://i.imgur.com/OW9dF4j.png
	*magicResearch7
	-"Fanbases are <b>twice</b> as efficient.<br><i>Turns out friendship IS magic! The friendship creates lots of magic that boosts things, and massively boosts your fanbases.<br><br>"FINALLY!!1!!!11111!!!!!11" ~Developer Mlepfim</i>
	-costs 10101010101010101010 code
	-multiplies efficiency of fanbase by 200%
	-unlocks at 250000 researchTime2
	-named Magic Friendship
	-picture : http://i.imgur.com/Mhm7bpB.png
	*magicResearch8
	-"Magic code writers are <b>twice</b> as efficient.<br><i>Near some odd stones, we found these scrolls that enhance magic code writers greatly.</i>
	-costs 10101010101010101010101 code
	-unlocks at 500000 researchTime2
	-multiplies efficiency of magic by 200%
	-named Wizard Scrolls
	-picture : http://i.imgur.com/GBMi33j.png
	*magicResearch9
	-"Everything is <b>0.1%</b> more efficient for every day you play.<br><i></i>
	-costs 10101010101010101010101010 code
	-unlocks at 1000000 researchTime2
	-multiplies efficiency of writeCode by 0.00000115740740740740% per time
	-multiplies efficiency of codeWriter by 0.00000115740740740740% per time
	-multiplies efficiency of object by 0.00000115740740740740% per time
	-multiplies efficiency of enemy by 0.00000115740740740740% per time
	-multiplies efficiency of player by 0.00000115740740740740% per time
	-multiplies efficiency of level by 0.00000115740740740740% per time
	-multiplies efficiency of game by 0.00000115740740740740% per time
	-multiplies efficiency of fanbase by 0.00000115740740740740% per time
	-multiplies efficiency of forum by 0.00000115740740740740% per time
	-multiplies efficiency of advertise by 0.00000115740740740740% per time
	-multiplies efficiency of highReviewer by 0.00000115740740740740% per time
	-multiplies efficiency of studio by 0.00000115740740740740% per time
	-multiplies efficiency of magic by 0.00000115740740740740% per time
	-multiplies efficiency of gameSeries by 0.00000115740740740740% per time
	-multiplies efficiency of popularYoutuber by 0.00000115740740740740% per time
	-multiplies efficiency of maganiumGenerator by 0.00000115740740740740% per time
	-multiplies efficiency of finality by 0.00000115740740740740% per time
	-multiplies efficiency of magicPointBuilding by 0.00000115740740740740% per time
	-named Magic Improvements
	-picture : http://i.imgur.com/O407PP3.png
	*researchUnlock3
	-"Unlocks the ultra-magic research lab. <br><i>If we try, we can research ultra-magic, a very strong form of magic.</i>
	-costs 10 code
	-named Ultra-magic Research
	-unlocks research3
	-unlocks at 5 popularity
	-picture : http://i.imgur.com/HM1foRb.png
	*maganiumResearch1
	-"Unlocks the ultra-magic research clickable.<br><i></i>
	-costs 1010 code
	-unlocks speedResearch3
	-unlocks at 1000 researchTime3
	-named Ultra-magic Research Speed Up
	-picture : http://i.imgur.com/HM1foRb.png
	*maganiumResearch2
	-"Everything is <b>15%</b> more efficient.<br><i>Ultra-magic enhancements are a bit like magic enhancements, but way more powerful.</i>
	-costs 1010101 code
	-multiplies efficiency of writeCode by 115%
	-multiplies efficiency of codeWriter by 115%
	-multiplies efficiency of object by 115%
	-multiplies efficiency of enemy by 115%
	-multiplies efficiency of player by 115%
	-multiplies efficiency of level by 115%
	-multiplies efficiency of game by 115%
	-multiplies efficiency of fanbase by 115%
	-multiplies efficiency of forum by 115%
	-multiplies efficiency of advertise by 115%
	-multiplies efficiency of studio by 115%
	-multiplies efficiency of magic by 115%
	-multiplies efficiency of gameSeries by 115%
	-multiplies efficiency of popularYoutuber by 115%
	-multiplies efficiency of gameProducer by 115%
	-multiplies efficiency of highReviewer by 115%
	-multiplies efficiency of maganiumGenerator by 115%
	-multiplies efficiency of finality by 115%
	-multiplies efficiency of magicPointBuilding by 115%
	-unlocks at 3000 researchTime3
	-named Ultra-magic enhancements
	-picture : http://i.imgur.com/sgTAmiD.png
	*maganiumResearch3
	-"Levels are <b>50%</b> more efficient.<br><i>Introducing ultra-magic into levels opens up more possibilities and makes them more enjoyable.</i>
	-costs 1010101010 code
	-multiplies efficiency of level by 150%
	-unlocks at 10000 researchTime3
	-named Levels with ultra-magic
	-picture : http://i.imgur.com/8q8kmmy.png
	*maganiumResearch4
	-"Magic code writers and ultra-magic generators are <b>50%</b> more efficient.<br><i>The magic code writers are getting code from the ultra-magic generators, and enhancing them so the ultra-magic can manipulate space. The magic code writers cast spells that turn things into code, and enhance the ultra-magic generators so they can convert and turn things into code as well.</i>
	-costs 1010101010101 code
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-unlocks at 30000 researchTime3
	-named Space Manipulation
	-picture : http://i.imgur.com/pS7oqsG.png
	*maganiumResearch5
	-"Players are <b>50%</b> more efficient, and code writers are <b>10%</b> more efficient.<br><i>The code writing players are doing well. Let's enhance them with ultra-magic, and then they become even more powerful!</i>
	-costs 1010101010101010 code
	-multiplies efficiency of codeWriter by 110%
	-multiplies efficiency of player by 150%
	-unlocks at 80000 researchTime3
	-named Ultra-magic code-writing players
	-picture : http://i.imgur.com/ituCX6V.png
	*maganiumResearch6
	-"Research is <b>20%</b> faster. Everything is <b>2%</b> more efficient.<br><i>Our ultra-magic is so powerful, we can alter time with it, and make it faster.</i>
	-costs 1010101010101010 code
	-multiplies efficiency of research by 120%
	-multiplies efficiency of research2 by 120%
	-multiplies efficiency of research3 by 120%
	-multiplies efficiency of research4 by 120%
	-multiplies efficiency of speedResearch by 120%
	-multiplies efficiency of speedResearch2 by 120%
	-multiplies efficiency of speedResearch3 by 120%
	-multiplies efficiency of speedResearch4 by 120%
	-multiplies efficiency of writeCode by 102%
	-multiplies efficiency of codeWriter by 102%
	-multiplies efficiency of object by 102%
	-multiplies efficiency of enemy by 102%
	-multiplies efficiency of player by 102%
	-multiplies efficiency of level by 102%
	-multiplies efficiency of game by 102%
	-multiplies efficiency of fanbase by 102%
	-multiplies efficiency of forum by 102%
	-multiplies efficiency of advertise by 102%
	-multiplies efficiency of studio by 102%
	-multiplies efficiency of magic by 102%
	-multiplies efficiency of gameSeries by 102%
	-multiplies efficiency of popularYoutuber by 102%
	-multiplies efficiency of gameProducer by 102%
	-multiplies efficiency of highReviewer by 102%
	-multiplies efficiency of maganiumGenerator by 102%
	-multiplies efficiency of finality by 102%
	-multiplies efficiency of magicPointBuilding by 102%
	-unlocks at 250000 researchTime3
	-named Time altering
	-picture : http://i.imgur.com/UKVssdn.png
	*maganiumResearch7
	-"Games and game series are <b>50%</b> more efficient. Game producers are <b>4 times</b> more efficient.<br><i>The games are now replicating themselves, which means more games, which gives a great boost to game-related things!</i>
	-costs 10101010101010101010 code
	-multiplies efficiency of game by 150%
	-multiplies efficiency of gameSeries by 150%
	-multiplies efficiency of gameProducer by 400%
	-unlocks at 500000 researchTime3
	-named Replicating games
	-picture : http://i.imgur.com/wERNP49.png
	*maganiumResearch8
	-"Everything is <b>10%</b> more efficient.<br><i>After combining enough ultra-magic, we are getting stronger ultra-magic, which, when used to enhance things, boosts them further.</i>
	-costs 101010101010101010101010 code
	-multiplies efficiency of writeCode by 110%
	-multiplies efficiency of codeWriter by 110%
	-multiplies efficiency of object by 110%
	-multiplies efficiency of enemy by 110%
	-multiplies efficiency of player by 110%
	-multiplies efficiency of level by 110%
	-multiplies efficiency of game by 110%
	-multiplies efficiency of fanbase by 110%
	-multiplies efficiency of forum by 110%
	-multiplies efficiency of advertise by 110%
	-multiplies efficiency of studio by 110%
	-multiplies efficiency of magic by 110%
	-multiplies efficiency of gameSeries by 110%
	-multiplies efficiency of popularYoutuber by 110%
	-multiplies efficiency of gameProducer by 110%
	-multiplies efficiency of highReviewer by 110%
	-multiplies efficiency of maganiumGenerator by 110%
	-multiplies efficiency of finality by 110%
	-multiplies efficiency of magicPointBuilding by 110%
	-unlocks at 1000000 researchTime3
	-named Ultra-magic strengthening
	-picture : http://i.imgur.com/7lDlaiA.png
	*researchUnlock4
	-"Unlocks the secret organisation building. <br><i>To help our secret organisation excel, we need a special building that no one that isn't in our organisation can enter.</i>
	-costs 101 code
	-named Secret Organisation
	-unlocks research4
	-unlocks at 10 popularity
	-picture : http://i.imgur.com/yrhwmAg.png
	*finalityResearch1
	-"Unlocks the finality research clickable.<br><i></i>
	-costs 10101 code
	-unlocks speedResearch4
	-unlocks at 1000 researchTime4
	-named Finality Research Speed Up
	-picture : http://i.imgur.com/yrhwmAg.png
	*finalityResearch2
	-"Everything is <b>20%</b> more efficient.<br><i>The power of the Finality is immense. Should we use this power to power up our other stuff, we will dominate the world sooner!</i>
	-costs 10101010 code
	-multiplies efficiency of writeCode by 120%
	-multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of object by 120%
	-multiplies efficiency of enemy by 120%
	-multiplies efficiency of player by 120%
	-multiplies efficiency of level by 120%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of studio by 120%
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of gameSeries by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-multiplies efficiency of gameProducer by 120%
	-multiplies efficiency of highReviewer by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-multiplies efficiency of finality by 120%
	-multiplies efficiency of magicPointBuilding by 120%
	-unlocks at 4000 researchTime4
	-named Finality Enhancements
	-picture : http://i.imgur.com/WaZILM4.png
	*finalityResearch3
	-"Objects are <b>50%</b> more efficient.<br><i>Our objects are becoming the best in the world. Soon, the other objects will start to fade away.</i>
	-costs 101010101010 code
	-multiplies efficiency of object by 150%
	-unlocks at 15000 researchTime4
	-named #1 objects
	-picture : http://i.imgur.com/jdcyBiS.png
	*finalityResearch4
	-"Players are <b>25%</b> more efficient. Code writers are <b>10%</b> more efficient.<br><i>We got the code-writing player to take part in The Finality. They're doing a good job.</i>
	-costs 1010101010101010 code
	-multiplies efficiency of codeWriter by 110%
	-multiplies efficiency of player by 125%
	-unlocks at 75000 researchTime4
	-named The Finality's code-writing players
	-picture : http://i.imgur.com/wpFs16P.png
	*finalityResearch5
	-"Fanbases, forums, and popular YouTubers are all <b>20%</b> more efficient.<br><i>As the Finality grows, it starts to take over the internet slowly.</i>
	-costs 10101010101010101010 code
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-unlocks at 200000 researchTime4
	-named Internet Domination
	-picture : http://i.imgur.com/TooFtLq.png
	*finalityResearch6
	-"Studios are <b>50%</b> more efficient.<br><i>Our studios are starting to drive other studios into bankruptcy. Soon, our studios will be the only ones left.</i>
	-costs 101010101010101010101010 code
	-multiplies efficiency of studio by 150%
	-unlocks at 500000 researchTime4
	-named Studio Wipeout
	-picture : http://i.imgur.com/bltisLT.png
	*finalityResearch7
	-"Everything is <b>0.1%</b> more efficient for every day you play.<br><i>As time goes by, the Finality starts to take over the world. The other game series are being wiped out. Major game companies are starting to decline, and your games will be the sole survivors</i>
	-costs 1010101010101010101010101010 code
	-multiplies efficiency of writeCode by 0.00000115740740740740% per time
	-multiplies efficiency of codeWriter by 0.00000115740740740740% per time
	-multiplies efficiency of object by 0.00000115740740740740% per time
	-multiplies efficiency of enemy by 0.00000115740740740740% per time
	-multiplies efficiency of player by 0.00000115740740740740% per time
	-multiplies efficiency of level by 0.00000115740740740740% per time
	-multiplies efficiency of game by 0.00000115740740740740% per time
	-multiplies efficiency of fanbase by 0.00000115740740740740% per time
	-multiplies efficiency of forum by 0.00000115740740740740% per time
	-multiplies efficiency of advertise by 0.00000115740740740740% per time
	-multiplies efficiency of highReviewer by 0.00000115740740740740% per time
	-multiplies efficiency of studio by 0.00000115740740740740% per time
	-multiplies efficiency of magic by 0.00000115740740740740% per time
	-multiplies efficiency of gameSeries by 0.00000115740740740740% per time
	-multiplies efficiency of popularYoutuber by 0.00000115740740740740% per time
	-multiplies efficiency of maganiumGenerator by 0.00000115740740740740% per time
	-multiplies efficiency of finality by 0.00000115740740740740% per time
	-multiplies efficiency of magicPointBuilding by 0.00000115740740740740% per time
	-unlocks at 1000000 researchTime4
	-named Gradual world domination
	-picture : http://i.imgur.com/iIneAoB.png
	*youtubeUnlock
	-"Unlocks Popular YouTubers.<br><i> The popularity has spread to a few well known YouTubers with tens of thousands of subscribers.</i>
	-costs 10000000 positiveReview
	-unlocks popularYoutuber
	-named Popular YouTubers
	-unlocks at 7 popularity
	-picture : http://i.imgur.com/FFxM1vH.png
	*stoneUnlock1
	-"Unlock the Stone of Time.<br><i> </i>
	-costs 1e+33 code
	-unlocks stone1
	-unlocks at 1 overtake20
	-named Time Stones
	-multiplies efficiency of writeCode by 0.2% per stone1
	-multiplies efficiency of codeWriter by 0.2% per stone1
	-multiplies efficiency of object by 0.2% per stone1
	-multiplies efficiency of enemy by 0.2% per stone1
	-multiplies efficiency of player by 0.2% per stone1
	-multiplies efficiency of level by 0.2% per stone1
	-multiplies efficiency of game by 0.2% per stone1
	-multiplies efficiency of fanbase by 0.2% per stone1
	-multiplies efficiency of forum by 0.2% per stone1
	-multiplies efficiency of advertise by 0.2% per stone1
	-multiplies efficiency of studio by 0.2% per stone1
	-multiplies efficiency of magic by 0.2% per stone1
	-multiplies efficiency of gameSeries by 0.2% per stone1
	-multiplies efficiency of popularYoutuber by 0.2% per stone1
	-multiplies efficiency of gameProducer by 0.2% per stone1
	-multiplies efficiency of highReviewer by 0.2% per stone1
	-multiplies efficiency of maganiumGenerator by 0.2% per stone1
	-multiplies efficiency of finality by 0.2% per stone1
	-multiplies efficiency of magicPointBuilding by 0.2% per stone1
	-picture : http://i.imgur.com/GZ0HvtW.png
	*stoneUnlock2
	-"Unlock the Stone of Space.<br><i> </i>
	-costs 1e+53 code
	-unlocks stone2
	-unlocks at 1 overtake40
	-multiplies efficiency of writeCode by 0.4% per stone2
	-multiplies efficiency of codeWriter by 0.4% per stone2
	-multiplies efficiency of object by 0.4% per stone2
	-multiplies efficiency of enemy by 0.4% per stone2
	-multiplies efficiency of player by 0.4% per stone2
	-multiplies efficiency of level by 0.4% per stone2
	-multiplies efficiency of game by 0.4% per stone2
	-multiplies efficiency of fanbase by 0.4% per stone2
	-multiplies efficiency of forum by 0.4% per stone2
	-multiplies efficiency of advertise by 0.4% per stone2
	-multiplies efficiency of studio by 0.4% per stone2
	-multiplies efficiency of magic by 0.4% per stone2
	-multiplies efficiency of gameSeries by 0.4% per stone2
	-multiplies efficiency of popularYoutuber by 0.4% per stone2
	-multiplies efficiency of gameProducer by 0.4% per stone2
	-multiplies efficiency of highReviewer by 0.4% per stone2
	-multiplies efficiency of maganiumGenerator by 0.4% per stone2
	-multiplies efficiency of finality by 0.4% per stone2
	-multiplies efficiency of magicPointBuilding by 0.4% per stone2
	-named Space Stones
	-picture : http://i.imgur.com/16ROFu4.png
	*stoneUnlock3
	-"Unlock the Synergy Stone.<br><i> </i>
	-costs 1e+73 code
	-unlocks stone3
	-unlocks at 1 overtake60
	-multiplies efficiency of writeCode by 1% per stone3
	-multiplies efficiency of codeWriter by 1% per stone3
	-multiplies efficiency of object by 1% per stone3
	-multiplies efficiency of enemy by 1% per stone3
	-multiplies efficiency of player by 1% per stone3
	-multiplies efficiency of level by 1% per stone3
	-multiplies efficiency of game by 1% per stone3
	-multiplies efficiency of fanbase by 1% per stone3
	-multiplies efficiency of forum by 1% per stone3
	-multiplies efficiency of advertise by 1% per stone3
	-multiplies efficiency of studio by 1% per stone3
	-multiplies efficiency of magic by 1% per stone3
	-multiplies efficiency of gameSeries by 1% per stone3
	-multiplies efficiency of popularYoutuber by 1% per stone3
	-multiplies efficiency of gameProducer by 1% per stone3
	-multiplies efficiency of highReviewer by 1% per stone3
	-multiplies efficiency of maganiumGenerator by 1% per stone3
	-multiplies efficiency of finality by 1% per stone3
	-multiplies efficiency of magicPointBuilding by 1% per stone3
	-picture : http://i.imgur.com/c8FCuLQ.png
	*stoneUnlock4
	-"Unlock the Mystery Stone.<br><i> </i>
	-costs 1e+93 code
	-unlocks stone4
	-unlocks at 1 overtake70
	-multiplies efficiency of writeCode by 0.25% per stoneBuilding
	-multiplies efficiency of codeWriter by  0.25% per stoneBuilding
	-multiplies efficiency of object by  0.25% per stoneBuilding
	-multiplies efficiency of enemy by  0.25% per stoneBuilding
	-multiplies efficiency of player by  0.25% per stoneBuilding
	-multiplies efficiency of level by  0.25% per stoneBuilding
	-multiplies efficiency of game by  0.25% per stoneBuilding
	-multiplies efficiency of fanbase by  0.25% per stoneBuilding
	-multiplies efficiency of forum by  0.25% per stoneBuilding
	-multiplies efficiency of advertise by  0.25% per stoneBuilding
	-multiplies efficiency of studio by  0.25% per stoneBuilding
	-multiplies efficiency of magic by  0.25% per stoneBuilding
	-multiplies efficiency of gameSeries by  0.25% per stoneBuilding
	-multiplies efficiency of popularYoutuber by  0.25% per stoneBuilding
	-multiplies efficiency of gameProducer by  0.25% per stoneBuilding
	-multiplies efficiency of highReviewer by  0.25% per stoneBuilding
	-multiplies efficiency of maganiumGenerator by  0.25% per stoneBuilding
	-multiplies efficiency of finality by  0.25% per stoneBuilding
	-multiplies efficiency of magicPointBuilding by  0.25% per stoneBuilding
	-picture : http://i.imgur.com/c8FCuLQ.png
	*allTimeUpgrade1
	-"Manual code writing is twice as efficient. <br><i>Some basic lessons on coding.</i>
	-costs 100 code
	-named Beginner coding lessons
	-unlocks at 1 totalCode
	-multiplies efficiency of writeCode by 200%
	-picture : http://i.imgur.com/GsOKd4T.png
	*allTimeUpgrade2
	-"Code writers are 0.1% more efficient for each code writer. <br><i>Our writers now know binary code.</i>
	-costs 2000 code
	-named Binary coding
	-unlocks at 150 totalCode
	-multiplies efficiency of codeWriter by 0.1% per codeWriter
	-picture : http://i.imgur.com/jg25zTJ.png
	*allTimeUpgrade3
	-"The first five buildings are twice as efficient. <br><i>We've just started, let's give ourselves a bit of a boost. </i>
	-costs 16000 code
	-named Early boost
	-unlocks at 800 totalCode
	-multiplies efficiency of codeWriter by 200%
	-multiplies efficiency of object by 200%
	-multiplies efficiency of enemy by 200%
	-multiplies efficiency of player by 200%
	-multiplies efficiency of level by 200%
	-picture : http://i.imgur.com/78PdK8q.png
	*allTimeUpgrade4
	-"Code writers write more code the longer you have played. <br><i>As time passes, our code writers slowly become more experienced.</i>
	-costs 60000 code
	-named Coding experience gaining
	-unlocks at 10000 totalCode
	-multiplies efficiency of codeWriter by 0.00001% per time
	-picture : http://i.imgur.com/MJ1j8uo.png
	*allTimeUpgrade5
	-"Everything up to game studios is 50% more efficient. <br><i>Let's hire all the good guys and not the ones that keep saying ''pls make fps game pls''</i>
	-costs 1000000 code
	-named Better hiring
	-unlocks at 150000 totalCode
	-multiplies efficiency of codeWriter by 150%
	-multiplies efficiency of object by 150%
	-multiplies efficiency of enemy by 150%
	-multiplies efficiency of player by 150%
	-multiplies efficiency of level by 150%
	-multiplies efficiency of game by 150%
	-multiplies efficiency of fanbase by 150%
	-multiplies efficiency of forum by 150%
	-multiplies efficiency of advertise by 150%
	-multiplies efficiency of highReviewer by 150%
	-multiplies efficiency of studio by 150%
	-picture : http://i.imgur.com/Nis3qlm.png
	*allTimeUpgrade6
	-"Manual code writing is twice as efficient. <br><i>The advanced coding lessons allow you to write code really fast, and without errors!</i>
	-costs 50000000 code
	-named Expert coding lessons
	-unlocks at 5000000 totalCode
	-multiplies efficiency of writeCode by 200%
	-picture : http://i.imgur.com/SJaSIJa.png
	*allTimeUpgrade7
	-"Everything is 20% more efficient. <br><i>Let's give ourselves a morale boost, and we will rise to the top quicker!</i>
	-costs 1000000000 code
	-named Morale Boost
	-unlocks at 100000000 totalCode
	-multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of object by 120%
	-multiplies efficiency of enemy by 120%
	-multiplies efficiency of player by 120%
	-multiplies efficiency of level by 120%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of highReviewer by 120%
	-multiplies efficiency of studio by 120%
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of gameSeries by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-multiplies efficiency of finality by 120%
	-multiplies efficiency of magicPointBuilding by 120%
	-picture : http://i.imgur.com/JpJVYph.png
	*allTimeUpgrade8
	-"Everything is more efficient the longer you play. <br><i>Some of the oldest coding on the planet.</i>
	-costs 100000000000 code
	-named Century Code
	-unlocks at 10000000000 totalCode
	-multiplies efficiency of writeCode by 0.000005% per time
	-multiplies efficiency of codeWriter by 0.000005% per time
	-multiplies efficiency of object by 0.000005% per time
	-multiplies efficiency of enemy by 0.000005% per time
	-multiplies efficiency of player by 0.000005% per time
	-multiplies efficiency of level by 0.000004% per time
	-multiplies efficiency of game by 0.000004% per time
	-multiplies efficiency of fanbase by 0.000004% per time
	-multiplies efficiency of forum by 0.000004% per time
	-multiplies efficiency of advertise by 0.000003% per time
	-multiplies efficiency of highReviewer by 0.000003% per time
	-multiplies efficiency of studio by 0.000003% per time
	-multiplies efficiency of magic by 0.000003% per time
	-multiplies efficiency of gameSeries by 0.000003% per time
	-multiplies efficiency of popularYoutuber by 0.000003% per time
	-multiplies efficiency of maganiumGenerator by 0.000003% per time
	-multiplies efficiency of finality by 0.000002% per time
	-multiplies efficiency of magicPointBuilding by 0.000005% per time
	-picture : http://i.imgur.com/NJUk4tU.png
	*allTimeUpgrade9
	-"Manual code writing is four times as efficient. <br><i>Magically enhances your fingers, allowing you to write at super speed!</i>
	-costs 1500000000000 code
	-named Magic hands
	-unlocks at 150000000000 totalCode
	-multiplies efficiency of writeCode by 400%
	-picture : http://i.imgur.com/QE98zMD.png
	*allTimeUpgrade10
	-"Unlocks positive reviewers. <br><i>They give you positive reviews frequently.</i>
	-costs 20000000000000 code
	-named High review score givers
	-unlocks at 2000000000000 totalCode
	-unlocks highReviewer
	-picture : http://i.imgur.com/jfLf6WV.png
	*allTimeUpgrade11
	-"Manual code writing is more efficient for each game series overtaken. <br><i>Now that we have succeeded in becoming a major game company, code writing is a lot more efficient because the morale boost.</i>
	-costs 2000000000000 code
	-named The Success
	-unlocks at 2 popularity
	-multiplies efficiency of writeCode by 50% per popularity
	-picture : http://i.imgur.com/oObczjC.png
	*allTimeUpgrade12
	-"Everything is 20% more efficient. <br><i>Your game company somehow becomes awesome, boosting everything.</i>
	-costs 200000000000000 code
	-named Awesomeness
	-unlocks at 4 popularity
	-multiplies efficiency of writeCode by 120%
	-multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of object by 120%
	-multiplies efficiency of enemy by 120%
	-multiplies efficiency of player by 120%
	-multiplies efficiency of level by 120%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of highReviewer by 120%
	-multiplies efficiency of studio by 120%
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of gameSeries by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-multiplies efficiency of finality by 120%
	-multiplies efficiency of magicPointBuilding by 120%
	-picture : http://i.imgur.com/Nf7rkFa.png
	*allTimeUpgrade13
	-"Manual coding is 0.1% more effective for each building. <br><i>You now receive manual coding help from EVERYTHING!</i>
	-costs 20000000000000000 code
	-named Ultimate Click Boost
	-unlocks at 7 popularity
	-multiplies efficiency of writeCode by 0.1% per buildings
	-picture : http://i.imgur.com/kgXxI10.png
	*allTimeUpgrade14
	-"Everything is 20% more efficient. <br><i>We finally found them!</i>
	-costs 200000000000000000 code
	-named The Best Coders
	-unlocks at 9 popularity
	-multiplies efficiency of writeCode by 120%
	-multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of object by 120%
	-multiplies efficiency of enemy by 120%
	-multiplies efficiency of player by 120%
	-multiplies efficiency of level by 120%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of highReviewer by 120%
	-multiplies efficiency of studio by 120%
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of gameSeries by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-multiplies efficiency of finality by 120%
	-multiplies efficiency of magicPointBuilding by 120%
	-picture : http://i.imgur.com/vfwJN5V.png
	*allTimeUpgrade15
	-"Everything is 50% more efficient. <br><i>With our world domination, we somehow found this code in space. Let's use it!</i>
	-costs 2000000000000000000 code
	-named The Ultimate Code
	-unlocks at 10 popularity
	-multiplies efficiency of writeCode by 150%
	-multiplies efficiency of codeWriter by 150%
	-multiplies efficiency of object by 150%
	-multiplies efficiency of enemy by 150%
	-multiplies efficiency of player by 150%
	-multiplies efficiency of level by 150%
	-multiplies efficiency of game by 150%
	-multiplies efficiency of fanbase by 150%
	-multiplies efficiency of forum by 150%
	-multiplies efficiency of advertise by 150%
	-multiplies efficiency of highReviewer by 150%
	-multiplies efficiency of studio by 150%
	-multiplies efficiency of magic by 150%
	-multiplies efficiency of gameSeries by 150%
	-multiplies efficiency of popularYoutuber by 150%
	-multiplies efficiency of maganiumGenerator by 150%
	-multiplies efficiency of finality by 150%
	-multiplies efficiency of magicPointBuilding by 150%
	-picture : http://i.imgur.com/yXYKOiS.png

	*bogusUpgrade1
	-"Everything is 10% more efficient, except advertisments, which are 50% more efficient. <br><i>We could have done this earlier, but, oh well.</i>
	-costs 1e+22 code
	-multiplies efficiency of writeCode by 110%
	-multiplies efficiency of codeWriter by 110%
	-multiplies efficiency of object by 110%
	-multiplies efficiency of enemy by 110%
	-multiplies efficiency of player by 110%
	-multiplies efficiency of level by 110%
	-multiplies efficiency of game by 110%
	-multiplies efficiency of fanbase by 110%
	-multiplies efficiency of forum by 110%
	-multiplies efficiency of advertise by 150%
	-multiplies efficiency of studio by 110%
	-multiplies efficiency of magic by 110%
	-multiplies efficiency of gameSeries by 110%
	-multiplies efficiency of popularYoutuber by 110%
	-multiplies efficiency of gameProducer by 110%
	-multiplies efficiency of highReviewer by 110%
	-multiplies efficiency of maganiumGenerator by 110%
	-multiplies efficiency of finality by 110%
	-multiplies efficiency of magicPointBuilding by 110%
	-named Merchandise
	-unlocks at 11 popularity
	-picture : http://i.imgur.com/JB8yyFG.png
	*bogusUpgrade2
	-"Unlocks bread. Everything is 4% more efficient for each bread you own. <br><i>Because the meaning of life is bread.<br><br>"I approve the this upgrade and its description." ~Developer Tofusaturn</i>
	-costs 1e+23 code
	-unlocks theBread
	-multiplies efficiency of writeCode by 4% per theBread
	-multiplies efficiency of codeWriter by 4% per theBread
	-multiplies efficiency of object by 4% per theBread
	-multiplies efficiency of enemy by 4% per theBread
	-multiplies efficiency of player by 4% per theBread
	-multiplies efficiency of level by 4% per theBread
	-multiplies efficiency of game by 4% per theBread
	-multiplies efficiency of fanbase by 4% per theBread
	-multiplies efficiency of forum by 4% per theBread
	-multiplies efficiency of advertise by 4% per theBread
	-multiplies efficiency of studio by 4% per theBread
	-multiplies efficiency of magic by 4% per theBread
	-multiplies efficiency of gameSeries by 4% per theBread
	-multiplies efficiency of popularYoutuber by 4% per theBread
	-multiplies efficiency of gameProducer by 4% per theBread
	-multiplies efficiency of highReviewer by 4% per theBread
	-multiplies efficiency of maganiumGenerator by 4% per theBread
	-multiplies efficiency of finality by 4% per theBread
	-multiplies efficiency of magicPointBuilding by 4% per theBread
	-named The Bread
	-unlocks at 12 popularity
	-picture : http://i.imgur.com/7I4066V.png
	*bogusUpgrade3
	-"Objects, enemies, players and levels all produce four times as much code. <br><i>Never again will we run out of ideas.</i>
	-costs 1e+24 code
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-named Infinite Ideas
	-unlocks at 13 popularity
	-picture : http://i.imgur.com/M3VrV2C.png
	*bogusUpgrade4
	-costs 1e+25 code
	-"Everything is 10% more efficient, except advertisements and magic code writers, which are 50% more efficient. <br><i>Magic merchandise seems to be going well.</i>
	-multiplies efficiency of writeCode by 110%
	-multiplies efficiency of codeWriter by 110%
	-multiplies efficiency of object by 110%
	-multiplies efficiency of enemy by 110%
	-multiplies efficiency of player by 110%
	-multiplies efficiency of level by 110%
	-multiplies efficiency of game by 110%
	-multiplies efficiency of fanbase by 110%
	-multiplies efficiency of forum by 110%
	-multiplies efficiency of advertise by 150%
	-multiplies efficiency of studio by 110%
	-multiplies efficiency of magic by 150%
	-multiplies efficiency of gameSeries by 110%
	-multiplies efficiency of popularYoutuber by 110%
	-multiplies efficiency of gameProducer by 110%
	-multiplies efficiency of highReviewer by 110%
	-multiplies efficiency of maganiumGenerator by 110%
	-multiplies efficiency of finality by 110%
	-multiplies efficiency of magicPointBuilding by 110%
	-named Magic Merchandise
	-unlocks at 14 popularity
	-picture : http://i.imgur.com/VEMpFzC.png
	*bogusUpgrade5
	-"Code writers, manual code writing, studios, magic code writers, and finalities are twice as efficient. <br><i>Tastes like code. The taste is oddly addictive, and they boost our people.</i>
	-costs 1e+26 code
	-multiplies efficiency of writeCode by 200%
	-multiplies efficiency of codeWriter by 200%
	-multiplies efficiency of studio by 200%
	-multiplies efficiency of magic by 200%
	-multiplies efficiency of finality by 200%
	-named Code Burgers
	-unlocks at 15 popularity
	-picture : http://i.imgur.com/8waqqbz.png
	*bogusUpgrade6
	-"Everything is 15% more efficient.  <br><i>We found this stuff in a dungeon. We don't know what it is, but it's useful!</i>
	-costs 1e+27 code
	-named The Unknown
	-multiplies efficiency of writeCode by 115%
	-multiplies efficiency of codeWriter by 115%
	-multiplies efficiency of object by 115%
	-multiplies efficiency of enemy by 115%
	-multiplies efficiency of player by 115%
	-multiplies efficiency of level by 115%
	-multiplies efficiency of game by 115%
	-multiplies efficiency of fanbase by 115%
	-multiplies efficiency of forum by 115%
	-multiplies efficiency of advertise by 115%
	-multiplies efficiency of studio by 115%
	-multiplies efficiency of magic by 115%
	-multiplies efficiency of gameSeries by 115%
	-multiplies efficiency of popularYoutuber by 115%
	-multiplies efficiency of gameProducer by 115%
	-multiplies efficiency of highReviewer by 115%
	-multiplies efficiency of maganiumGenerator by 115%
	-multiplies efficiency of finality by 115%
	-multiplies efficiency of magicPointBuilding by 115%
	-unlocks at 16 popularity
	-picture : http://i.imgur.com/u0sNa3B.png
	*bogusUpgrade7
	-"Everything is 4% more efficient for each bread.  <br><i>thats it. im getting the bread.<br><br>"+4" ~Developer Tofusaturn</i>
	-costs 1e+28 code
	-named TFU's bread
	-multiplies efficiency of writeCode by 4% per theBread
	-multiplies efficiency of codeWriter by 4% per theBread
	-multiplies efficiency of object by 4% per theBread
	-multiplies efficiency of enemy by 4% per theBread
	-multiplies efficiency of player by 4% per theBread
	-multiplies efficiency of level by 4% per theBread
	-multiplies efficiency of game by 4% per theBread
	-multiplies efficiency of fanbase by 4% per theBread
	-multiplies efficiency of forum by 4% per theBread
	-multiplies efficiency of advertise by 4% per theBread
	-multiplies efficiency of studio by 4% per theBread
	-multiplies efficiency of magic by 4% per theBread
	-multiplies efficiency of gameSeries by 4% per theBread
	-multiplies efficiency of popularYoutuber by 4% per theBread
	-multiplies efficiency of gameProducer by 4% per theBread
	-multiplies efficiency of highReviewer by 4% per theBread
	-multiplies efficiency of maganiumGenerator by 4% per theBread
	-multiplies efficiency of finality by 4% per theBread
	-multiplies efficiency of magicPointBuilding by 4% per theBread
	-unlocks at 17 popularity
	-picture : http://i.imgur.com/uVQcsZR.png
	*bogusUpgrade8
	-"Research labs and manual research are <b>0.01%</b> more efficient for each building. <br><i></i>
	-multiplies efficiency of research by 0.01% per buildings
	-multiplies efficiency of research2 by 0.01% per buildings
	-multiplies efficiency of research3 by 0.01% per buildings
	-multiplies efficiency of research4 by 0.01% per buildings
	-multiplies efficiency of speedResearch by 0.01% per buildings
	-multiplies efficiency of speedResearch2 by 0.01% per buildings
	-multiplies efficiency of speedResearch3 by 0.01% per buildings
	-multiplies efficiency of speedResearch4 by 0.01% per buildings
	-costs 1e+29 code
	-named Researching Engineers
	-unlocks at 18 popularity
	-picture : http://i.imgur.com/9VoHIiB.png
	*bogusUpgrade9
	-"Everything is 20% more efficient. <br><i>Let's do something to the Unknown...</i>
	-costs 1e+30 code
	-named Unknown Enhancement
	-multiplies efficiency of writeCode by 120%
	-multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of object by 120%
	-multiplies efficiency of enemy by 120%
	-multiplies efficiency of player by 120%
	-multiplies efficiency of level by 120%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of studio by 120%
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of gameSeries by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-multiplies efficiency of gameProducer by 120%
	-multiplies efficiency of highReviewer by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-multiplies efficiency of finality by 120%
	-multiplies efficiency of magicPointBuilding by 120%
	-unlocks at 19 popularity
	-picture : http://i.imgur.com/vNqAWQY.png
	*bogusUpgrade10
	-"Fanbases, forums, and popular YouTubers are three times as efficient. <br><i>Your game slowly turns into a religion for some. Unlike Helixism and "egg"ism, this religion is taken seriously. And since haters are now rare, this doesn't cause much hate.</i>
	-costs 1e+31 code
	-multiplies efficiency of fanbase by 300%
	-multiplies efficiency of forum by 300%
	-multiplies efficiency of popularYoutuber by 300%
	-named Game-based religions
	-unlocks at 20 popularity
	-picture : http://i.imgur.com/IVDy8Mr.png
	*bogusUpgrade11
	-"Everything is 6% more efficient.   <br><i>There are some useful things in Hell. Let's go and check 'em out!</i>
	-costs 1e+32 code
	-named Descent into Hell
	-multiplies efficiency of writeCode by 106%
	-multiplies efficiency of codeWriter by 106%
	-multiplies efficiency of object by 106%
	-multiplies efficiency of enemy by 106%
	-multiplies efficiency of player by 106%
	-multiplies efficiency of level by 106%
	-multiplies efficiency of game by 106%
	-multiplies efficiency of fanbase by 106%
	-multiplies efficiency of forum by 106%
	-multiplies efficiency of advertise by 106%
	-multiplies efficiency of studio by 106%
	-multiplies efficiency of magic by 106%
	-multiplies efficiency of gameSeries by 106%
	-multiplies efficiency of popularYoutuber by 106%
	-multiplies efficiency of gameProducer by 106%
	-multiplies efficiency of highReviewer by 106%
	-multiplies efficiency of maganiumGenerator by 106%
	-multiplies efficiency of finality by 106%
	-multiplies efficiency of magicPointBuilding by 106%
	-unlocks at 21 popularity
	-picture : http://i.imgur.com/7k2PXuX.png
	*bogusUpgrade12
	-"Code writers, manual code writing, studios, magic code writers, and finalities are twice as efficient. <br><i>Surprisingly tasty.</i>
	-costs 1e+33 code
	-multiplies efficiency of writeCode by 200%
	-multiplies efficiency of codeWriter by 200%
	-multiplies efficiency of studio by 200%
	-multiplies efficiency of magic by 200%
	-multiplies efficiency of finality by 200%
	-named Pixel Burgers
	-unlocks at 22 popularity
	-picture : http://i.imgur.com/ikN0x1S.png
	*bogusUpgrade13
	-"Everything is 10% more efficient, except advertisments and finalities, which are 50% more efficient. <br><i>All other merchandise shall be eliminated.<br><br> "But I like all that other merchandise I don't want it to go *crying*"~ Developer Bakanium<br><br>"SHUT THE FUCK UP."~ Developer Kezelwal </i>
	-costs 1e+34 code
	-multiplies efficiency of writeCode by 110%
	-multiplies efficiency of codeWriter by 110%
	-multiplies efficiency of object by 110%
	-multiplies efficiency of enemy by 110%
	-multiplies efficiency of player by 110%
	-multiplies efficiency of level by 110%
	-multiplies efficiency of game by 110%
	-multiplies efficiency of fanbase by 110%
	-multiplies efficiency of forum by 110%
	-multiplies efficiency of advertise by 150%
	-multiplies efficiency of studio by 110%
	-multiplies efficiency of magic by 110%
	-multiplies efficiency of gameSeries by 110%
	-multiplies efficiency of popularYoutuber by 110%
	-multiplies efficiency of gameProducer by 110%
	-multiplies efficiency of highReviewer by 110%
	-multiplies efficiency of maganiumGenerator by 110%
	-multiplies efficiency of finality by 150%
	-multiplies efficiency of magicPointBuilding by 110%
	-named Finality Merchandise
	-unlocks at 23 popularity
	-picture : http://i.imgur.com/P8fmroM.png
	*bogusUpgrade14
	-"Everything is 6% more efficient.   <br><i>We found a strange stone in Hell. It contains huge power.</i>
	-multiplies efficiency of writeCode by 106%
	-multiplies efficiency of codeWriter by 106%
	-multiplies efficiency of object by 106%
	-multiplies efficiency of enemy by 106%
	-multiplies efficiency of player by 106%
	-multiplies efficiency of level by 106%
	-multiplies efficiency of game by 106%
	-multiplies efficiency of fanbase by 106%
	-multiplies efficiency of forum by 106%
	-multiplies efficiency of advertise by 106%
	-multiplies efficiency of studio by 106%
	-multiplies efficiency of magic by 106%
	-multiplies efficiency of gameSeries by 106%
	-multiplies efficiency of popularYoutuber by 106%
	-multiplies efficiency of gameProducer by 106%
	-multiplies efficiency of highReviewer by 106%
	-multiplies efficiency of maganiumGenerator by 106%
	-multiplies efficiency of finality by 106%
	-multiplies efficiency of magicPointBuilding by 106%
	-costs 1e+35 code
	-named Hell Stone
	-unlocks at 24 popularity
	-picture : http://i.imgur.com/lYXTpz1.png
	*bonusUpgrade15
	-"Everything is 16% more efficient.   <br><i>Deeper into Hell, we find more powerful things. It's getting a bit hot though...</i>
	-costs 1e+36 code
	-named Second Descent into Hell
	-unlocks at 25 popularity
	-multiplies efficiency of writeCode by 116%
	-multiplies efficiency of codeWriter by 116%
	-multiplies efficiency of object by 116%
	-multiplies efficiency of enemy by 116%
	-multiplies efficiency of player by 116%
	-multiplies efficiency of level by 116%
	-multiplies efficiency of game by 116%
	-multiplies efficiency of fanbase by 116%
	-multiplies efficiency of forum by 116%
	-multiplies efficiency of advertise by 116%
	-multiplies efficiency of studio by 116%
	-multiplies efficiency of magic by 116%
	-multiplies efficiency of gameSeries by 116%
	-multiplies efficiency of popularYoutuber by 116%
	-multiplies efficiency of gameProducer by 116%
	-multiplies efficiency of highReviewer by 116%
	-multiplies efficiency of maganiumGenerator by 116%
	-multiplies efficiency of finality by 116%
	-multiplies efficiency of magicPointBuilding by 116%
	-picture : http://i.imgur.com/tfG8y8Q.png
	*bonusUpgrade16
	-"Games produce five times as much code. <br><i>Everyone in the world can understand your games now. Even tribes in the Amazon Rainforest.</i>
	-costs 1e+37 code
	-multiplies efficiency of game by 500%
	-named All the Translations
	-unlocks at 26 popularity
	-picture : http://i.imgur.com/X8DP2IY.png
	*bonusUpgrade17
	-"Manual coding is 66% more efficient.   <br><i>The Hell Stone can boost your ability to code, as well.</i>
	-costs 1e+38 code
	-named Code of Hell
	-unlocks at 27 popularity
	-picture : http://i.imgur.com/tIXC7t2.png
	*bonusUpgrade18
	-"Everything is 30% more efficient.   <br><i>Doing more enhancements on The Unknown results in... code. Lots of it.</i>
	-costs 1e+39 code
	-named Further Unknown Enhancements
	-unlocks at 28 popularity
	-multiplies efficiency of writeCode by 130%
	-multiplies efficiency of codeWriter by 130%
	-multiplies efficiency of object by 130%
	-multiplies efficiency of enemy by 130%
	-multiplies efficiency of player by 130%
	-multiplies efficiency of level by 130%
	-multiplies efficiency of game by 130%
	-multiplies efficiency of fanbase by 130%
	-multiplies efficiency of forum by 130%
	-multiplies efficiency of advertise by 130%
	-multiplies efficiency of studio by 130%
	-multiplies efficiency of magic by 130%
	-multiplies efficiency of gameSeries by 130%
	-multiplies efficiency of popularYoutuber by 130%
	-multiplies efficiency of gameProducer by 130%
	-multiplies efficiency of highReviewer by 130%
	-multiplies efficiency of maganiumGenerator by 130%
	-multiplies efficiency of finality by 130%
	-multiplies efficiency of magicPointBuilding by 130%
	-picture : http://i.imgur.com/6yxkc7o.png
	*bonusUpgrade19
	-"Everything is 16% more efficient.   <br><i>We're really deep into Hell. We're finding strange magic, code portals, and more odd stuff.<br><br>It's really hot down there...</i>
	-costs 1e+40 code
	-named Third Descent into Hell
	-unlocks at 29 popularity
	-multiplies efficiency of writeCode by 116%
	-multiplies efficiency of codeWriter by 116%
	-multiplies efficiency of object by 116%
	-multiplies efficiency of enemy by 116%
	-multiplies efficiency of player by 116%
	-multiplies efficiency of level by 116%
	-multiplies efficiency of game by 116%
	-multiplies efficiency of fanbase by 116%
	-multiplies efficiency of forum by 116%
	-multiplies efficiency of advertise by 116%
	-multiplies efficiency of studio by 116%
	-multiplies efficiency of magic by 116%
	-multiplies efficiency of gameSeries by 116%
	-multiplies efficiency of popularYoutuber by 116%
	-multiplies efficiency of gameProducer by 116%
	-multiplies efficiency of highReviewer by 116%
	-multiplies efficiency of maganiumGenerator by 116%
	-multiplies efficiency of finality by 116%
	-multiplies efficiency of magicPointBuilding by 116%
	-picture : http://i.imgur.com/9YeyEKf.png
	*bonusUpgrade20
	-"Everything is 0.005% more efficient for each building.  <br><i>The buildings are summoning giant code vortexes. The more buildings, the more code.<br><br>"What the fuck, that fucking vortex just turned my brick wall into code." ~Developer Kezelwal<br><br>"That was MY brick wall, not yours!" ~Generic Developer #52</i>
	-costs 1e+41 code
	-named Code Vortexes
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-unlocks at 30 popularity
	-picture : http://i.imgur.com/3GobV6H.png

	*bonusUpgrade21
	-"Everything is 16% more efficient.   <br><i>Another Hell stone! This time, it's a lot more powerful.</i>
	-costs 1e+42 code
	-named Powerful Hell Stone
	-multiplies efficiency of writeCode by 116%
	-multiplies efficiency of codeWriter by 116%
	-multiplies efficiency of object by 116%
	-multiplies efficiency of enemy by 116%
	-multiplies efficiency of player by 116%
	-multiplies efficiency of level by 116%
	-multiplies efficiency of game by 116%
	-multiplies efficiency of fanbase by 116%
	-multiplies efficiency of forum by 116%
	-multiplies efficiency of advertise by 116%
	-multiplies efficiency of studio by 116%
	-multiplies efficiency of magic by 116%
	-multiplies efficiency of gameSeries by 116%
	-multiplies efficiency of popularYoutuber by 116%
	-multiplies efficiency of gameProducer by 116%
	-multiplies efficiency of highReviewer by 116%
	-multiplies efficiency of maganiumGenerator by 116%
	-multiplies efficiency of finality by 116%
	-multiplies efficiency of magicPointBuilding by 116%
	-unlocks at 31 popularity
	-picture : http://i.imgur.com/FsvR7av.png
	*bonusUpgrade22
	-"Everything is 20% more efficient.   <br><i>Our games have dominated Earth, and we have enough money to go to the Moon. We will spread our games there, and the fact that our games will be the first on the Moon gives us a morale boost! </i>
	-multiplies efficiency of writeCode by 120%
	-multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of object by 120%
	-multiplies efficiency of enemy by 120%
	-multiplies efficiency of player by 120%
	-multiplies efficiency of level by 120%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of studio by 120%
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of gameSeries by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-multiplies efficiency of gameProducer by 120%
	-multiplies efficiency of highReviewer by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-multiplies efficiency of finality by 120%
	-multiplies efficiency of magicPointBuilding by 120%
	-costs 1e+43 code
	-named Mission to the Moon
	-unlocks at 32 popularity
	-picture : http://i.imgur.com/JAq5j04.png
	*bonusUpgrade23
	-"Everything is 25% more efficient.   <br><i>We're not sure how this works exactly, but by using some weird mirror thing, all our code is multiplied!</i>
	-costs 1e+44 code
	-multiplies efficiency of writeCode by 125%
	-multiplies efficiency of codeWriter by 125%
	-multiplies efficiency of object by 125%
	-multiplies efficiency of enemy by 125%
	-multiplies efficiency of player by 125%
	-multiplies efficiency of level by 125%
	-multiplies efficiency of game by 125%
	-multiplies efficiency of fanbase by 125%
	-multiplies efficiency of forum by 125%
	-multiplies efficiency of advertise by 125%
	-multiplies efficiency of studio by 125%
	-multiplies efficiency of magic by 125%
	-multiplies efficiency of gameSeries by 125%
	-multiplies efficiency of popularYoutuber by 125%
	-multiplies efficiency of gameProducer by 125%
	-multiplies efficiency of highReviewer by 125%
	-multiplies efficiency of maganiumGenerator by 125%
	-multiplies efficiency of finality by 125%
	-multiplies efficiency of magicPointBuilding by 125%
	-named Mirrorage
	-unlocks at 33 popularity
	-picture : http://i.imgur.com/I4UVsax.png
	*bonusUpgrade24
	-"Everything is 45% more efficient.   <br><i>If we power up the Unknown with some Hell Stones, then maybe...</i>
	-costs 1e+45 code
	-multiplies efficiency of writeCode by 145%
	-multiplies efficiency of codeWriter by 145%
	-multiplies efficiency of object by 145%
	-multiplies efficiency of enemy by 145%
	-multiplies efficiency of player by 145%
	-multiplies efficiency of level by 145%
	-multiplies efficiency of game by 145%
	-multiplies efficiency of fanbase by 145%
	-multiplies efficiency of forum by 145%
	-multiplies efficiency of advertise by 145%
	-multiplies efficiency of studio by 145%
	-multiplies efficiency of magic by 145%
	-multiplies efficiency of gameSeries by 145%
	-multiplies efficiency of popularYoutuber by 145%
	-multiplies efficiency of gameProducer by 145%
	-multiplies efficiency of highReviewer by 145%
	-multiplies efficiency of maganiumGenerator by 145%
	-multiplies efficiency of finality by 145%
	-multiplies efficiency of magicPointBuilding by 145%
	-named Hell Unknown Enhancements
	-unlocks at 34 popularity
	-picture : http://i.imgur.com/xVDW5D2.png
	*bonusUpgrade25
	-"Everything is 40% more efficient.   <br><i>The fact that we were the first to Mars gives us even more of a morale boost! Also, if humanity ever needs to evacuate Earth and go to Mars, our games will still exist.<br><br>"Like that will ever happen" ~Developer Bakanium</i>
	-costs 1e+46 code
	-named Mission to Mars
	-multiplies efficiency of writeCode by 140%
	-multiplies efficiency of codeWriter by 140%
	-multiplies efficiency of object by 140%
	-multiplies efficiency of enemy by 140%
	-multiplies efficiency of player by 140%
	-multiplies efficiency of level by 140%
	-multiplies efficiency of game by 140%
	-multiplies efficiency of fanbase by 140%
	-multiplies efficiency of forum by 140%
	-multiplies efficiency of advertise by 140%
	-multiplies efficiency of studio by 140%
	-multiplies efficiency of magic by 140%
	-multiplies efficiency of gameSeries by 140%
	-multiplies efficiency of popularYoutuber by 140%
	-multiplies efficiency of gameProducer by 140%
	-multiplies efficiency of highReviewer by 140%
	-multiplies efficiency of maganiumGenerator by 140%
	-multiplies efficiency of finality by 140%
	-multiplies efficiency of magicPointBuilding by 140%
	-unlocks at 35 popularity
	-picture : http://i.imgur.com/XQ4mHZ1.png
	*bonusUpgrade26
	-"Everything is 66% more efficient.   <br><i>Stuff is really weird down there. So weird I can't describe. Just imagine a grenade that explodes into guns that shoot portals that produce code.<br><br>"Fucking hell. That IS weird." ~Developer Kezelwal</i>
	-costs 1e+47 code
	-named Final Descent into Hell
	-multiplies efficiency of writeCode by 166%
	-multiplies efficiency of codeWriter by 166%
	-multiplies efficiency of object by 166%
	-multiplies efficiency of enemy by 166%
	-multiplies efficiency of player by 166%
	-multiplies efficiency of level by 166%
	-multiplies efficiency of game by 166%
	-multiplies efficiency of fanbase by 166%
	-multiplies efficiency of forum by 166%
	-multiplies efficiency of advertise by 166%
	-multiplies efficiency of studio by 166%
	-multiplies efficiency of magic by 166%
	-multiplies efficiency of gameSeries by 166%
	-multiplies efficiency of popularYoutuber by 166%
	-multiplies efficiency of gameProducer by 166%
	-multiplies efficiency of highReviewer by 166%
	-multiplies efficiency of maganiumGenerator by 166%
	-multiplies efficiency of finality by 166%
	-multiplies efficiency of magicPointBuilding by 166%
	-unlocks at 36 popularity
	-picture : http://i.imgur.com/VxCpCMG.png
	*bonusUpgrade27
	-"Everything is 0.005% more efficient per building.   <br><i>This is weird. </i>
	-costs 1e+48 code
	-named Vortexes that spawn more vortexes
	-unlocks at 37 popularity
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-picture : http://i.imgur.com/Otrzgvj.png
	*bonusUpgrade28
	-"Everything is 66% more efficient.   <br><i>We did a deal with the demons, and we got this stone. It contains power unknown to mankind.<br><br>"Destroy it, it's dangerous." ~Developer Bakanium</i>
	-costs 1e+49 code
	-named Ultimate Hell Stone
	-unlocks at 38 popularity
	-multiplies efficiency of writeCode by 166%
	-multiplies efficiency of codeWriter by 166%
	-multiplies efficiency of object by 166%
	-multiplies efficiency of enemy by 166%
	-multiplies efficiency of player by 166%
	-multiplies efficiency of level by 166%
	-multiplies efficiency of game by 166%
	-multiplies efficiency of fanbase by 166%
	-multiplies efficiency of forum by 166%
	-multiplies efficiency of advertise by 166%
	-multiplies efficiency of studio by 166%
	-multiplies efficiency of magic by 166%
	-multiplies efficiency of gameSeries by 166%
	-multiplies efficiency of popularYoutuber by 166%
	-multiplies efficiency of gameProducer by 166%
	-multiplies efficiency of highReviewer by 166%
	-multiplies efficiency of maganiumGenerator by 166%
	-multiplies efficiency of finality by 166%
	-multiplies efficiency of magicPointBuilding by 166%
	-picture : http://i.imgur.com/pRH2HqR.png
	*bonusUpgrade29
	-"everything is 50% more efficient.   <br><i>The galaxy contains some pretty interesting things. Some of which are extremely useful.</i>
	-costs 1e+50 code
	-named Missions to the Galaxy
	-multiplies efficiency of writeCode by 150%
	-multiplies efficiency of codeWriter by 150%
	-multiplies efficiency of object by 150%
	-multiplies efficiency of enemy by 150%
	-multiplies efficiency of player by 150%
	-multiplies efficiency of level by 150%
	-multiplies efficiency of game by 150%
	-multiplies efficiency of fanbase by 150%
	-multiplies efficiency of forum by 150%
	-multiplies efficiency of advertise by 150%
	-multiplies efficiency of studio by 150%
	-multiplies efficiency of magic by 150%
	-multiplies efficiency of gameSeries by 150%
	-multiplies efficiency of popularYoutuber by 150%
	-multiplies efficiency of gameProducer by 150%
	-multiplies efficiency of highReviewer by 150%
	-multiplies efficiency of maganiumGenerator by 150%
	-multiplies efficiency of finality by 150%
	-multiplies efficiency of magicPointBuilding by 150%
	-unlocks at 39 popularity
	-picture : http://i.imgur.com/PqugWdV.png
	*bonusUpgrade30
	-"Everything is 70% more efficient.   <br><i>We used the Ultimate Hell Stone on the Unknown, and things are crazy.</i>
	-costs 1e+51 code
	-multiplies efficiency of writeCode by 170%
	-multiplies efficiency of codeWriter by 170%
	-multiplies efficiency of object by 170%
	-multiplies efficiency of enemy by 170%
	-multiplies efficiency of player by 170%
	-multiplies efficiency of level by 170%
	-multiplies efficiency of game by 170%
	-multiplies efficiency of fanbase by 170%
	-multiplies efficiency of forum by 170%
	-multiplies efficiency of advertise by 170%
	-multiplies efficiency of studio by 170%
	-multiplies efficiency of magic by 170%
	-multiplies efficiency of gameSeries by 170%
	-multiplies efficiency of popularYoutuber by 170%
	-multiplies efficiency of gameProducer by 170%
	-multiplies efficiency of highReviewer by 170%
	-multiplies efficiency of maganiumGenerator by 170%
	-multiplies efficiency of finality by 170%
	-multiplies efficiency of magicPointBuilding by 170%
	-named Ultimate Hell Unknown Enhancements
	-unlocks at 40 popularity
	-picture : http://i.imgur.com/Rah7nnz.png

	*bonusUpgrade31
	-"Everything is 50% more efficient.   <br><i>More mirrors = more code. The mirrors have NOTHING to do with bad word mirrors.</i>
	-costs 1e+52 code
	-named Advances Mirrorage
	-unlocks at 41 popularity
	-multiplies efficiency of writeCode by 150%
	-multiplies efficiency of codeWriter by 150%
	-multiplies efficiency of object by 150%
	-multiplies efficiency of enemy by 150%
	-multiplies efficiency of player by 150%
	-multiplies efficiency of level by 150%
	-multiplies efficiency of game by 150%
	-multiplies efficiency of fanbase by 150%
	-multiplies efficiency of forum by 150%
	-multiplies efficiency of advertise by 150%
	-multiplies efficiency of studio by 150%
	-multiplies efficiency of magic by 150%
	-multiplies efficiency of gameSeries by 150%
	-multiplies efficiency of popularYoutuber by 150%
	-multiplies efficiency of gameProducer by 150%
	-multiplies efficiency of highReviewer by 150%
	-multiplies efficiency of maganiumGenerator by 150%
	-multiplies efficiency of finality by 150%
	-multiplies efficiency of magicPointBuilding by 150%
	-picture : http://i.imgur.com/8TXisgF.png
	*bonusUpgrade32
	-"Everything is 4% more efficient per bread.  <br><i>Combining bread and the number four had a really powerful effect.<br><br>"Best upgrade ever 4/4" ~Developer Tofusaturn</i>
	-costs 1e+53 code
	-named Bread-4 synergy
	-multiplies efficiency of writeCode by 4% per theBread
	-multiplies efficiency of codeWriter by 4% per theBread
	-multiplies efficiency of object by 4% per theBread
	-multiplies efficiency of enemy by 4% per theBread
	-multiplies efficiency of player by 4% per theBread
	-multiplies efficiency of level by 4% per theBread
	-multiplies efficiency of game by 4% per theBread
	-multiplies efficiency of fanbase by 4% per theBread
	-multiplies efficiency of forum by 4% per theBread
	-multiplies efficiency of advertise by 4% per theBread
	-multiplies efficiency of studio by 4% per theBread
	-multiplies efficiency of magic by 4% per theBread
	-multiplies efficiency of gameSeries by 4% per theBread
	-multiplies efficiency of popularYoutuber by 4% per theBread
	-multiplies efficiency of gameProducer by 4% per theBread
	-multiplies efficiency of highReviewer by 4% per theBread
	-multiplies efficiency of maganiumGenerator by 4% per theBread
	-multiplies efficiency of finality by 4% per theBread
	-multiplies efficiency of magicPointBuilding by 4% per theBread
	-unlocks at 42 popularity
	-picture : http://i.imgur.com/tuWyQY4.png
	*bonusUpgrade33
	-"Everything is 70% more efficient.   <br><i>We found this code planet, and my was there code everywhere. Requesting immediate construction of shipments.</i>
	-costs 1e+54 code
	-multiplies efficiency of writeCode by 170%
	-multiplies efficiency of codeWriter by 170%
	-multiplies efficiency of object by 170%
	-multiplies efficiency of enemy by 170%
	-multiplies efficiency of player by 170%
	-multiplies efficiency of level by 170%
	-multiplies efficiency of game by 170%
	-multiplies efficiency of fanbase by 170%
	-multiplies efficiency of forum by 170%
	-multiplies efficiency of advertise by 170%
	-multiplies efficiency of studio by 170%
	-multiplies efficiency of magic by 170%
	-multiplies efficiency of gameSeries by 170%
	-multiplies efficiency of popularYoutuber by 170%
	-multiplies efficiency of gameProducer by 170%
	-multiplies efficiency of highReviewer by 170%
	-multiplies efficiency of maganiumGenerator by 170%
	-multiplies efficiency of finality by 170%
	-multiplies efficiency of magicPointBuilding by 170%
	-named Missions to the code planet
	-unlocks at 43 popularity
	-picture : http://i.imgur.com/hJOlOTX.png
	*bonusUpgrade34
	-"Everything is 40% more efficient.   <br><i>We are finding some extraterrestrial life in this galaxy, we should make translations so the aliens can play our games too. No one ever thought this could be accomplished.</i>
	-costs 1e+55 code
	-multiplies efficiency of writeCode by 140%
	-multiplies efficiency of codeWriter by 140%
	-multiplies efficiency of object by 140%
	-multiplies efficiency of enemy by 140%
	-multiplies efficiency of player by 140%
	-multiplies efficiency of level by 140%
	-multiplies efficiency of game by 140%
	-multiplies efficiency of fanbase by 140%
	-multiplies efficiency of forum by 140%
	-multiplies efficiency of advertise by 140%
	-multiplies efficiency of studio by 140%
	-multiplies efficiency of magic by 140%
	-multiplies efficiency of gameSeries by 140%
	-multiplies efficiency of popularYoutuber by 140%
	-multiplies efficiency of gameProducer by 140%
	-multiplies efficiency of highReviewer by 140%
	-multiplies efficiency of maganiumGenerator by 140%
	-multiplies efficiency of finality by 140%
	-multiplies efficiency of magicPointBuilding by 140%
	-named Alien translations
	-unlocks at 44 popularity
	-picture : http://i.imgur.com/SlZd5Zp.png
	*bonusUpgrade35
	-"Everything is twice as efficient.   <br><i>Reality? You know what, fuck that. I'm having code raining from the sky, faster-than-light speeds, time travel and giant monsters that turn stuff into code!</i>
	-costs 1e+56 code
	-named Reality Breach
	-multiplies efficiency of writeCode by 200%
	-multiplies efficiency of codeWriter by 200%
	-multiplies efficiency of object by 200%
	-multiplies efficiency of enemy by 200%
	-multiplies efficiency of player by 200%
	-multiplies efficiency of level by 200%
	-multiplies efficiency of game by 200%
	-multiplies efficiency of fanbase by 200%
	-multiplies efficiency of forum by 200%
	-multiplies efficiency of advertise by 200%
	-multiplies efficiency of studio by 200%
	-multiplies efficiency of magic by 200%
	-multiplies efficiency of gameSeries by 200%
	-multiplies efficiency of popularYoutuber by 200%
	-multiplies efficiency of gameProducer by 200%
	-multiplies efficiency of highReviewer by 200%
	-multiplies efficiency of maganiumGenerator by 200%
	-multiplies efficiency of finality by 200%
	-multiplies efficiency of magicPointBuilding by 200%
	-unlocks at 45 popularity
	-picture : http://i.imgur.com/DxtK1Mi.png
	*bonusUpgrade36
	-"Everything is 90% more efficient.   <br><i>With faster-than-light travel, we can reach the ends of the universe, and find the most beneficial things there are! We also get a large morale boost!</i>
	-costs 1e+57 code
	-multiplies efficiency of writeCode by 190%
	-multiplies efficiency of codeWriter by 190%
	-multiplies efficiency of object by 190%
	-multiplies efficiency of enemy by 190%
	-multiplies efficiency of player by 190%
	-multiplies efficiency of level by 190%
	-multiplies efficiency of game by 190%
	-multiplies efficiency of fanbase by 190%
	-multiplies efficiency of forum by 190%
	-multiplies efficiency of advertise by 190%
	-multiplies efficiency of studio by 190%
	-multiplies efficiency of magic by 190%
	-multiplies efficiency of gameSeries by 190%
	-multiplies efficiency of popularYoutuber by 190%
	-multiplies efficiency of gameProducer by 190%
	-multiplies efficiency of highReviewer by 190%
	-multiplies efficiency of maganiumGenerator by 190%
	-multiplies efficiency of finality by 190%
	-multiplies efficiency of magicPointBuilding by 190%
	-named Missions to the ends of the Universe
	-unlocks at 46 popularity
	-picture : http://i.imgur.com/jqRrvL3.png
	*bonusUpgrade37
	-"Everything is 90% more efficient.   <br><i>We can make the Unknown breach reality, too.</i>
	-costs 1e+58 code
	-multiplies efficiency of writeCode by 190%
	-multiplies efficiency of codeWriter by 190%
	-multiplies efficiency of object by 190%
	-multiplies efficiency of enemy by 190%
	-multiplies efficiency of player by 190%
	-multiplies efficiency of level by 190%
	-multiplies efficiency of game by 190%
	-multiplies efficiency of fanbase by 190%
	-multiplies efficiency of forum by 190%
	-multiplies efficiency of advertise by 190%
	-multiplies efficiency of studio by 190%
	-multiplies efficiency of magic by 190%
	-multiplies efficiency of gameSeries by 190%
	-multiplies efficiency of popularYoutuber by 190%
	-multiplies efficiency of gameProducer by 190%
	-multiplies efficiency of highReviewer by 190%
	-multiplies efficiency of maganiumGenerator by 190%
	-multiplies efficiency of finality by 190%
	-multiplies efficiency of magicPointBuilding by 190%
	-named Reality-breaching Unknown
	-unlocks at 47 popularity
	-picture : http://i.imgur.com/6P05nm1.png
	*bonusUpgrade38
	-"Everything is twice as efficient.   <br><i>Finality-powered engines spread our game everywhere in the Universe.</i>
	-costs 1e+59 code
	-named Finality-powered engines
	-unlocks at 48 popularity
	-multiplies efficiency of writeCode by 200%
	-multiplies efficiency of codeWriter by 200%
	-multiplies efficiency of object by 200%
	-multiplies efficiency of enemy by 200%
	-multiplies efficiency of player by 200%
	-multiplies efficiency of level by 200%
	-multiplies efficiency of game by 200%
	-multiplies efficiency of fanbase by 200%
	-multiplies efficiency of forum by 200%
	-multiplies efficiency of advertise by 200%
	-multiplies efficiency of studio by 200%
	-multiplies efficiency of magic by 200%
	-multiplies efficiency of gameSeries by 200%
	-multiplies efficiency of popularYoutuber by 200%
	-multiplies efficiency of gameProducer by 200%
	-multiplies efficiency of highReviewer by 200%
	-multiplies efficiency of maganiumGenerator by 200%
	-multiplies efficiency of finality by 200%
	-multiplies efficiency of magicPointBuilding by 200%
	-picture : http://i.imgur.com/Uln8U5I.png
	*bonusUpgrade39
	-"Everything is twice as efficient.   <br><i>Every single extraterrestial life form that can play your games, is now playing your games.</i>
	-costs 1e+60 code
	-named All the alien translations
	-unlocks at 49 popularity
	-multiplies efficiency of writeCode by 200%
	-multiplies efficiency of codeWriter by 200%
	-multiplies efficiency of object by 200%
	-multiplies efficiency of enemy by 200%
	-multiplies efficiency of player by 200%
	-multiplies efficiency of level by 200%
	-multiplies efficiency of game by 200%
	-multiplies efficiency of fanbase by 200%
	-multiplies efficiency of forum by 200%
	-multiplies efficiency of advertise by 200%
	-multiplies efficiency of studio by 200%
	-multiplies efficiency of magic by 200%
	-multiplies efficiency of gameSeries by 200%
	-multiplies efficiency of popularYoutuber by 200%
	-multiplies efficiency of gameProducer by 200%
	-multiplies efficiency of highReviewer by 200%
	-multiplies efficiency of maganiumGenerator by 200%
	-multiplies efficiency of finality by 200%
	-multiplies efficiency of magicPointBuilding by 200%
	-picture : http://i.imgur.com/qRfHmTm.png
	*bonusUpgrade40
	-"Everything is 4 times as efficient.   <br><i>You win a cookie.</i>
	-costs 1e+61 code
	-named Cookie
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-unlocks at 50 popularity
	-picture : http://i.imgur.com/poTrc1j.png


	*alternateUniverseReset
	-"Unlocks the reset button. <br><i>Let's become the most popular game company... in another universe!</i>
	-costs 1000000000000000000000 code
	-named Alternate Universe Travel
	-unlocks reset
	-picture : http://i.imgur.com/yXYKOiS.png
	*winUnlock
	-"Unlocks the ability to win. <br><i>Our next goal... is win. Yes, you can win this idle game.</i>
	-costs 1 code
	-named The Win
	-unlocks at 1 overtake10
	-unlocks win
	-picture : http://i.imgur.com/yXYKOiS.png

	*playtimeUpgrade1
	-"Everything is <b>1%</b> more efficient.<br><i>It takes time to learn. After some time, we've improved a bit.</i>
	-unlocks at 60 time
	-costs 10000 code
	-multiplies efficiency of writeCode by 101%
	-multiplies efficiency of codeWriter by 101%
	-multiplies efficiency of object by 101%
	-multiplies efficiency of enemy by 101%
	-multiplies efficiency of player by 101%
	-multiplies efficiency of level by 101%
	-multiplies efficiency of game by 101%
	-multiplies efficiency of fanbase by 101%
	-multiplies efficiency of forum by 101%
	-multiplies efficiency of advertise by 101%
	-multiplies efficiency of studio by 101%
	-multiplies efficiency of magic by 101%
	-multiplies efficiency of gameSeries by 101%
	-multiplies efficiency of popularYoutuber by 101%
	-multiplies efficiency of gameProducer by 101%
	-multiplies efficiency of highReviewer by 101%
	-multiplies efficiency of maganiumGenerator by 101%
	-multiplies efficiency of finality by 101%
	-multiplies efficiency of magicPointBuilding by 101%
	-named Learning
	-picture : http://i.imgur.com/WjM2HmH.png
	*playtimeUpgrade2
	-"Everything is <b>0.01%</b> more efficient for every hour you play.<br><i>They say it takes 10,000 hours of practice to become an expert...</i>
	-unlocks at 600 time
	-costs 100000 code
	-named Practice
	-multiplies efficiency of writeCode by 0.000002777777777777777777777778% per time
	-multiplies efficiency of codeWriter by 0.000002777777777777777777777778% per time
	-multiplies efficiency of object by 0.000002777777777777777777777778% per time
	-multiplies efficiency of enemy by 0.000002777777777777777777777778% per time
	-multiplies efficiency of player by 0.000002777777777777777777777778% per time
	-multiplies efficiency of level by 0.000002777777777777777777777778% per time
	-multiplies efficiency of game by 0.000002777777777777777777777778% per time
	-multiplies efficiency of fanbase by 0.000002777777777777777777777778% per time
	-multiplies efficiency of forum by 0.000002777777777777777777777778% per time
	-multiplies efficiency of advertise by 0.000002777777777777777777777778% per time
	-multiplies efficiency of highReviewer by 0.000002777777777777777777777778% per time
	-multiplies efficiency of studio by 0.000002777777777777777777777778% per time
	-multiplies efficiency of magic by 0.000002777777777777777777777778% per time
	-multiplies efficiency of gameSeries by 0.000002777777777777777777777778% per time
	-multiplies efficiency of popularYoutuber by 0.000002777777777777777777777778% per time
	-multiplies efficiency of maganiumGenerator by 0.000002777777777777777777777778% per time
	-multiplies efficiency of finality by 0.000002777777777777777777777778% per time
	-multiplies efficiency of magicPointBuilding by 0.000002777777777777777777777778% per time
	-picture : http://i.imgur.com/KDOfNlq.png
	*playtimeUpgrade3
	-"Games are <b>0.1%</b> more efficient for every hour you play.<br><i>We are learning from mistakes. We realise what went wrong, and why people don't like us.</i>
	-costs 50000000 code
	-unlocks at 3600 time
	-multiplies efficiency of game by 0.00002777777777777777777777778% per time
	-named Learning to make better games
	-picture : http://i.imgur.com/pivMW9X.png
	*playtimeUpgrade4
	-"Everything is <b>0.01%</b> more efficient for every hour you play.<br><i>It seems that other game developers are doing things to make them more popular. If we see what they do, surely we can become better.</i>
	-costs 1e+9 code
	-multiplies efficiency of writeCode by 0.000002777777777777777777777778% per time
	-multiplies efficiency of codeWriter by 0.000002777777777777777777777778% per time
	-multiplies efficiency of object by 0.000002777777777777777777777778% per time
	-multiplies efficiency of enemy by 0.000002777777777777777777777778% per time
	-multiplies efficiency of player by 0.000002777777777777777777777778% per time
	-multiplies efficiency of level by 0.000002777777777777777777777778% per time
	-multiplies efficiency of game by 0.000002777777777777777777777778% per time
	-multiplies efficiency of fanbase by 0.000002777777777777777777777778% per time
	-multiplies efficiency of forum by 0.000002777777777777777777777778% per time
	-multiplies efficiency of advertise by 0.000002777777777777777777777778% per time
	-multiplies efficiency of highReviewer by 0.000002777777777777777777777778% per time
	-multiplies efficiency of studio by 0.000002777777777777777777777778% per time
	-multiplies efficiency of magic by 0.000002777777777777777777777778% per time
	-multiplies efficiency of gameSeries by 0.000002777777777777777777777778% per time
	-multiplies efficiency of popularYoutuber by 0.000002777777777777777777777778% per time
	-multiplies efficiency of maganiumGenerator by 0.000002777777777777777777777778% per time
	-multiplies efficiency of finality by 0.000002777777777777777777777778% per time
	-multiplies efficiency of magicPointBuilding by 0.000002777777777777777777777778% per time
	-unlocks at 10800 time
	-named Learning from other games
	-picture : http://i.imgur.com/86RAVM5.png
	*playtimeUpgrade5
	-"Advertisements are <b>0.1%</b>more efficient for every hour you play.<br><i>It takes time to put up advertisements. But gradually, people will put up more advertisements. And more.</i>
	-costs 1e+12 code
	-unlocks at 86400 time
	-multiplies efficiency of advertise by 0.00002777777777777777777777778% per time
	-named More advertisements
	-picture : http://i.imgur.com/CaYQJ8W.png
	*playtimeUpgrade6
	-"Everything is <b>10%</b> more efficient.<br><i>We need to learn more, and then we will become more intelligent, and better at making games.</i>
	-costs 1e+15 code
	-multiplies efficiency of writeCode by 110%
	-multiplies efficiency of codeWriter by 110%
	-multiplies efficiency of object by 110%
	-multiplies efficiency of enemy by 110%
	-multiplies efficiency of player by 110%
	-multiplies efficiency of level by 110%
	-multiplies efficiency of game by 110%
	-multiplies efficiency of fanbase by 110%
	-multiplies efficiency of forum by 110%
	-multiplies efficiency of advertise by 110%
	-multiplies efficiency of studio by 110%
	-multiplies efficiency of magic by 110%
	-multiplies efficiency of gameSeries by 110%
	-multiplies efficiency of popularYoutuber by 110%
	-multiplies efficiency of gameProducer by 110%
	-multiplies efficiency of highReviewer by 110%
	-multiplies efficiency of maganiumGenerator by 110%
	-multiplies efficiency of finality by 110%
	-multiplies efficiency of magicPointBuilding by 110%
	-unlocks at 172800 time
	-named Advanced Learning
	-picture : http://i.imgur.com/cmBW6mk.png
	*playtimeUpgrade7
	-"Everything is <b>0.1%</b> more efficient for every day you play.<br><i>Things can only get better.</i>
	-costs 1e+21 code
	-multiplies efficiency of writeCode by 0.00000115740740740740% per time
	-multiplies efficiency of codeWriter by 0.00000115740740740740% per time
	-multiplies efficiency of object by 0.00000115740740740740% per time
	-multiplies efficiency of enemy by 0.00000115740740740740% per time
	-multiplies efficiency of player by 0.00000115740740740740% per time
	-multiplies efficiency of level by 0.00000115740740740740% per time
	-multiplies efficiency of game by 0.00000115740740740740% per time
	-multiplies efficiency of fanbase by 0.00000115740740740740% per time
	-multiplies efficiency of forum by 0.00000115740740740740% per time
	-multiplies efficiency of advertise by 0.00000115740740740740% per time
	-multiplies efficiency of highReviewer by 0.00000115740740740740% per time
	-multiplies efficiency of studio by 0.00000115740740740740% per time
	-multiplies efficiency of magic by 0.00000115740740740740% per time
	-multiplies efficiency of gameSeries by 0.00000115740740740740% per time
	-multiplies efficiency of popularYoutuber by 0.00000115740740740740% per time
	-multiplies efficiency of maganiumGenerator by 0.00000115740740740740% per time
	-multiplies efficiency of finality by 0.00000115740740740740% per time
	-multiplies efficiency of magicPointBuilding by 0.00000115740740740740% per time
	-unlocks at 604800 time
	-named Daily power-up
	-picture : http://i.imgur.com/IV4zqxl.png
	*playtimeUpgrade8
	-"Everything is <b>20%</b> more efficient.
	-costs 1e+25 code
	-unlocks at 1209600 time
	-multiplies efficiency of writeCode by 120%
	-multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of object by 120%
	-multiplies efficiency of enemy by 120%
	-multiplies efficiency of player by 120%
	-multiplies efficiency of level by 120%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of studio by 120%
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of gameSeries by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-multiplies efficiency of gameProducer by 120%
	-multiplies efficiency of highReviewer by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-multiplies efficiency of finality by 120%
	-multiplies efficiency of magicPointBuilding by 120%
	-named Speed Up
	-picture : http://i.imgur.com/mw3Ql5t.png
	*playtimeUpgrade9
	-"Everything is <b>0.1%</b> more efficient for each day you play.<br><i>While looking around on old dungeons and mine shafts, we found a mysteriously coloured stone that has a mysterious essence of time.<br><br>"Throw it away. It's old and useless. We don't need it." ~Developer Bakanium<br><br>"Shut up. Why did the hiring pick you anyway?" ~Every other developer</i>
	-costs 1e+30 code
	-unlocks at 2419200 time
	-multiplies efficiency of writeCode by 0.00000115740740740740% per time
	-multiplies efficiency of codeWriter by 0.00000115740740740740% per time
	-multiplies efficiency of object by 0.00000115740740740740% per time
	-multiplies efficiency of enemy by 0.00000115740740740740% per time
	-multiplies efficiency of player by 0.00000115740740740740% per time
	-multiplies efficiency of level by 0.00000115740740740740% per time
	-multiplies efficiency of game by 0.00000115740740740740% per time
	-multiplies efficiency of fanbase by 0.00000115740740740740% per time
	-multiplies efficiency of forum by 0.00000115740740740740% per time
	-multiplies efficiency of advertise by 0.00000115740740740740% per time
	-multiplies efficiency of highReviewer by 0.00000115740740740740% per time
	-multiplies efficiency of studio by 0.00000115740740740740% per time
	-multiplies efficiency of magic by 0.00000115740740740740% per time
	-multiplies efficiency of gameSeries by 0.00000115740740740740% per time
	-multiplies efficiency of popularYoutuber by 0.00000115740740740740% per time
	-multiplies efficiency of maganiumGenerator by 0.00000115740740740740% per time
	-multiplies efficiency of finality by 0.00000115740740740740% per time
	-multiplies efficiency of magicPointBuilding by 0.00000115740740740740% per time
	-named Ancient Stone of Time
	-picture : http://i.imgur.com/EycDBgR.png
	*playtimeUpgrade10
	-"Magic code writers are <b>0.1%</b> more efficient for each hour you play.
	-unlocks at 5184000 time
	-costs 1e+40 code
	-named Magic Code Lessons
	-multiplies efficiency of magic by 0.00002777777777777777777777778% per time
	-picture : http://i.imgur.com/phuZIhK.png
	*playtimeUpgrade11
	-"Everything is <b>40%</b> more efficient.<br><i>What is this thing... ... ... TTTUUUUUUURRRRRRRRRRRBBBBBBBBBBBBBBBBBBBOOOOOOOOOOOOOOOO!!!!!</i>
	-costs 1e+50 code
	-multiplies efficiency of writeCode by 140%
	-multiplies efficiency of codeWriter by 140%
	-multiplies efficiency of object by 140%
	-multiplies efficiency of enemy by 140%
	-multiplies efficiency of player by 140%
	-multiplies efficiency of level by 140%
	-multiplies efficiency of game by 140%
	-multiplies efficiency of fanbase by 140%
	-multiplies efficiency of forum by 140%
	-multiplies efficiency of advertise by 140%
	-multiplies efficiency of studio by 140%
	-multiplies efficiency of magic by 140%
	-multiplies efficiency of gameSeries by 140%
	-multiplies efficiency of popularYoutuber by 140%
	-multiplies efficiency of gameProducer by 140%
	-multiplies efficiency of highReviewer by 140%
	-multiplies efficiency of maganiumGenerator by 140%
	-multiplies efficiency of finality by 140%
	-multiplies efficiency of magicPointBuilding by 140%
	-unlocks at 7776000 time
	-named Turbo Boost
	-picture : http://i.imgur.com/5dcDNsD.png
	*playtimeUpgrade12
	-"Everything is <b>60%</b> more efficient.<br><i>After breaching reality, we can make things go faster.</i>
	-costs 1e+60 code
	-unlocks at 15552000 time
	-multiplies efficiency of writeCode by 160%
	-multiplies efficiency of codeWriter by 160%
	-multiplies efficiency of object by 160%
	-multiplies efficiency of enemy by 160%
	-multiplies efficiency of player by 160%
	-multiplies efficiency of level by 160%
	-multiplies efficiency of game by 160%
	-multiplies efficiency of fanbase by 160%
	-multiplies efficiency of forum by 160%
	-multiplies efficiency of advertise by 160%
	-multiplies efficiency of studio by 160%
	-multiplies efficiency of magic by 160%
	-multiplies efficiency of gameSeries by 160%
	-multiplies efficiency of popularYoutuber by 160%
	-multiplies efficiency of gameProducer by 160%
	-multiplies efficiency of highReviewer by 160%
	-multiplies efficiency of maganiumGenerator by 160%
	-multiplies efficiency of finality by 160%
	-multiplies efficiency of magicPointBuilding by 160%
	-named Fast Forward
	-picture : http://i.imgur.com/ATzIrEX.png
	*playtimeUpgrade13
	-"Everything is 90% more efficient.<br><i>With time travel, we can go back millions of years ago, and collect ancient treasures with immense power.<br><br>"No point. The world is only 2014 years old." ~Developer Bakanium</i>
	-costs 1e+70 code
	-multiplies efficiency of writeCode by 190%
	-multiplies efficiency of codeWriter by 190%
	-multiplies efficiency of object by 190%
	-multiplies efficiency of enemy by 190%
	-multiplies efficiency of player by 190%
	-multiplies efficiency of level by 190%
	-multiplies efficiency of game by 190%
	-multiplies efficiency of fanbase by 190%
	-multiplies efficiency of forum by 190%
	-multiplies efficiency of advertise by 190%
	-multiplies efficiency of studio by 190%
	-multiplies efficiency of magic by 190%
	-multiplies efficiency of gameSeries by 190%
	-multiplies efficiency of popularYoutuber by 190%
	-multiplies efficiency of gameProducer by 190%
	-multiplies efficiency of highReviewer by 190%
	-multiplies efficiency of maganiumGenerator by 190%
	-multiplies efficiency of finality by 190%
	-multiplies efficiency of magicPointBuilding by 190%
	-unlocks at 23328000 time
	-named Time travel
	-picture : http://i.imgur.com/FgfebrM.png
	*playtimeUpgrade14
	-"Everything is <b>4 times</b> as efficient.<br><i>We now have complete dominance over time.<br><br>We later built a Time Facility that can be used to speed up, slow down, stop, reverse, or travel through, time, or erase things from time. Shortly before we activated the facility, we agreed on these: <br><br>1. You cannot use the facility to stop time for more than three hours. <br>2. You cannot speed time up by more than four times. <br> 3. Developer Bakanium is banned from using the facility. Wait, he's gone.<br> 4. The facility must be used to erase De- he's still gone. <br> 5. You must read the instruction booklet thoroughly before travelling through time. <br><br>No one can stop us now. No one.</i>
	-costs 1e+80 code
	-unlocks at 31104000 time
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-named Ultimate power over time
	-picture : http://i.imgur.com/LLxDPlr.png


	*eggUpgrade1
	-"Manual code writing is 50% more efficient. <br><i>With this unstable gem, we can increase the power of our clicking. It's pretty good.</i>
	-costs 1 eggGem
	-named Click Corruption
	-unlocks at 1 overtake10
	-multiplies efficiency of writeCode by 150%
	-picture : http://i.imgur.com/yHBV3cR.png
	*eggUpgrade2
	-"Game producers are 8 times as efficient. <br><i>With these unstable gems, we can cause the game producers to become unstable and produce more code.</i>
	-costs 2 eggGem
	-named Game Producer Corruption
	-unlocks at 1 overtake10
	-multiplies efficiency of gameProducer by 800%
	-picture : http://i.imgur.com/9XbMwxz.png
	*eggUpgrade3
	-"Positive reviewers are 8 times as efficient. <br><i>These unstable gems can also be used to make the positive reviewers unstable, causing them to give out positive reviews like mad.</i>
	-costs 2 eggGem
	-named Positive Reviewer Corruption
	-unlocks at 1 overtake10
	-multiplies efficiency of highReviewer by 800%
	-picture : http://i.imgur.com/Efcgp4R.png
	*eggUpgrade4
	-"Everything is more efficient for each bonus. <br><i>Corrupt the bonus generators. This'll give us a great advantage. Great idea.</i>
	-costs 4 eggGem
	-named Bonus Corruption
	-unlocks at 1 overtake10
	-multiplies efficiency of writeCode by 0.05% per bonus
	-multiplies efficiency of codeWriter by 3% per bonus
	-multiplies efficiency of object by 2% per bonus
	-multiplies efficiency of enemy by 2% per bonus
	-multiplies efficiency of player by 2% per bonus
	-multiplies efficiency of level by 1% per bonus
	-multiplies efficiency of game by 1% per bonus
	-multiplies efficiency of fanbase by 1% per bonus
	-multiplies efficiency of forum by 1% per bonus
	-multiplies efficiency of advertise by 0.6% per bonus
	-multiplies efficiency of highReviewer by 0.6% per bonus
	-multiplies efficiency of studio by 0.6% per bonus
	-multiplies efficiency of magic by 0.6% per bonus
	-multiplies efficiency of gameSeries by 0.3% per bonus
	-multiplies efficiency of popularYoutuber by 0.3% per bonus
	-multiplies efficiency of maganiumGenerator by 0.2% per bonus
	-multiplies efficiency of finality by 0.2% per bonus
	-multiplies efficiency of magicPointBuilding by 1% per bonus
	-picture : http://i.imgur.com/0FlgNnK.png
	*eggUpgrade5
	-"All corruptions are more powerful. <br><i>These unstable gems have the power to corrupt the world. We'll use them to the maximum possible without destroying or corrupting the world. This is the last one. We won't be using any more unstable gems after this.</i>
	-costs 8 eggGem
	-named Power Corruption
	-unlocks at 1 overtake10, 9 resets
	-multiplies efficiency of writeCode by 150%
	-multiplies efficiency of gameProducer by 200%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of writeCode by 0.05% per bonus
	-multiplies efficiency of codeWriter by 3% per bonus
	-multiplies efficiency of object by 2% per bonus
	-multiplies efficiency of enemy by 2% per bonus
	-multiplies efficiency of player by 2% per bonus
	-multiplies efficiency of level by 1% per bonus
	-multiplies efficiency of game by 1% per bonus
	-multiplies efficiency of fanbase by 1% per bonus
	-multiplies efficiency of forum by 1% per bonus
	-multiplies efficiency of advertise by 0.6% per bonus
	-multiplies efficiency of highReviewer by 0.6% per bonus
	-multiplies efficiency of studio by 0.6% per bonus
	-multiplies efficiency of magic by 0.6% per bonus
	-multiplies efficiency of gameSeries by 0.3% per bonus
	-multiplies efficiency of popularYoutuber by 0.3% per bonus
	-multiplies efficiency of maganiumGenerator by 0.2% per bonus
	-multiplies efficiency of finality by 0.2% per bonus
	-multiplies efficiency of magicPointBuilding by 1% per bonus
	-picture : http://i.imgur.com/NCftRDZ.png
	*gameConvert
	-"Unlocks the ability to convert games into code. <br><i>Too many games? No problem!</i>
	-costs 100 game2
	-unlocks at 1 game
	-unlocks convertGame1
	-unlocks convertGame2
	-unlocks convertGame3
	-unlocks convertGame4
	-unlocks convertGame5
	-named Game Conversion
	-unlocks gameConvert2
	-picture : http://i.imgur.com/5wnMU6r.png
	*gameConvert2
	-"Unlocks more conversion options. Conversion rate is doubled. <br><i>converting up pls buff</i>
	-costs 1000 game2
	-requires 50 game
	-locks convertGame1
	-locks convertGame2
	-locks convertGame3
	-locks convertGame4
	-locks convertGame5
	-unlocks convertGame6
	-unlocks convertGame7
	-unlocks convertGame8
	-unlocks convertGame9
	-unlocks convertGame10
	-unlocks convertGame11
	-unlocks convertGame12
	-unlocks gameConvert3
	-named Advanced Game Conversion
	-picture : http://i.imgur.com/KHMUutT.png
	*gameConvert3
	-"Unlocks game producers. <br><i>Helping you make a lot more games. </i>
	-costs 10000 game2
	-requires 100 game
	-unlocks gameProducer
	-unlocks gameConvert4
	-named Game Producers
	-picture : http://i.imgur.com/M7CT5pJ.png
	*gameConvert4
	-"Unlocks even more game conversion options. Game conversion is five times as efficient. <br><i>conversion still up pls buff agan </i>
	-costs 100000000 game2
	-requires 100 gameProducer
	-locks convertGame6
	-locks convertGame7
	-locks convertGame8
	-locks convertGame9
	-locks convertGame10
	-locks convertGame11
	-locks convertGame12
	-unlocks convertGame13
	-unlocks convertGame14
	-unlocks convertGame15
	-unlocks convertGame16
	-unlocks convertGame17
	-unlocks convertGame18
	-unlocks convertGame19
	-unlocks convertGame20
	-unlocks convertGame21
	-unlocks gameConvert5
	-named Epic Conversions
	-picture : http://i.imgur.com/Mmq4iFS.png
	*gameConvert5
	-"Unlocks the ability to convert all games into code, at the rate of 1 game into 5,000,000 code.<br><i>y u no buff???</i>
	-costs 1000000000000 game2
	-unlocks at 250 gameProducer
	-requires 250 gameProducer
	-locks convertGame1
	-locks convertGame2
	-locks convertGame3
	-locks convertGame4
	-locks convertGame5
	-locks convertGame6
	-locks convertGame7
	-locks convertGame8
	-locks convertGame9
	-locks convertGame10
	-locks convertGame11
	-locks convertGame12
	-locks convertGame13
	-locks convertGame14
	-locks convertGame15
	-locks convertGame16
	-locks convertGame17
	-locks convertGame18
	-locks convertGame19
	-locks convertGame20
	-locks convertGame21
	-unlocks convertGame22
	-unlocks convertGame23
	-named Ultimate Conversions
	-picture : http://i.imgur.com/fROK9uy.png
	*gameConvert6
	-"Converting is <b>twice</b> as efficient.<br><i>We can power up our ultimate conversions for more code and stuff.</i>
	-costs 1000000000000000 game2
	-unlocks at 325 gameProducer
	-requires 325 gameProducer
	-locks convertGame22
	-locks convertGame23
	-unlocks convertGame24
	-unlocks convertGame25
	-named Boosted Ultimate Conversions
	-picture : http://i.imgur.com/5XHe60b.png
	*gameConvert7
	-"Converting is <b>twice</b> as efficient.<br><i>The ultimate conversions have achieved epicness. Meaning a lot of code from each game.</i>
	-costs 1000000000000000000 game2
	-unlocks at 400 gameProducer
	-requires 400 gameProducer
	-locks convertGame24
	-locks convertGame25
	-unlocks convertGame26
	-unlocks convertGame27
	-named Epic Ultimate Conversions
	-picture : http://i.imgur.com/l7aEKTb.png

	*everythingUpgrade1
	-"Everything is <b>0.005%</b> more efficient for each building.<br><i></i>
	-costs 1e+9 code
	-unlocks at 1 codeWriter, 1 object, 1 enemy, 1 player, 1 level, 1 game, 1 fanbase, 1 forum, 1 advertise, 1 studio
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-named Helpers
	-picture : http://i.imgur.com/8Tk44xT.png
	*everythingUpgrade2
	-"Everything is <b>0.005%</b> more efficient for each building.<br><i></i>
	-costs 1e+11 code
	-unlocks at 10 codeWriter, 10 object, 10 enemy, 10 player, 10 level, 10 game, 10 fanbase, 10 forum, 10 advertise, 10 studio
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-named Workers
	-picture : http://i.imgur.com/R2xhSvR.png
	*everythingUpgrade3
	-"Everything is <b>0.005%</b> more efficient for each building.<br><i></i>
	-costs 1e+13 code
	-unlocks at 20 codeWriter, 20 object, 20 enemy, 20 player, 20 level, 20 game, 20 fanbase, 20 forum, 20 advertise, 20 studio
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-named Dedicated Workers
	-picture : http://i.imgur.com/aufjvya.png
	*everythingUpgrade4
	-"Everything is <b>0.005%</b> more efficient for each building.<br><i></i>
	-costs 1e+16 code
	-unlocks at 40 codeWriter, 40 object, 40 enemy, 40 player, 40 level, 40 game, 40 fanbase, 40 forum, 40 advertise, 40 studio, 40 magic
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-named Engineers
	-picture : http://i.imgur.com/LXayqUf.png
	*everythingUpgrade5
	-"Everything is <b>0.005%</b> more efficient for each building.<br><i></i>
	-costs 1e+19 code
	-unlocks at 80 codeWriter, 80 object, 80 enemy, 80 player, 80 level, 80 game, 80 fanbase, 80 forum, 80 advertise, 80 studio, 80 magic, 80 gameSeries
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-named Dedicated Engineers
	-picture : http://i.imgur.com/6gVWBRU.png
	*everythingUpgrade6
	-"Everything is <b>0.005%</b> more efficient for each building.<br><i></i>
	-costs 1e+22 code
	-unlocks at 100 codeWriter, 100 object, 100 enemy, 100 player, 100 level, 100 game, 100 fanbase, 100 forum, 100 advertise, 100 studio, 100 magic, 100 gameSeries, 100 maganiumGenerator, 100 magicPointBuilding
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-named Experienced Engineers
	-picture : http://i.imgur.com/eLSZsdD.png
	*everythingUpgrade7
	-"Everything is <b>0.005%</b> more efficient for each building.<br><i></i>
	-costs 1e+25 code
	-unlocks at 150 codeWriter, 150 object, 150 enemy, 150 player, 150 level, 150 game, 150 fanbase, 150 forum, 150 advertise, 150 studio, 150 magic, 150 gameSeries, 150 maganiumGenerator, 150 magicPointBuilding, 150 popularYoutuber
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-named Architects
	-picture : http://i.imgur.com/N6IIVMr.png
	*everythingUpgrade8
	-"Everything is <b>0.005%</b> more efficient for each building.<br><i></i>
	-costs 1e+28 code
	-unlocks at 200 codeWriter, 200 object, 200 enemy, 200 player, 200 level, 200 game, 200 fanbase, 200 forum, 200 advertise, 200 studio, 200 magic, 200 gameSeries, 200 maganiumGenerator, 200 magicPointBuilding, 200 popularYoutuber, 200 finality
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-named Dedicated Architects
	-picture : http://i.imgur.com/ygzYeg4.png
	*everythingUpgrade9
	-"Everything is <b>0.005%</b> more efficient for each building.<br><i></i>
	-costs 1e+30 code
	-unlocks at 250 codeWriter, 250 object, 250 enemy, 250 player, 250 level, 250 game, 250 fanbase, 250 forum, 250 advertise, 250 studio, 250 magic, 250 gameSeries, 250 maganiumGenerator, 250 magicPointBuilding, 250 popularYoutuber, 250 finality
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-named Experienced Architects
	-picture : http://i.imgur.com/Z7ob1lw.png
	*everythingUpgrade10
	-"Everything is <b>0.005%</b> more efficient for each building.<br><i></i>
	-costs 1e+32 code
	-unlocks at 300 codeWriter, 300 object, 300 enemy, 300 player, 300 level, 300 game, 300 fanbase, 300 forum, 300 advertise, 300 studio, 300 magic, 300 gameSeries, 300 maganiumGenerator, 300 magicPointBuilding, 300 popularYoutuber, 300 finality
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-named Architect Masters
	-picture : http://i.imgur.com/CML1yuO.png
	*everythingUpgrade11
	-"Everything is <b>0.005%</b> more efficient for each building.<br><i></i>
	-costs 1e+34 code
	-unlocks at 350 codeWriter, 350 object, 350 enemy, 350 player, 350 level, 350 game, 350 fanbase, 350 forum, 350 advertise, 350 studio, 350 magic, 350 gameSeries, 350 maganiumGenerator, 350 magicPointBuilding, 350 popularYoutuber, 350 finality
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-named Managers
	-picture : http://i.imgur.com/aAIbpDR.png
	*everythingUpgrade12
	-"Everything is <b>0.005%</b> more efficient for each building.<br><i></i>
	-costs 1e+36 code
	-unlocks at 400 codeWriter, 400 object, 400 enemy, 400 player, 400 level, 400 game, 400 fanbase, 400 forum, 400 advertise, 400 studio, 400 magic, 400 gameSeries, 400 maganiumGenerator, 400 magicPointBuilding, 400 popularYoutuber, 400 finality
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-named Experienced Managers
	-picture : http://i.imgur.com/PxFf9nF.png
	*everythingUpgrade13
	-"Everything is <b>0.005%</b> more efficient for each building.<br><i></i>
	-costs 1e+38 code
	-unlocks at 450 codeWriter, 450 object, 450 enemy, 450 player, 450 level, 450 game, 450 fanbase, 450 forum, 450 advertise, 450 studio, 450 magic, 450 gameSeries, 450 maganiumGenerator, 450 magicPointBuilding, 450 popularYoutuber, 450 finality
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-named Magically Enhanced Managers
	-picture : http://i.imgur.com/j3tNsPW.png
	*everythingUpgrade14
	-"Everything is <b>0.005%</b> more efficient for each building.<br><i></i>
	-costs 1e+40 code
	-unlocks at 500 codeWriter, 500 object, 500 enemy, 500 player, 500 level, 500 game, 500 fanbase, 500 forum, 500 advertise, 500 studio, 500 magic, 500 gameSeries, 500 maganiumGenerator, 500 magicPointBuilding, 500 popularYoutuber, 500 finality
	-multiplies efficiency of writeCode by 0.005% per buildings
	-multiplies efficiency of codeWriter by 0.005% per buildings
	-multiplies efficiency of object by 0.005% per buildings
	-multiplies efficiency of enemy by 0.005% per buildings
	-multiplies efficiency of player by 0.005% per buildings
	-multiplies efficiency of level by 0.005% per buildings
	-multiplies efficiency of game by 0.005% per buildings
	-multiplies efficiency of fanbase by 0.005% per buildings
	-multiplies efficiency of forum by 0.005% per buildings
	-multiplies efficiency of advertise by 0.005% per buildings
	-multiplies efficiency of highReviewer by 0.005% per buildings
	-multiplies efficiency of studio by 0.005% per buildings
	-multiplies efficiency of magic by 0.005% per buildings
	-multiplies efficiency of gameSeries by 0.005% per buildings
	-multiplies efficiency of popularYoutuber by 0.005% per buildings
	-multiplies efficiency of maganiumGenerator by 0.005% per buildings
	-multiplies efficiency of finality by 0.005% per buildings
	-multiplies efficiency of magicPointBuilding by 0.005% per buildings
	-named Project Leaders
	-picture : http://i.imgur.com/agtoDM0.png

	*manualUpgrade1
	-"Manual writing writes twice times as much code.<br><i>You found an IDE to help with your coding.</i>
	-costs 10101 code
	-unlocks at 1010 manualWritten
	-multiplies efficiency of writeCode by 200%
	-named IDE
	-picture : http://i.imgur.com/l2eh2M0.png
	*manualUpgrade2
	-"Manual writing writes twice as much code.<br><i>This program is very good for when you want to write code.</i>
	-costs 1010101 code
	-unlocks at 101010 manualWritten
	-multiplies efficiency of writeCode by 200%
	-named Notepad++
	-picture : http://i.imgur.com/lH2Tqem.png
	*manualUpgrade3
	-"Manual writing writes 1.5 times as much code.<br><i>MORE PROGRAMS! MORE PROGRAMS!</i>
	-costs 101010101 code
	-unlocks at 10101010 manualWritten
	-multiplies efficiency of writeCode by 150%
	-named Sublime Text
	-picture : http://i.imgur.com/m68CvMa.png
	*manualUpgrade4
	-"Manual writing writes 1.5 times as much code.<br><i>You now get your ideas for game features faster.</i>
	-costs 10101010101 code
	-unlocks at 1010101010 manualWritten
	-multiplies efficiency of writeCode by 150%
	-named Faster Ideas
	-picture : http://i.imgur.com/qXf9Zx5.png
	*manualUpgrade5
	-"Manual writing writes 1.5 times as much code.<br><i>Are you sure it's safe? Well... it boosts your ability to write code...<br><br>Developer Bakanium was seen taking large quantities of this substance four hours ago.</i>
	-costs 1010101010101 code
	-unlocks at 101010101010 manualWritten
	-multiplies efficiency of writeCode by 150%
	-named Strange substance
	-picture : http://i.imgur.com/8qnm0Yd.png
	*manualUpgrade6
	-"Manual writing writes 1.5 times as much code.<br><i>This is the perfect program. Unfortunately, it's a gigantic secret, but I finally found it! And I'm not telling anyone else, because I'm a troll!<br><br>Developer Bakanium, STOP putting this in the recycle bin.</i>
	-costs 101010101010101 code
	-unlocks at 10101010101010 manualWritten
	-multiplies efficiency of writeCode by 150%
	-named [REDACTED]
	-picture : http://i.imgur.com/n7JjUTs.png
	*manualUpgrade7
	-"Manual writing writes 1.4 times as much code.<br><i>I don't know what it does, but it sure was expensive. I think just the morale boost from it will largely increase my writing speed.</i>
	-costs 10101010101010101 code
	-unlocks at 1010101010101010 manualWritten
	-multiplies efficiency of writeCode by 140%
	-named Special Keyboard
	-picture : http://i.imgur.com/fu2JYTN.png
	*manualUpgrade8
	-"Manual writing writes 1.3 times as much code.<br><i>These work here too.</i>
	-costs 1010101010101010101 code
	-unlocks at 101010101010101010 manualWritten
	-multiplies efficiency of writeCode by 130%
	-named Bionic Hands
	-picture : http://i.imgur.com/L7SkQn7.png
	*manualUpgrade9
	-"Manual writing writes 1.3 times as much code.<br><i>It's going to be tough to adapt to this, but it's certainly going to be useful.</i>
	-costs 101010101010101010101 code
	-unlocks at 10101010101010101010 manualWritten
	-multiplies efficiency of writeCode by 130%
	-named Extra fingers
	-picture : http://i.imgur.com/53vHc4l.png
	*manualUpgrade10
	-"Manual writing writes 1.2 times as much code.<br><i>Are you kidding me?</i>
	-costs 10101010101010101010101 code
	-unlocks at 1010101010101010101010 manualWritten
	-multiplies efficiency of writeCode by 120%
	-named Extra Arms
	-picture : http://i.imgur.com/Pzl1TD1.png
	*manualUpgrade11
	-"Manual writing writes 1.4 times as much code.<br><i>Well, it certainly increases my speed.</i>
	-costs 1010101010101010101010101 code
	-unlocks at 101010101010101010101010 manualWritten
	-multiplies efficiency of writeCode by 140%
	-named Brain Enhancement
	-picture : http://i.imgur.com/6VQslWd.png
	*manualUpgrade12
	-"Manual writing writes 1.6 times as much code.<br><i>Writing games in mere seconds.</i>
	-costs 101010101010101010101010101 code
	-unlocks at 10101010101010101010101010 manualWritten
	-multiplies efficiency of writeCode by 160%
	-named Epic Enhancement
	-picture : http://i.imgur.com/dajUAc5.png
	*manualUpgrade13
	-"Manual writing writes 1.8 times as much code.<br><i>You're turning into a writing god. Thins is the first stage.</i>
	-costs 10101010101010101010101010101 code
	-unlocks at 1010101010101010101010101010 manualWritten
	-multiplies efficiency of writeCode by 180%
	-named Godly Enhancement
	-picture : http://i.imgur.com/GHvllQv.png
	*manualUpgrade14
	-"Manual writing writes twice as much code.<br><i>The last stage of turning into a writing god.</i>
	-costs 1010101010101010101010101010101 code
	-unlocks at 101010101010101010101010101010 manualWritten
	-multiplies efficiency of writeCode by 200%
	-named Ultimate Enhancement
	-picture : http://i.imgur.com/o72qTcr.png
	*manualResearch1
	-"Manual research is <b>twice</b> as efficient. <br><i>Increasing the efficiency of research is a good idea.</i>
	-costs 6161616161616 code
	-unlocks at 100 manualResearch
	-multiplies efficiency of speedResearch by 200%
	-multiplies efficiency of speedResearch2 by 200%
	-multiplies efficiency of speedResearch3 by 200%
	-multiplies efficiency of speedResearch4 by 200%
	-named Efficient Researching
	-picture : http://i.imgur.com/GS3JNtZ.png
	*manualResearch2
	-"Manual research is <b>50%</b> more efficient. <br><i>You now get special lessons from the experienced researchers to help you research very efficiently.</i>
	-costs 616161616161616 code
	-unlocks at 1000 manualResearch
	-multiplies efficiency of speedResearch by 150%
	-multiplies efficiency of speedResearch2 by 150%
	-multiplies efficiency of speedResearch3 by 150%
	-multiplies efficiency of speedResearch4 by 150%
	-named Special Lessons
	-picture : http://i.imgur.com/GS3JNtZ.png
	*manualResearch3
	-"Manual research is <b>30%</b> more efficient. <br><i>The wizards themselves now teach you how to research faster.</i>
	-costs 61616161616161616 code
	-unlocks at 10000 manualResearch
	-multiplies efficiency of speedResearch by 130%
	-multiplies efficiency of speedResearch2 by 130%
	-multiplies efficiency of speedResearch3 by 130%
	-multiplies efficiency of speedResearch4 by 130%
	-named Wizard Lessons
	-picture : http://i.imgur.com/GS3JNtZ.png
	*manualResearch35
	-"Manual research is <b>30%</b> more efficient. <br><i>The wizards have allowed you to cast magic spells. These spells greatly boost research.</i>
	-costs 6161616161616161616 code
	-unlocks at 100000 manualResearch
	-multiplies efficiency of speedResearch by 130%
	-multiplies efficiency of speedResearch2 by 130%
	-multiplies efficiency of speedResearch3 by 130%
	-multiplies efficiency of speedResearch4 by 130%
	-named Special Wizard Lessons
	-picture : http://i.imgur.com/GS3JNtZ.png
	*manualResearch4
	-"Manual research is <b>30%</b> more efficient. <br><i>The wizards have allowed you to cast ultra-magic spells. These spells boost research further.</i>
	-costs 6161616161616161616 code
	-unlocks at 1000000 manualResearch
	-multiplies efficiency of speedResearch by 130%
	-multiplies efficiency of speedResearch2 by 130%
	-multiplies efficiency of speedResearch3 by 130%
	-multiplies efficiency of speedResearch4 by 130%
	-named Ultra-magic Wizard Lessons
	-picture : http://i.imgur.com/GS3JNtZ.png
	*click1
	-"Manual writing is 0.6% more efficient for each object.<br><i>You can now write objects that write code for you.</i>
	-costs 1 positiveReview
	-unlocks at 64 object
	-multiplies efficiency of writeCode by 0.6% per object
	-named Objects that write
	-picture : http://i.imgur.com/wJmuYFc.png
	*click2
	-"Manual writing is 0.55% more efficient for each enemy.<br><i>Special tamable enemies that can write for you as well!</i>
	-costs 3 positiveReview
	-unlocks at 64 enemy
	-multiplies efficiency of writeCode by 0.55% per enemy
	-named Tamed enemies
	-picture : http://i.imgur.com/BJd7hcH.png
	*click3
	-"Manual writing is 0.5% more efficient for each player.<br><i>We can hire players, and they can write for you too!</i>
	-costs 10 positiveReview
	-unlocks at 64 player
	-multiplies efficiency of writeCode by 0.5% per player
	-named Hired players
	-picture : http://i.imgur.com/kVGfl4S.png
	*click4
	-"Manual writing is 0.5% more efficient for each level.<br><i>How about we just take everything from the level and get it to help you write more code?</i>
	-costs 20 positiveReview
	-unlocks at 64 level
	-multiplies efficiency of writeCode by 0.5% per level
	-named Stuff from levels
	-picture : http://i.imgur.com/8yR8kgQ.png
	*click5
	-"Manual writing is 0.5% more efficient for each game.<br><i>Scratch that. Take everything from the whole game and let that help you write!</i>
	-costs 100 positiveReview
	-unlocks at 64 game
	-multiplies efficiency of writeCode by 0.5% per game
	-named Stuff from games
	-picture : http://i.imgur.com/5wnMU6r.png
	*click6
	-"Manual writing is 0.4% more efficient for each fanbase.<br><i>We can get our fanbases to help you write code.</i>
	-costs 600 positiveReview
	-unlocks at 64 fanbase
	-multiplies efficiency of writeCode by 0.4% per fanbase
	-named Fanbase Helpers
	-picture : http://i.imgur.com/RgI2bKx.png
	*click7
	-"Manual writing is 0.4% more efficient for each forum.<br><i>Let's get all the good guys from the forums, and get them to help and encourage you to write.</i>
	-costs 5000 positiveReview
	-unlocks at 64 forum
	-multiplies efficiency of writeCode by 0.4% per forum
	-named Forum Helpers
	-picture : http://i.imgur.com/2mkVLkh.png
	*click8
	-"Manual writing is 0.3% more efficient for each advertisement.<br><i>The advertisements encourage you to write more code... somehow.</i>
	-costs 25000 positiveReview
	-unlocks at 64 advertise
	-multiplies efficiency of writeCode by 0.4% per advertise
	-named Encouraging advertisements
	-picture : http://i.imgur.com/G3xMef4.png
	*click9
	-"Manual writing is 0.4% more efficient for each studio.<br><i>The studios team up with you and help you write faster than a menner.</i>
	-costs 50000 positiveReview
	-unlocks at 64 studio
	-requires 1 fastMenResearch
	-unlocks click10
	-multiplies efficiency of writeCode by 0.4% per studio
	-named Studio Team Up
	-picture : http://i.imgur.com/cTTotVI.png
	*click10
	-"Manual writing is slightly more efficient for everything else.<br><i>Everything else is boosting you now as well. This is giving you a great boost.</i>
	-costs 1000000 positiveReview
	-multiplies efficiency of writeCode by 0.20% per gameProducer
	-multiplies efficiency of writeCode by 0.20% per highReviewer
	-multiplies efficiency of writeCode by 0.20% per magic
	-multiplies efficiency of writeCode by 0.21% per gameSeries
	-multiplies efficiency of writeCode by 0.16% per popularYoutuber
	-multiplies efficiency of writeCode by 0.20% per bonus
	-multiplies efficiency of writeCode by 0.21% per maganiumGenerator
	-multiplies efficiency of writeCode by 0.15% per finality
	-multiplies efficiency of writeCode by 0.10% per magicPointBuilding
	-named Team Up with Everything
	-picture : http://i.imgur.com/4n7fOoc.png
	*overtakeCrap1
	-"Code writers are <b>10%</b> more efficient for each game series overtaken. <br><i>If we overtake game series, our code writers can gain morale.</i>
	-costs 2 positiveReview
	-named Code Writer Morale
	-unlocks at 128 codeWriter
	-multiplies efficiency of codeWriter by 10% per popularity
	-picture : http://i.imgur.com/v3UN7Rk.png
	*overtakeCrap2
	-"Objects are <b>10%</b> more efficient for each game series overtaken. <br><i>We found strange boost things underground that boost things the more game series we overtake.</i>
	-costs 10 positiveReview
	-named Object boost type A
	-unlocks at 128 object
	-multiplies efficiency of object by 10% per popularity
	-picture : http://i.imgur.com/wJmuYFc.png
	*overtakeCrap3
	-"Enemies are <b>10%</b> more efficient for each game series overtaken. <br><i></i>
	-costs 40 positiveReview
	-named Enemy boost type A
	-unlocks at 128 enemy
	-multiplies efficiency of enemy by 10% per popularity
	-picture : http://i.imgur.com/BJd7hcH.png
	*overtakeCrap4
	-"Players are <b>10%</b> more efficient for each game series overtaken. <br><i></i>
	-costs 200 positiveReview
	-named Player boost type A
	-unlocks at 128 player
	-multiplies efficiency of player by 10% per popularity
	-picture : http://i.imgur.com/kVGfl4S.png
	*overtakeCrap5
	-"Levels are <b>10%</b> more efficient for each game series overtaken. <br><i></i>
	-costs 1000 positiveReview
	-named Level boost type A
	-unlocks at 128 level
	-multiplies efficiency of level by 10% per popularity
	-picture : http://i.imgur.com/8yR8kgQ.png
	*overtakeCrap6
	-"Games are <b>10%</b> more efficient for each game series overtaken. <br><i>Our games are starting to have a cultural influence. The more game series we evertake, the more powerful this effect is.</i>
	-costs 6000 positiveReview
	-named Culturally influencing games
	-unlocks at 128 game
	-multiplies efficiency of game by 10% per popularity
	-picture : http://i.imgur.com/5wnMU6r.png
	*overtakeCrap7
	-"Fanbases are <b>10%</b> more efficient for each game series overtaken. <br><i>The fanbases also become more popular when you overtake a game series.</i>
	-costs 30000 positiveReview
	-named Fanbase rising
	-unlocks at 128 fanbase
	-multiplies efficiency of fanbase by 10% per popularity
	-picture : http://i.imgur.com/RgI2bKx.png
	*overtakeCrap8
	-"Forums are <b>10%</b> more efficient for each game series overtaken. <br><i>Ditto with the forums.</i>
	-costs 150000 positiveReview
	-named Forum rising
	-unlocks at 128 forum
	-multiplies efficiency of forum by 10% per popularity
	-picture : http://i.imgur.com/2mkVLkh.png
	*overtakeCrap9
	-"Advertisements are <b>10%</b> more efficient for each game series overtaken. <br><i>As your games become more popular, the percentage of ads that are for your games gets larger and larger.</i>
	-costs 1000000 positiveReview
	-named Advertisement takeover
	-unlocks at 128 advertise
	-multiplies efficiency of advertise by 10% per popularity
	-picture : http://i.imgur.com/G3xMef4.png
	*overtakeCrap10
	-"Game studios are <b>10%</b> more efficient for each game series overtaken. <br><i>The studios gain morale as well.</i>
	-costs 5000000 positiveReview
	-named Studio Morale
	-unlocks at 128 studio
	-multiplies efficiency of studio by 10% per popularity
	-picture : http://i.imgur.com/cTTotVI.png
	*overtakeCrap11
	-"Magic code writers are <b>10%</b> more efficient for each game series overtaken. <br><i>omg cant burthcookie be a bit more creative?!?</i>
	-costs 25000000 positiveReview
	-named Magic Code Writer Morale
	-unlocks at 128 magic
	-multiplies efficiency of magic by 10% per popularity
	-picture : http://i.imgur.com/SF8q1Sj.png
	*overtakeCrap12
	-"Game series are <b>10%</b> more efficient for each game series overtaken. <br><i>The games have an influence on culture, but why not game series? Fixed.</i>
	-costs 125000000 positiveReview
	-named Game series cultural influence
	-unlocks at 128 gameSeries
	-multiplies efficiency of gameSeries by 10% per popularity
	-picture : http://i.imgur.com/5mBFGVY.png
	*overtakeCrap13
	-"Ultra-magic generators are <b>10%</b> more efficient for each game series overtaken. <br><i>We have been finding better ultra-magic ever since we kicked that game series' ass!</i>
	-costs 3125000000 positiveReview
	-named Ultra-magic boost
	-unlocks at 128 maganiumGenerator
	-multiplies efficiency of maganiumGenerator by 10% per popularity
	-picture : http://i.imgur.com/lZnr4yP.png
	*overtakeCrap14
	-"Popular YouTubers are <b>10%</b> more efficient for each game series overtaken. <br><i>The popular YouTubers that play your games now have more subs than all the others.</i>
	-costs 15625000000 positiveReview
	-named Popular Youtuber rising
	-unlocks at 128 popularYoutuber
	-multiplies efficiency of popularYoutuber by 10% per popularity
	-picture : http://i.imgur.com/FFxM1vH.png
	*overtakeCrap15
	-"Finalities are <b>10%</b> more efficient for each game series overtaken. <br><i>Your secret organisation grows... and it is slowly destroying minor game series.</i>
	-costs 85000000000 positiveReview
	-named Secret Organisation Growth
	-unlocks at 128 finality
	-multiplies efficiency of finality by 10% per popularity
	-picture : http://i.imgur.com/zAJHtxm.png
	*overtakeCrap16
	-"Magic point converters are <b>10%</b> more efficient for each game series overtaken. <br><i>As the maintainers got a morale boost, the maintenance is better.</i>
	-costs 35625000000 positiveReview
	-named Better maintenance
	-unlocks at 128 magicPointBuilding
	-multiplies efficiency of magicPointBuilding by 10% per popularity
	-picture : http://i.imgur.com/jFbU9zq.png
	*writerAndManualUpgrade1
	-"Manual writing is 4% more efficient for each writer. Code writers are twice as efficient. <br><i>The code writers help you write code faster.</i>
	-costs 10000 code
	-unlocks at 40 codeWriter
	-multiplies efficiency of writeCode by 4% per codeWriter
	-multiplies efficiency of codeWriter by 200%
	-named Coder Helpers
	-picture : http://i.imgur.com/EmZMOhw.png
	*writerAndManualUpgrade2
	-"Manual writing is 3% more efficient for each object. Code writers are twice as efficient.<br><i>Code writers are now teaming up to produce an object that can be brought into the real world, that can be used to boost your performance. The more objects there are, the more objects they will be able to create to boost you.</i>
	-costs 10000000 code
	-unlocks at 100 codeWriter
	-requires 90 object
	-multiplies efficiency of writeCode by 3% per object
	-multiplies efficiency of codeWriter by 200%
	-named Real Life Powerups
	-picture : http://i.imgur.com/uD8n20F.png
	*writerAndManualUpgrade3
	-"Manual writing is 2% more efficient for each object. Code writers are twice as efficient.<br><i>The code writers enhanced the players so that they could boost you, and also so that they could be brought into the real world.<br><br>"They should really make me a character." ~Developer Bakanium</i>
	-costs 10000000000 code
	-unlocks at 150 codeWriter
	-requires 100 player
	-multiplies efficiency of writeCode by 2% per player
	-multiplies efficiency of codeWriter by 200%
	-named Player Helpers
	-picture : http://i.imgur.com/JJEmNy6.png
	*writerAndManualUpgrade4
	-"Manual writing is 1% more efficient for each writer. Code writers are twice as efficient.<br><i>The code writers give you their sentient keyboards, helping you write code even faster, like a menner.</i>
	-costs 10000000000000 code
	-unlocks at 200 codeWriter
	-requires 1 fastMenResearch
	-multiplies efficiency of writeCode by 1% per codeWriter
	-multiplies efficiency of codeWriter by 200%
	-named Sentient Keyboard Donation
	-picture : http://i.imgur.com/BWJBzES.png
	*writerAndManualUpgrade5
	-"Manual writing is 0.5% more efficient for each magic code writer. Magic code writers are twice as efficient.<br><i>We got the wizards to give you a great boost. Every wizard there is casts a spell on you to make you more powerful. </i>
	-costs 1e+20 code
	-requires 120 magic
	-unlocks at 400 codeWriter
	-multiplies efficiency of writeCode by 0.5% per codeWriter
	-multiplies efficiency of magic by 200%
	-named Wizard Enhancements
	-picture : http://i.imgur.com/TK1xf5v.png
	*writerAndManualUpgrade6
	-"Manual writing is 0.2% more efficient for each writer. <br><i>Should the code writers, after being enhanced with ultra-magic, all join together to power you up, you would become a lot more powerful.</i>
	-costs 1e+24 code
	-unlocks at 500 codeWriter
	-requires 200 maganiumGenerator
	-multiplies efficiency of writeCode by 0.2% per codeWriter
	-named The Ultimate Code Writer Boost
	-picture : http://i.imgur.com/Jw22fY0.png
	*writerUpgrade1
        -"Manual writing writes <b>1 more</b> code.<br>Code writers write <b>20%</b> more code.<br><i>Less time wasted correcting typos.</i>"
        -costs 120 code
        -unlocks at 1 codeWriter
        -multiplies efficiency of writeCode by 200%
        -multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of magic by 1% per orb
	-multiplies efficiency of maganiumGenerator by 5% per magicCore
        -named Typo reduction
	-picture : http://i.imgur.com/v3UN7Rk.png
        *writerUpgrade2
        -"Code writers write <b>50%</b> more code. Manual writing writes <b>50%</b> more code.<i>They were typing really slowly before these lessons.</i>"
        -costs 500 code
        -unlocks at 10 codeWriter
        -multiplies efficiency of codeWriter by 200%
        -multiplies efficiency of writeCode by 150%
        -named Typing lessons
	-picture : http://i.imgur.com/rEGTZV6.png
        *writerUpgrade3
        -"Writers and manual writing write <b>twice</b> as much code.<br><i>Copy-pasting allows them to not have to write out the same line several times.</i>"
        -costs 12500 code
        -unlocks at 20 codeWriter
        -multiplies efficiency of codeWriter by 200%
        -multiplies efficiency of writeCode by 200%
        -named Copy-pasting
	-picture : http://i.imgur.com/ZIQ1nUp.png
        *writerUpgrade4
        -"Writers and manual writing write <b>twice</b> as much code.<br><i>The previous code writers were noobs, se we fired them and got new ones.</i>"
        -costs 130000 code
        -unlocks at 40 codeWriter
        -multiplies efficiency of codeWriter by 200%
        -multiplies efficiency of writeCode by 200%
        -named Expert coders
	-picture : http://i.imgur.com/9ax6pn4.png
        *writerUpgrade5
        -"Writers and manual writing write <b>twice</b> as much code.<br><i>Teamwork. Now the writers are even faster.</i>"
        -costs 1400000 code
        -unlocks at 80 codeWriter
        -multiplies efficiency of codeWriter by 200%
        -multiplies efficiency of writeCode by 200%
        -named Teamwork
	-picture : http://i.imgur.com/hLIJzXq.png
        *writerUpgrade6
        -"Writers write <b>three times</b> as much code.<br>Manual writing writes <b>twice</b> as much code.<br><i>The computers kept crashing, so we installed software that stopped them crashing.</i>"
        -costs 30000000 code
        -unlocks at 100 codeWriter
        -multiplies efficiency of codeWriter by 300%
        -multiplies efficiency of writeCode by 200%
        -named Crash fix
	-picture : http://i.imgur.com/wsb2WtD.png
        *writerUpgrade7
        -"Writers write <b>three times</b> as much code.<br>Manual writing writes <b>twice</b> as much code.<br><i>Our code writers now have more energy, and now they take breaks less often.</i>"
        -costs 3200000000 code
        -unlocks at 150 codeWriter
        -multiplies efficiency of codeWriter by 300%
        -multiplies efficiency of writeCode by 200%
        -named Extra energy
	-picture : http://i.imgur.com/QD1JfQK.png
        *writerUpgrade8
        -"Writers and manual writing write <b>four times</b> as much code.<br><i>The keyboards are now sentient, and write code super-fast. They run out of battery often though.</i>"
        -costs 400000000000 code
        -unlocks at 200 codeWriter
        -multiplies efficiency of codeWriter by 400%
        -multiplies efficiency of writeCode by 400%
        -named Sentient keyboards
	-picture : http://i.imgur.com/Vnikuhh.png
        *writerUpgrade11
        -"Writers write <b>5 times</b> as much code. Manual writing writes <b>twice</b> as much code.<br><i>They write for you.</i>"
        -costs 100000000000000 code
        -unlocks at 250 codeWriter
        -multiplies efficiency of codeWriter by 500%
	-multiplies efficiency of writeCode by 200%
        -named Bionic hands
	-picture : http://i.imgur.com/KoDR9D7.png
        *writerUpgrade9
        -"Writers write <b>6 times</b> as much code.<br><i>Fewer battery replacements.</i>"
        -costs 5000000000000000 code
        -unlocks at 300 codeWriter
        -multiplies efficiency of codeWriter by 600%
        -named Long-life batteries
	-picture : http://i.imgur.com/OaEcSm8.png
 	*writerUpgrade12
        -"Writers write <b>8 times</b> as much code. Manual writing writes <b>twice</b> as much code.<br><i>2fast4me<br><br>"Why not a "Friendship is Magic" upgrade?" ~Developer Mlepfim</i>"
        -costs 720000000000000000 code
        -unlocks at 350 codeWriter
        -multiplies efficiency of codeWriter by 800%
	-multiplies efficiency of writeCode by 200%
        -named Bionic hand turbo charge
	-picture : http://i.imgur.com/4su0nNt.png
        *writerUpgrade10
        -"Writers write <b>10 times</b> as much code. Manual writing writes <b>twice</b> as much code.<br><i>An fast men to write a lot, lot of code.<br><br>"No. This is a really stupid running gag, and it doesn't deserve to be in any game." ~Developer Bakanium</i>"
        -costs 65000000000000000000 code
	-requires 1 fastMenResearch
        -unlocks at 400 codeWriter
        -multiplies efficiency of codeWriter by 1000%
	-multiplies efficiency of writeCode by 200%
        -named FASTER MENNER
	-picture : http://i.imgur.com/uwcdty9.png
        *writerUpgrade13
        -"Writers write <b>12 times</b> as much code. <br><i>Faster than a menner! Finally.</i>"
        -costs 6500000000000000000000 code
	-requires 1 fastMenResearch
        -unlocks at 450 codeWriter
        -multiplies efficiency of codeWriter by 1200%
        -named Faster than a menner
	-picture : http://i.imgur.com/Z5By3GV.png
        *writerUpgrade14
        -"Writers write <b>1%</b> more code for each code writer. <br><i></i>"
        -costs 1000000000000000000000000 code
        -unlocks at 500 codeWriter
        -multiplies efficiency of codeWriter by 1% per codeWriter
        -named Code Writer Ascension
	-picture : http://i.imgur.com/hp7GWjq.png
        *writerUpgrade15
        -"Writers write <b>1%</b> more code for each code writer. <br><i></i>"
        -costs 15000000000000000000000000000 code
        -unlocks at 600 codeWriter
        -multiplies efficiency of codeWriter by 1% per codeWriter
        -named Code Writer Ascension Type Alpha
	-picture : http://i.imgur.com/Qj2GIFc.png
        *writerUpgrade16
        -"Writers write <b>1%</b> more code for each code writer. <br><i></i>"
        -costs 225000000000000000000000000000000 code
        -unlocks at 700 codeWriter
        -multiplies efficiency of codeWriter by 1% per codeWriter
        -named Code Writer Ascension Type Beta
	-picture : http://i.imgur.com/jNsvB2a.png
        *writerUpgrade17
        -"Writers write <b>1%</b> more code for each code writer. <br><i></i>"
        -costs 4000000000000000000000000000000000000 code
        -unlocks at 800 codeWriter
        -multiplies efficiency of codeWriter by 0.5% per codeWriter
        -named Code Writer Ascension Type Gamma
	-picture : http://i.imgur.com/QrXkePs.png
      
	*objectUpgrade1
	-"Objects give <b>20%</b> more code. <br><i> A collectible for your game. Pick 100 of them up and... </i>"
	-costs 1000 code
	-unlocks at 1 object
	-multiplies efficiency of object by 120%
	-named Collectibles
	-picture : http://i.imgur.com/wJmuYFc.png
	*objectUpgrade2
	-"Objects give <b>50%</b> more code. <br><i> Powerups that boost your player. </i>"
	-costs 3000 code
	-unlocks at 10 object
	-multiplies efficiency of object by 150%
	-named Powerups
	-picture : http://i.imgur.com/4eQt0Xk.png
	*objectUpgrade3
	-"Objects give <b>twice</b> as much code. <br><i> Your objects were completely stationary before. Now your objects can move! </i>"
	-costs 10000 code
	-unlocks at 20 object
	-multiplies efficiency of object by 200%
	-named Moving objects
	-picture : http://i.imgur.com/pprEVjM.png
	*objectUpgrade4
	-"Objects give <b>twice</b> as much code. Levels give 10% more code. <br><i>Each level has a certain amount of these. Collect every single one of them and you get a reward.</i>"
	-costs 200000 code
	-unlocks at 40 object
	-multiplies efficiency of object by 200%
	-multiplies efficiency of level by 110%
	-named Level Collectibles
	-picture : http://i.imgur.com/5Q5hNcI.png
	*objectUpgrade5
	-"Objects give <b>twice</b> as much code. Enemies give 20% more code. <br><i> Sharp pointy things. Instant death.</i>"
	-costs 3000000 code
	-unlocks at 80 object
	-multiplies efficiency of object by 200%
	-named Spikes
	-picture : http://i.imgur.com/gCUkqc7.png
	*objectUpgrade6
	-"Objects give <b>2.5 times</b> as much code. Levels give 50% more code. <br><i> A nice way to finish your level. </i>"
	-costs 4000000 code
	-unlocks at 100 object
	-multiplies efficiency of object by 250%
	-multiplies efficiency of level by 150%
	-named Goals
	-picture : http://i.imgur.com/HnGxy2l.png
	*objectUpgrade7
	-"Objects give <b>3 times</b> as much code. <br><i> Some buildings to enter and exit. </i>"
	-costs 5000000000 code
	-unlocks at 150 object
	-multiplies efficiency of object by 300%
	-named Buildings
	-picture : http://i.imgur.com/GnbmWWc.png
	*objectUpgrade8
	-"Objects give <b>4 times</b> as much code. <br><i> EXTRA LIFE- Wait, what? </i>"
	-costs 800000000000 code
	-unlocks at 200 object
	-multiplies efficiency of object by 400%
	-named Disguised objects
	-picture : http://i.imgur.com/tbnjb1f.png
	*objectUpgrade11
	-"Objects give <b>5 times</b> as much code. <br><i>An object with multiple effects! </i>"
	-costs 200000000000000 code
	-unlocks at 250 object
	-multiplies efficiency of object by 450%
	-named Combined objects
	-picture : http://i.imgur.com/GbAOrz9.png
	*objectUpgrade9
	-"Objects give <b>5 times</b> as much code. <br><i>Now your objects have THREE DIMENSIONS! </i>"
	-costs 20000000000000000 code
	-unlocks at 300 object
	-multiplies efficiency of object by 500%
	-named 3D objects
	-picture : http://i.imgur.com/X0RfaIV.png
	*objectUpgrade12
	-"Objects give <b>6 times</b> as much code. <br><i>We finally managed to open up an infinite amount of possibilities. </i>"
	-costs 2000000000000000000 code
	-unlocks at 350 object
	-multiplies efficiency of object by 600%
	-named Infinite possibilities
	-picture : http://i.imgur.com/y0yL9XZ.png
	*objectUpgrade10
	-"Objects give <b>8 times</b> as much code.<br><i> Who needs just 3D when you can have objects in REAL-LIFE? </i>"
	-costs 1000000000000000000000 code
	-unlocks at 400 object
	-multiplies efficiency of object by 800%
	-named Real life objects
	-picture : http://i.imgur.com/FbO2UQ5.png
	*objectUpgrade13
	-"Objects give <b>12 times</b> as much code. <br><i> People used the bombs in your games in real life. Time to stop that happening. </i>"
	-costs 100000000000000000000000 code
	-unlocks at 450 object
	-multiplies efficiency of object by 1000%
	-named Inability to use dangerous objects in real life
	-picture : http://i.imgur.com/wnBBVcn.png
        *objectUpgrade14
        -"Objects write <b>1%</b> more code for each code object. <br><i>No objections to this.</i>"
        -costs 15000000000000000000000000 code
        -unlocks at 500 object
        -multiplies efficiency of object by 1% per object
        -named Object Ascension
	-picture : http://i.imgur.com/bEbIeeZ.png
        *objectUpgrade15
        -"Objects write <b>1%</b> more code for each code object. <br><i></i>"
        -costs 2250000000000000000000000000 code
        -unlocks at 600 object
        -multiplies efficiency of object by 1% per object
        -named Object Ascension Type Alpha
	-picture : http://i.imgur.com/4J8uDaA.png
        *objectUpgrade16
        -"Objects write <b>1%</b> more code for each code object. <br><i></i>"
        -costs 400000000000000000000000000000 code
        -unlocks at 700 object
        -multiplies efficiency of object by 1% per object
        -named Object Ascension Type Beta
	-picture : http://i.imgur.com/WpivUiF.png
        *objectUpgrade17
        -"Objects write <b>1%</b> more code for each code object. <br><i></i>"
        -costs 60000000000000000000000000000000 code
        -unlocks at 800 object
        -multiplies efficiency of object by 1% per object
        -named Object Ascension Type Gamma
	-picture : http://i.imgur.com/hJzJjAB.png
	*enemyUpgrade1
	-"Enemies give <b>20%</b> more code. <br><i> The enemies didn't have any AI at all before. Let's fix that. </i>"
	-costs 5000 code
	-unlocks at 1 enemy
	-multiplies efficiency of enemy by 120%
	-named Low-level AI
	-picture : http://i.imgur.com/BJd7hcH.png
	*enemyUpgrade2
	-"Enemies give <b>50%</b> more code. <br><i> Now enemies can have a special attack! </i>"
	-costs 15000 code
	-unlocks at 10 enemy
	-multiplies efficiency of enemy by 150%
	-named Special Attacks
	-picture : http://i.imgur.com/nQWCRsY.png
	*enemyUpgrade3
	-"Enemies give twice as much code. <br><i> You have to defeat them to get past. </i>"
	-costs 45000 code
	-unlocks at 20 enemy
	-multiplies efficiency of enemy by 200%
	-named Blockade enemies
	-picture : http://i.imgur.com/EVEvmsr.png
	*enemyUpgrade4
	-"Enemies give twice as much code. <br><i> Know those annoying little buggers that can't be killed? Well it's abut time we added them in. </i>"
	-costs 400000 code
	-unlocks at 40 enemy
	-multiplies efficiency of enemy by 200%
	-named Unkillable enemies
	-picture : http://i.imgur.com/wXGI9zH.png
	*enemyUpgrade5
	-"Enemies give twice as much code. <br><i> Say hello to my little friend. </i>"
	-costs 20000000 code
	-unlocks at 80 enemy
	-multiplies efficiency of enemy by 200%
	-named Tamable enemies
	-picture : http://i.imgur.com/qpxueYX.png
	*enemyUpgrade6
	-"Enemies give 2.5 times as much code. <br><i> Enemies have pretty damn good AI now that we added this. </i>"
	-costs 160000000 code
	-unlocks at 100 enemy
	-multiplies efficiency of enemy by 250%
	-named High-level AI
	-picture : http://i.imgur.com/MPDFv2A.png
	*enemyUpgrade7
	-"Enemies give three times as much code. <br><i> A boss randomly appears when you think you reached the end of the level. </i>"
	-costs 25000000000 code
	-unlocks at 150 enemy
	-multiplies efficiency of enemy by 300%
	-named Stage Bosses
	-picture : http://i.imgur.com/yyffRhv.png
	*enemyUpgrade8
	-"Enemies give four times as much code. <br><i>Customise your own enemies with the enemy editor! </i>"
	-costs 5000000000000 code
	-unlocks at 200 enemy
	-multiplies efficiency of enemy by 400%
	-named Customisable enemies
	-picture : http://i.imgur.com/s00TzAn.png
	*enemyUpgrade11
	-"Enemies give five times as much code. <br><i> .Now you can have your enemies also in 3D! </i>"
	-costs 1000000000000000 code
	-unlocks at 250 enemy
	-multiplies efficiency of enemy by 450%
	-named 3D enemies
	-picture : http://i.imgur.com/ikSx5r1.png
	*enemyUpgrade9
	-"Enemies give six times as much code. <br><i> It's possible to play as the enemy now. </i>"
	-costs 100000000000000000 code
	-unlocks at 300 enemy
	-multiplies efficiency of enemy by 500%
	-named Playable enemies
	-picture : http://i.imgur.com/q6R2mca.png
	*enemyUpgrade12
	-"Enemies give seven times as much code. <i> The AI now has the intelligence of a human... has science gone too far? </i>"
	-costs 5e+19 code
	-unlocks at 350 enemy
	-multiplies efficiency of enemy by 700%
	-named Sentient AI
	-picture : http://i.imgur.com/1pBIbiy.png
	*enemyUpgrade10
	-"Enemies give eight times as much code. <br><i> Well, we didn't exactly had the sense of a final boss before... We just slapped the same boss with a slightly more powerful or a single new attack over and over without much focus at the sense of final fights. </i>"
	-costs 5e+21 code
	-unlocks at 400 enemy
	-multiplies efficiency of enemy by 800%
	-named Final bosses
	-picture : http://i.imgur.com/XdJLtmY.png
	*enemyUpgrade13
	-"Enemies give 9 times as much code. <br><i>This boss has just about EVERYTHING... we've reached perfection. Going any further could destroy the world. </i>"
	-costs 5e+23 code
	-unlocks at 450 enemy
	-multiplies efficiency of enemy by 900%
	-named The ultimate boss
	-picture : http://i.imgur.com/6bqRFUF.png
        *enemyUpgrade14
        -"Enemies write <b>1%</b> more code for each enemy. <br><i></i>"
        -costs 8e+25 code
        -unlocks at 500 enemy
        -multiplies efficiency of enemy by 1% per enemy
        -named Enemy Ascension
	-picture : http://i.imgur.com/IWwxVoe.png
        *enemyUpgrade15
        -"Enemies write <b>1%</b> more code for each enemy. <br><i></i>"
        -costs 4e+28 code
        -unlocks at 600 enemy
        -multiplies efficiency of enemy by 1% per enemy
        -named Enemy Ascension Type Alpha
	-picture : http://i.imgur.com/wMxmhIP.png
        *enemyUpgrade16
        -"Enemies write <b>1%</b> more code for each enemy. <br><i></i>"
        -costs 6e+30 code
        -unlocks at 700 enemy
        -multiplies efficiency of enemy by 1% per enemy
        -named Enemy Ascension Type Beta
	-picture : http://i.imgur.com/26u6FZr.png
        *enemyUpgrade17
        -"Enemies write <b>1%</b> more code for each enemy. <br><i></i>"
        -costs 1e+33 code
        -unlocks at 800 enemy
        -multiplies efficiency of enemy by 1% per enemy
        -named Enemy Ascension Type Gamma
	-picture : http://i.imgur.com/HS47WOG.png
	*objectAndEnemyUpgrade1
	-"Objects are 5% more efficient for each enemy, and enemies are 4.5% more efficient for each object.<br><i>These are objects that harm you when you touch them. Like spikes.</i>
	-costs 500000 code
	-unlocks at 40 enemy, 40 object
	-multiplies efficiency of enemy by 4.5% per object
	-multiplies efficiency of object by 5% per enemy
	-named Dangerous Objects
	-picture : http://i.imgur.com/7ERdDqB.png
	*objectAndEnemyUpgrade2
	-"Objects are 3.5% more efficient for each enemy, and enemies are 2.5% more efficient for each object.<br><i>These are objects that act like enemies. They move and have AI.</i>
	-costs 25000000000 code
	-unlocks at 120 enemy, 120 object
	-multiplies efficiency of enemy by 2.5% per object
	-multiplies efficiency of object by 3.5% per enemy
	-named Enemy Objects
	-picture : http://i.imgur.com/2xeA97i.png
	*objectAndEnemyUpgrade3
	-"Objects are 2.5% more efficient for each enemy, and enemies are 2% more efficient for each object.<br><i>These look like they're objects... but actually they're enemies.</i>
	-costs 7500000000000 code
	-unlocks at 200 enemy, 200 object
	-multiplies efficiency of enemy by 2% per object
	-multiplies efficiency of object by 2.5% per enemy
	-named Disguised Enemy Objects
	-picture : http://i.imgur.com/j4QU5qi.png
	*objectAndEnemyUpgrade4
	-"Objects are 2% more efficient for each enemy, and enemies are 1.5% more efficient for each object.<br><i>Self-explanatory, really.</i>
	-costs 160000000000000000 code
	-unlocks at 300 enemy, 300 object
	-multiplies efficiency of enemy by 2% per object
	-multiplies efficiency of object by 1.5% per enemy
	-named Sometimes object, sometimes enemy
	-picture : http://i.imgur.com/tVJUiFV.png
	*objectAndEnemyUpgrade5
	-"Objects are 1% more efficient for each enemy, and enemies are 1% more efficient for each object.<br><i>This boss looks like a giant object. But when you touch it, a boss battle starts.</i>
	-costs 8e+21 code
	-unlocks at 400 enemy, 400 object
	-multiplies efficiency of enemy by 1% per object
	-multiplies efficiency of object by 1% per enemy
	-named Object bosses
	-picture : http://i.imgur.com/Va8DMwB.png
	*objectAndEnemyUpgrade6
	-"Objects are 1% more efficient for each enemy, and enemies are 1% more efficient for each object.<br><i></i>
	-costs 4e+25 code
	-unlocks at 500 enemy, 500 object
	-multiplies efficiency of enemy by 1% per object
	-multiplies efficiency of object by 1% per enemy
	-named Joint Object-Enemy Ascension
	-picture : http://i.imgur.com/YuPQIE4.png
	*playerUpgrade1
	-"Players give <b>20%</b> more code.<br> <i> The previous controls were shoddy. Let's improve them a bit. </i>"
	-costs 70000 code
	-unlocks at 1 player
	-multiplies efficiency of player by 120%
	-named Better Controls
	-picture : http://i.imgur.com/kVGfl4S.png
	*playerUpgrade2
	-"Players give <b>50%</b> more code.<br> <i>Now you can invite your friend to play co-op! </i>"
	-costs 200000 code
	-unlocks at 10 player
	-multiplies efficiency of player by 150%
	-named 2 player mode
	-picture : http://i.imgur.com/oIrj792.png
	*playerUpgrade3
	-"Players give <b>twice</b> as much code.<br> <i> You can now use button combinations, allowing for more possibilities. </i>"
	-costs 500000 code
	-unlocks at 20 player
	-multiplies efficiency of player by 200%
	-named Button combinations
	-picture : http://i.imgur.com/4skOCMH.png
	*playerUpgrade4
	-"Players give <b>twice</b> as much code.<br> <i> The four the merrier. </i>"
	-costs 4000000 code
	-unlocks at 40 player
	-multiplies efficiency of player by 200%
	-named Four players
	-picture : http://i.imgur.com/to5E0fP.png
	*playerUpgrade5
	-"Players give <b>twice</b> as much code.<br> <i> You can customize your character, allowing it to have different stats. </i>"
	-costs 250000000 code
	-unlocks at 80 player
	-multiplies efficiency of player by 200%
	-named Customization
	-picture : http://i.imgur.com/sAR12o2.png
	*playerUpgrade6
	-"Players give <b>2.5 times</b> as much code. Games give 20% more code. Fanbases give 10% more code. Forums give 10% more code.<br> <i> What an awesome idea this was. </i>"
	-costs 1500000000 code
	-unlocks at 100 player
	-multiplies efficiency of player by 250%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of fanbase by 110%
	-multiplies efficiency of forum by 110%
	-named Online multiplayer
	-picture : http://i.imgur.com/WxQo35V.png
	*playerUpgrade7
	-"Players give <b>three times</b> as much code.<br> <i> There were only a few customizable options before, so let's add more! </i>"
	-costs 300000000000 code
	-unlocks at 150 player
	-multiplies efficiency of player by 300%
	-named More customization
	-picture : http://i.imgur.com/UzVFTfA.png
	*playerUpgrade8
	-"Players give <b>four times</b> as much code. Forums give 50% more code.<br> <i> Phrases that will be repeated on the internet thousands of times... </i>"
	-costs 75000000000000 code
	-unlocks at 200 player
	-multiplies efficiency of player by 400%
	-multiplies efficiency of forum by 150%
	-named Memorable phrases
	-picture : http://i.imgur.com/cLfuNQy.png
	*playerUpgrade11
	-"Players give <b>4.5 times</b> as much code.<br> <i> These controls are pretty damn good. They work with almost everyone. </i>"
	-costs 7500000000000000 code
	-unlocks at 250 player
	-multiplies efficiency of player by 450%
	-named Awesome Controls
	-picture : http://i.imgur.com/oVdmZHI.png
	*playerUpgrade9
	-"Players give <b>five times</b> as much code.<br> <i> Should have done this sooner, but oh well... </i>"
	-costs 2000000000000000000 code
	-unlocks at 300 player
	-multiplies efficiency of player by 500%
	-named Great character design
	-picture : http://i.imgur.com/b6tuXJN.png
	*playerUpgrade12
	-"Players give <b>6.5 times</b> as much code.<br> <i> Your player has the ability to break he Fourth Wall now. People think it's cool. </i>"
	-costs 75000000000000000000 code
	-unlocks at 350 player
	-multiplies efficiency of player by 650%
	-named Fourth-Wall breaking characters
	-picture : http://i.imgur.com/sdrIZaX.png
	*playerUpgrade10
	-"Players give <b>7.5 times</b> as much code.<br> <i> We found the controls that work best for all players. At last. </i>"
	-costs 4e+22 code
	-unlocks at 400 player
	-multiplies efficiency of player by 750%
	-named The Best Controls
	-picture : http://i.imgur.com/TFC0xvM.png
	*playerUpgrade13
	-"Players give <b>9 times</b> as much code.<br> <i> We introduced the ability to interact with your own player by talking to it! </i>"
	-costs 4e+24 code
	-unlocks at 450 player
	-multiplies efficiency of player by 900%
	-named Interact with your player
	-picture : http://i.imgur.com/49amzUR.png
        *playerUpgrade14
        -"Players write <b>1%</b> more code for each player. <br><i></i>"
        -costs 6e+26 code
        -unlocks at 500 player
        -multiplies efficiency of player by 1% per player
        -named Player Ascension
	-picture : http://i.imgur.com/n052EUU.png
        *playerUpgrade15
        -"Players write <b>1%</b> more code for each player. <br><i></i>"
        -costs 1e+29 code
        -unlocks at 600 player
        -multiplies efficiency of player by 1% per player
        -named Player Ascension Type Alpha
	-picture : http://i.imgur.com/OygzM5y.png
        *playerUpgrade16
        -"Players write <b>1%</b> more code for each player. <br><i></i>"
        -costs 1.5e+31 code
        -unlocks at 700 player
        -multiplies efficiency of player by 1% per player
        -named Player Ascension Type Beta
	-picture : http://i.imgur.com/zWWgVon.png
        *playerUpgrade17
        -"Players write <b>1%</b> more code for each player. <br><i></i>"
        -costs 2.25e+33 code
        -unlocks at 800 player
        -multiplies efficiency of player by 1% per player
        -named Player Ascension Type Gamma
	-picture : http://i.imgur.com/b5F4prH.png
	*writerAndPlayerUpgrade1
	-"Players are 5% more efficient for code writer, and code writers are 12% more efficient for each player.<br><i>The players can now code for us. Neat.</i>
	-costs 250000000 code
	-unlocks at 40 codeWriter, 40 player
	-multiplies efficiency of player by 5% per codeWriter
	-multiplies efficiency of codeWriter by 12% per player
	-named Coding Players
	-picture : http://i.imgur.com/RvLWS43.png
	*writerAndPlayerUpgrade2
	-"Players are 3% more efficient for code writer, and code writers are 3% more efficient for each player.<br><i>The players receive special lessons to help them write more efficiently as well.</i>
	-costs 25000000000 code
	-unlocks at 120 codeWriter, 120 player
	-multiplies efficiency of player by 3% per codeWriter
	-multiplies efficiency of codeWriter by 3% per player
	-named Lessons for players
	-picture : http://i.imgur.com/7qKQCcR.png
	*writerAndPlayerUpgrade3
	-"Players are 2% more efficient for code writer, and code writers are 2% more efficient for each player.<br><i>Some players were lost during the warping to reality. Let's make sure this doesn't happen again.</i>
	-costs 250000000000000 code
	-unlocks at 200 codeWriter, 200 player
	-multiplies efficiency of player by 2% per codeWriter
	-multiplies efficiency of codeWriter by 2% per player
	-named Better warping
	-picture : http://i.imgur.com/zuio4Z7.png
	*writerAndPlayerUpgrade4
	-"Players are 1% more efficient for code writer, and code writers are 1.5% more efficient for each player.<br><i>The players care now optimised for maximum writing efficiency.</i>
	-costs 2500000000000000000 code
	-unlocks at 300 codeWriter, 300 player
	-multiplies efficiency of player by 1% per codeWriter
	-multiplies efficiency of codeWriter by 1.5% per player
	-named Optimised Players
	-picture : http://i.imgur.com/AaH9HtG.png
	*writerAndPlayerUpgrade5
	-"Players are 0.5% more efficient for code writer, and code writers are 1% more efficient for each player.<br><i>We optimised the players to the max. Perfection = reached.</i>
	-costs 25000000000000000000000 code
	-unlocks at 400 codeWriter, 400 player
	-multiplies efficiency of player by 0.5% per codeWriter
	-multiplies efficiency of codeWriter by 1% per player
	-named Maximum Optimisation
	-picture : http://i.imgur.com/cIQ9tW3.png
	*writerAndPlayerUpgrade6
	-"Players are 1% more efficient for code writer, and code writers are 1% more efficient for each player.<br><i></i>
	-costs 600000000000000000000000000 code
	-unlocks at 500 codeWriter, 500 player
	-multiplies efficiency of player by 1% per codeWriter
	-multiplies efficiency of codeWriter by 1% per player
	-named Joint Code Writer-Player Ascension
	-picture : http://i.imgur.com/IZCca08.png
	*levelUpgrade1
	-"Levels give <b>20%</b> more code.<br> <i> A bit of challenge to your levels. </i>"
	-costs 800000 code
	-unlocks at 1 level
	-multiplies efficiency of level by 120%
	-named Obstacles
	-picture : http://i.imgur.com/8yR8kgQ.png
	*levelUpgrade2
	-"Levels give <b>50%</b> more code.<br> <i>...and this level is themed on a desert. </i>"
	-costs 2000000 code
	-unlocks at 10 level
	-multiplies efficiency of level by 150%
	-named Themed levels
	-picture : http://i.imgur.com/LMJOKB9.png
	*levelUpgrade3
	-"Levels give <b>twice</b> as much code.<br> <i> The bane of all gamers. </i>"
	-costs 7500000 code
	-unlocks at 20 level
	-multiplies efficiency of level by 200%
	-named Water levels
	-picture : http://i.imgur.com/k7aKHdL.png
	*levelUpgrade4
	-"Levels give <b>twice</b> as much code.<br> <i> ''Yay! I found a secret bonus level!'' </i>"
	-costs 50000000 code
	-unlocks at 40 level
	-multiplies efficiency of level by 200%
	-named Bonus levels
	-picture : http://i.imgur.com/XUf9eAA.png
	*levelUpgrade5
	-"Levels give <b>twice</b> as much code.<br> <i> ''Nice! I found a hidden area!'' </i>"
	-costs 2000000000 code
	-unlocks at 80 level
	-multiplies efficiency of level by 200%
	-named Secret areas
	-picture : http://i.imgur.com/EinxKxG.png
	*levelUpgrade6
	-"Levels give <b>2.5 times</b> as much code.<br> <i> A challenging level that greatly rewards players that pass. </i>"
	-costs 20000000000 code
	-unlocks at 100 level
	-multiplies efficiency of level by 250%
	-named Challenge levels
	-picture : http://i.imgur.com/tCwH35v.png
	*levelUpgrade7
	-"Levels give <b>three times</b> as much code. Enemies give 50% more code.<br> <i> WARNING: BOSS APPROACHING </i>"
	-costs 5000000000000 code
	-unlocks at 150 level
	-multiplies efficiency of level by 300%
	-multiplies efficiency of enemy by 150%
	-named Boss levels
	-picture : http://i.imgur.com/6oLaqjp.png
	*levelUpgrade8
	-"Levels give <b>four times</b> as much code. Enemies give twice as much code.<br> <i> The Final Boss approaches. Are you prepared? </i>"
	-costs 800000000000000 code
	-unlocks at 200 level
	-multiplies efficiency of level by 400%
	-multiplies efficiency of enemy by 200%
	-named Final Boss level
	-picture : http://i.imgur.com/HoAC6IU.png
	*levelUpgrade11
	-"Levels give <b>4.5 times</b> as much code. <br> <i> And in this level, you fight off a multitude of bosses. </i>"
	-costs 80000000000000000 code
	-unlocks at 250 level
	-multiplies efficiency of level by 400%
	-named Multi-boss level
	-picture : http://i.imgur.com/dRM7Qzl.png
	*levelUpgrade9
	-"Levels give <b>five times</b> as much code.<br> <i> ''Awesome! A bonus world!'' </i>"
	-costs 20000000000000000000 code
	-unlocks at 300 level
	-multiplies efficiency of level by 500%
	-named Bonus world
	-picture : http://i.imgur.com/YGpgHKY.png
	*levelUpgrade12
	-"Levels give <b>six times</b> as much code. <br> <i> Here is the level for the Super-Boss, which is the last and most powerful enemy there is. </i>"
	-costs 800000000000000000000 code
	-unlocks at 350 level
	-multiplies efficiency of level by 600%
	-named Super-Boss level
	-picture : http://i.imgur.com/vXfLCPg.png
	*levelUpgrade10
	-"Levels give <b>8 times</b> as much code.<br> <i> The true ultimate level. It has every difficult obstacle in the game. No powerups. No checkpoints. Beating it means completing the game. </i>"
	-costs 5e+23 code
	-unlocks at 400 level
	-multiplies efficiency of level by 800%
	-named The Hardest Level
	-picture : http://i.imgur.com/rEl5B6q.png
	*levelUpgrade13
	-"Levels give <b>8 times</b> as much code.<br> <i> The game rewards you with a huge bonus level after you beat the hardest level. </i>"
	-costs 5e+25 code
	-unlocks at 450 level
	-multiplies efficiency of level by 800%
	-named Super Bonus Round
	-picture : http://i.imgur.com/Nfd0ls6.png
        *levelUpgrade14
        -"Levels write <b>1%</b> more code for each level. <br><i></i>"
        -costs 8e+27 code
        -unlocks at 500 level
        -multiplies efficiency of level by 1% per level
        -named Level Ascension
	-picture : http://i.imgur.com/rzcd4m3.png
        *levelUpgrade15
        -"Levels write <b>1%</b> more code for each level. <br><i></i>"
        -costs 4e+30 code
        -unlocks at 600 level
        -multiplies efficiency of level by 1% per level
        -named Level Ascension Type Alpha
	-picture : http://i.imgur.com/O0ZuYTW.png
        *levelUpgrade16
        -"Levels write <b>1%</b> more code for each level. <br><i></i>"
        -costs 1e+35 code
        -unlocks at 700 level
        -multiplies efficiency of level by 1% per level
        -named Level Ascension Type Beta
	-picture : http://i.imgur.com/qcukJO6.png
        *levelUpgrade17
        -"Levels write <b>1%</b> more code for each level. <br><i></i>"
        -costs 2.25e+39 code
        -unlocks at 800 level
        -multiplies efficiency of level by 1% per level
        -named Level Ascension Type Gamma
	-picture : http://i.imgur.com/qcukJO6.png
	*gameUpgrade1
	-"Games give <b>20%</b> more code.<br> <i> The games were really short before. Let's make them a bit longer. </i>"
	-costs 20000000 code
	-unlocks at 1 game
	-multiplies efficiency of game by 120%
	-multiplies efficiency of gameProducer by 120%
	-named Longer games
	-picture : http://i.imgur.com/5wnMU6r.png
	*gameUpgrade2
	-"Games give <b>50%</b> more code.<br> <i> ''so mlg'' ~xX360n0sc0prXx </i>"
	-costs 75000000 code
	-unlocks at 10 game
	-multiplies efficiency of game by 150%
	-multiplies efficiency of gameProducer by 150%
	-named Better graphics
	-picture : http://i.imgur.com/KHMUutT.png
	*gameUpgrade3
	-"Games give <b>twice</b> as much code.<br> <i> ''gameplay > graphics'' ~fanboy </i>"
	-costs 200000000 code
	-unlocks at 20 game
	-multiplies efficiency of game by 200%
	-multiplies efficiency of gameProducer by 200%
	-named Better gameplay
	-picture : http://i.imgur.com/M7CT5pJ.png
	*gameUpgrade4
	-"Games give <b>twice</b> as much code.<br> <i> Achievement unlocked: add achievements! </i>"
	-costs 1500000000 code
	-unlocks at 40 game
	-multiplies efficiency of game by 200%
	-multiplies efficiency of gameProducer by 200%
	-named Achievements
	-picture : http://i.imgur.com/Mmq4iFS.png
	*gameUpgrade5
	-"Games give <b>twice</b> as much code.<br> <i> The funny thing is you're playing an idle game about developing games, and you unlock idle games. What happens if one of those idle games is about developing games and that has an upgrade about idle games? And so on... </i>"
	-costs 100000000000 code
	-unlocks at 80 game
	-multiplies efficiency of game by 200%
	-multiplies efficiency of gameProducer by 200%
	-named Idle games
	-picture : http://i.imgur.com/fROK9uy.png
	*gameUpgrade6
	-"Games give <b>2.5 times</b> as much code.<br> <i>Some great music in your game. </i>"
	-costs 2.25e+12 code
	-unlocks at 100 game
	-multiplies efficiency of game by 250%
	-multiplies efficiency of gameProducer by 250%
	-named Music
	-picture : http://i.imgur.com/5XHe60b.png
	*gameUpgrade7
	-"Games give <b>3 times</b> as much code.<br> <i>The sounds change from mediocre to some of the best. </i>"
	-costs 4e+14 code
	-unlocks at 150 game
	-multiplies efficiency of game by 300%
	-multiplies efficiency of gameProducer by 300%
	-named Sound Improvement
	-picture : http://i.imgur.com/l7aEKTb.png
	*gameUpgrade8
	-"Games give <b>4 times</b> as much code. Sequels give twice as much code.<br> <i>Let's add a storyline to our game. </i>"
	-costs 6e+16 code
	-unlocks at 200 game
	-multiplies efficiency of game by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of gameSeries by 200%
	-named Story
	-picture : http://i.imgur.com/gQ607Zd.png
	*gameUpgrade9
	-"Games give <b>4.5 times</b> as much code.<br> <i> Always satisfying finding them. </i>"
	-costs 1e+19 code
	-unlocks at 250 game
	-multiplies efficiency of game by 450%
	-multiplies efficiency of gameProducer by 450%
	-named Easter eggs
	-picture : http://i.imgur.com/GAzWhfB.png
	*gameUpgrade10
	-"Games give <b>5 times</b> as much code.<br> <i> New things are being brought into your game. </i>"
	-costs 1.5e+21 code
	-unlocks at 300 game
	-multiplies efficiency of game by 500%
	-multiplies efficiency of gameProducer by 500%
	-named Innovation
	-picture : http://i.imgur.com/jxisIM5.png
	*gameUpgrade11
	-"Games give <b>6 times</b> as much code.<br> <i> So.. many... game... modes... </i>"
	-costs 2.25e+23 code
	-unlocks at 350 game
	-multiplies efficiency of game by 600%
	-multiplies efficiency of gameProducer by 600%
	-named Multiple game modes
	-picture : http://i.imgur.com/JhCnyEC.png
	*gameUpgrade12
	-"Games give <b>7 times</b> as much code.<br> <i> We asked our coders to try and put everything into one game, and they deliver.  </i>"
	-costs 4e+25 code
	-unlocks at 400 game
	-multiplies efficiency of game by 700%
	-multiplies efficiency of gameProducer by 700%
	-named Everything
	-picture : http://i.imgur.com/B5iAh6r.png
	*gameUpgrade13
	-"Games give <b>8 times</b> as much code.<br> <i> People thought this was impossible. But we finally made it. A game without a single bug in it. Not even a graphical one.  </i>"
	-costs 6e+27 code
	-unlocks at 450 game
	-multiplies efficiency of game by 800%
	-multiplies efficiency of gameProducer by 800%
	-named The Game without any Bugs
	-picture : http://i.imgur.com/RPQ8DeL.png
        *gameUpgrade14
        -"Games write <b>1%</b> more code for each game. <br><i></i>"
        -costs 1e+30 code
        -unlocks at 500 game
        -multiplies efficiency of game by 1% per game
        -named Game Ascension
	-picture : http://i.imgur.com/SGCPj2D.png
        *gameUpgrade15
        -"Games write <b>1%</b> more code for each game. <br><i></i>"
        -costs 2.25e+34 code
        -unlocks at 600 game
        -multiplies efficiency of game by 1% per game
        -named Game Ascension Type Alpha
	-picture : http://i.imgur.com/2xkEDS0.png
        *gameUpgrade16
        -"Games write <b>1%</b> more code for each game. <br><i></i>"
        -costs 6e+38 code
        -unlocks at 700 game
        -multiplies efficiency of game by 1% per game
        -named Game Ascension Type Beta
	-picture : http://i.imgur.com/2xkEDS0.png
        *gameUpgrade17
        -"Games write <b>1%</b> more code for each game. <br><i></i>"
        -costs 1.5e+43 code
        -unlocks at 800 game
        -multiplies efficiency of game by 1% per game
        -named Game Ascension Type Gamma
	-picture : http://i.imgur.com/2xkEDS0.png
	*gameAndProducerUpgrade1
	-"Game producers are 2% more efficient for each game.<br><i>Some inspiration for your game producers.</i>
	-costs 100000000000 code
	-unlocks at 40 game, 40 gameProducer
	-multiplies efficiency of gameProducer by 2% per game
	-named Inspiration
	-picture : http://i.imgur.com/5wnMU6r.png
	*gameAndProducerUpgrade2
	-"Game producers are 0.5% more efficient for each game.<br><i>The games increase the productivity of the game producers.</i>
	-costs 15000000000000 code
	-unlocks at 120 game, 120 gameProducer
	-multiplies efficiency of gameProducer by 0.5% per game
	-named Productivity Boosting Games
	-picture : http://i.imgur.com/fROK9uy.png
	*gameAndProducerUpgrade3
	-"Game producers are 0.2% more efficient for each game.<br><i>The gamers now help your producers produce more!</i>
	-costs 225000000000000000 code
	-unlocks at 200 game, 200 gameProducer
	-multiplies efficiency of gameProducer by 0.2% per game
	-named Gamer helpers
	-picture : http://i.imgur.com/l7aEKTb.png
	*gameAndProducerUpgrade4
	-"Game producers are 0.1% more efficient for each game.<br><i>Because magically enhancing anything makes it better, of course.</i>
	-costs 4000000000000000000000 code
	-unlocks at 300 game, 300 gameProducer
	-multiplies efficiency of gameProducer by 0.1% per game
	-named Magically enhanced game producers
	-picture : http://i.imgur.com/gQ607Zd.png
	*gameAndProducerUpgrade5
	-"Game producers are 0.02% more efficient for each game, and games are twice as efficient.<br><i>The games inspire the producers in the best way possible.</i>
	-costs 60000000000000000000000000 code
	-unlocks at 400 game, 400 gameProducer
	-multiplies efficiency of gameProducer by 0.02% per game
	-multiplies efficiency of game by 200%
	-named Ultimate Inspiration
	-picture : http://i.imgur.com/jxisIM5.png

	*levelAndGameUpgrade1
	-"Levels are 4.5% more efficient for each game, and games are 3.5% more efficient for each level.<br><i>These aren't main levels. These levels are just essentially storyline.</i>
	-costs 2000000000 code
	-unlocks at 40 level, 40 game
	-multiplies efficiency of level by 4.5% per game
	-multiplies efficiency of game by 3.5% per level
	-named Storyline-based levels
	-picture : http://i.imgur.com/744PzQg.png
	*levelAndGameUpgrade2
	-"Levels are 3% more efficient for each game, and games are 2% more efficient for each level.<br><i>Brought to you by...</i>
	-costs 300000000000000 code
	-unlocks at 120 level, 120 game
	-multiplies efficiency of level by 3% per game
	-multiplies efficiency of game by 2% per level
	-named Credit levels
	-picture : http://i.imgur.com/PkK2Y2t.png
	*levelAndGameUpgrade3
	-"Levels are 2% more efficient for each game, and games are 1% more efficient for each level.<br><i>Downloadable content means that you can download more levels from the internet.</i>
	-costs 30000000000000000 code
	-unlocks at 200 level, 200 game
	-multiplies efficiency of level by 2% per game
	-multiplies efficiency of game by 1% per level
	-named DLC
	-picture : http://i.imgur.com/YoCg0Uw.png
	*levelAndGameUpgrade4
	-"Levels are 1.5% more efficient for each game, and games are 0.75% more efficient for each level.<br><i>Why just have DLC when you can have entire expansion packs?</i>
	-costs 1.5e+21 code
	-unlocks at 300 level, 300 game
	-multiplies efficiency of level by 1.5% per game
	-multiplies efficiency of game by 0.75% per level
	-named Expansion Packs
	-picture : http://i.imgur.com/Cs5NeXY.png
	*levelAndGameUpgrade5
	-"Objects are 1% more efficient for each enemy, and enemies are 0.5% more efficient for each object.<br><i>A similar game to the original, but with slightly different storyline and levels. With an added challenge.</i>
	-costs 5e+23 code
	-unlocks at 400 level, 400 game
	-multiplies efficiency of level by 1% per game
	-multiplies efficiency of game by 0.5% per level
	-named Alternate Games
	-picture : http://i.imgur.com/DqkXKCs.png
	*levelAndGameUpgrade6
	-"Objects are 1% more efficient for each enemy, and enemies are 1% more efficient for each object.<br><i></i>
	-costs 8e+27 code
	-unlocks at 500 level, 500 game
	-multiplies efficiency of level by 1% per game
	-multiplies efficiency of game by 1% per level
	-named Joint Level-Game Ascension
	-picture : http://i.imgur.com/KJj7k9Q.png
	*fanbaseUpgrade1
	-"Fanbases give <b>20%</b> more code.<br> <i> There are now fewer creeps in the fanbases, deterring fewer people. </i>"
	-costs 400000000 code
	-unlocks at 1 fanbase
	-multiplies efficiency of fanbase by 120%
	-named Fewer creeps
	-picture : http://i.imgur.com/RgI2bKx.png
	*fanbaseUpgrade2
	-"Fanbases give <b>50%</b> more code.<br> <i> They donate to you, allowing you to write more code! </i>"
	-costs 1500000000 code
	-unlocks at 10 fanbase
	-multiplies efficiency of fanbase by 150%
	-named Donating fanbases
	-picture : http://i.imgur.com/429bi8N.png
	*fanbaseUpgrade3
	-"Fanbases give <b>twice</b> as much code.<br> <i> The fanbases increase the popularity of your game by making add-ons for your game. </i>"
	-costs 3600000000 code
	-unlocks at 20 fanbase
	-multiplies efficiency of fanbase by 200%
	-named Add-ons
	-picture : http://i.imgur.com/I57jV3O.png
	*fanbaseUpgrade4
	-"Fanbases give <b>twice</b> as much code.<br> <i> The fanbases make mods for your game. Mods can make a game massively popular. </i>"
	-costs 36000000000 code
	-unlocks at 40 fanbase
	-multiplies efficiency of fanbase by 200%
	-named Modding community
	-picture : http://i.imgur.com/TKoWEKw.png
	*fanbaseUpgrade5
	-"Fanbases give <b>twice</b> as much code.<br> <i> The creeps in your fanbase are no longer, and the negative reputation this puts on your game is now gone. </i>"
	-costs 1000000000000 code
	-unlocks at 80 fanbase
	-multiplies efficiency of fanbase by 200%
	-named No creeps
	-picture : http://i.imgur.com/7jnIIiV.png
	*fanbaseUpgrade6
	-"Fanbases give <b>2.5 times</b> as much code.<br> <i> Now your fans help develop your game for you! </i>"
	-costs 10000000000000 code
	-unlocks at 100 fanbase
	-multiplies efficiency of fanbase by 250%
	-named Game-developing community
	-picture : http://i.imgur.com/SsevfM7.png
	*fanbaseUpgrade7
	-"Fanbases give <b>three times</b> as much code.<br> <i>The community becomes simply awesome, putting a really positive light on your game.</i>"
	-costs 2000000000000000 code
	-unlocks at 150 fanbase
	-multiplies efficiency of fanbase by 300%
	-named Awesome community
	-picture : http://i.imgur.com/vQvf7Ix.png
	*fanbaseUpgrade8
	-"Fanbases give <b>four times</b> as much code.<br> <i> Your fanbases are friendly to newbies now, encouraging them to keep going. </i>"
	-costs 400000000000000000 code
	-unlocks at 200 fanbase
	-multiplies efficiency of fanbase by 400%
	-named Newbie-friendly fanbses
	-picture : http://i.imgur.com/cFYlL2l.png
	*fanbaseUpgrade9
	-"Fanbases give <b>4.5 times</b> as much code.<br> <i>Fanbases give you good ideas for your next game now. </i>"
	-costs 1e+20 code
	-unlocks at 250 fanbase
	-multiplies efficiency of fanbase by 450%
	-named Idea Fanbases
	-picture : http://i.imgur.com/mqzlu6m.png
	*fanbaseUpgrade10
	-"Fanbases give <b>5 times</b> as much code.<br> <i> The fanbases are actually made up of expert coders! This really is a good thing. </i>"
	-costs 1e+22 code
	-unlocks at 300 fanbase
	-multiplies efficiency of fanbase by 500%
	-named Coding Fanbases
	-picture : http://i.imgur.com/HQhNtcb.png
	*fanbaseUpgrade11
	-"Fanbases give <b>6 times</b> as much code.<br> <i> You are now hiring the best coders in the fanbases. This has had no bad effect so far. </i>"
	-costs 2e+24 code
	-unlocks at 350 fanbase
	-multiplies efficiency of fanbase by 600%
	-named Fanbase hiring
	-picture : http://i.imgur.com/Vx0HKfa.png
	*fanbaseUpgrade12
	-"Fanbases give <b>7 times</b> as much code.<br> <i> Turns out that some of them were noobs, and kept adding ''spaghetti unkillable boss nonillion'', whatever that is. Anyway, our fanbases have reached perfection now. </i>"
	-costs 5e+26 code
	-unlocks at 400 fanbase
	-multiplies efficiency of fanbase by 700%
	-named Noob firing
	-picture : http://i.imgur.com/DwU5XGf.png
	*fanbaseUpgrade13
	-"Fanbases give <b>9 times</b> as much code.<br> <i> The fanbases encourage more people to play your games. Because of the immense power of your games and your fanbases, millions more people buy your game. </i>"
	-costs 5e+28 code
	-unlocks at 450 fanbase
	-multiplies efficiency of fanbase by 900%
	-named Super-powerful encouragement
	-picture : http://i.imgur.com/lVM9lRk.png
        *fanbaseUpgrade14
        -"Fanbases write <b>1%</b> more code for each fanbase. <br><i></i>"
        -costs 8e+30 code
        -unlocks at 500 fanbase
        -multiplies efficiency of fanbase by 1% per fanbase
        -named Fanbase Ascension
	-picture : http://i.imgur.com/HQEKjOR.png
        *fanbaseUpgrade15
        -"Fanbases write <b>1%</b> more code for each fanbase. <br><i></i>"
        -costs 1.5e+35 code
        -unlocks at 600 fanbase
        -multiplies efficiency of fanbase by 1% per fanbase
        -named Fanbase Ascension Type Alpha
	-picture : http://i.imgur.com/HQEKjOR.png
        *fanbaseUpgrade16
        -"Fanbases write <b>1%</b> more code for each fanbase. <br><i></i>"
        -costs 4e+39 code
        -unlocks at 700 fanbase
        -multiplies efficiency of fanbase by 1% per fanbase
        -named Fanbase Ascension Type Beta
	-picture : http://i.imgur.com/HQEKjOR.png
        *fanbaseUpgrade17
        -"Fanbases write <b>1%</b> more code for each fanbase. <br><i></i>"
        -costs 1e+44 code
        -unlocks at 800 fanbase
        -multiplies efficiency of fanbase by 1% per fanbase
        -named Fanbase Ascension Type Gamma
	-picture : http://i.imgur.com/HQEKjOR.png
	*forumUpgrade1
	-"Forums give <b>20%</b> more code.<br> <i> The forums were abused previously. Pictures of penises were spammed everywhere, useless threads were created... let's fix that. </i>"
	-costs 25000000000 code
	-unlocks at 1 forum
	-multiplies efficiency of forum by 120%
	-named Moderation
	-picture : http://i.imgur.com/2mkVLkh.png
	*forumUpgrade2
	-"Forums give <b>50%</b> more code.<br> <i> A nice admin to ban more spammers. </i>"
	-costs 75000000000 code
	-unlocks at 10 forum
	-multiplies efficiency of forum by 150%
	-named Site Admins
	-picture : http://i.imgur.com/KGTx2Sr.png
	*forumUpgrade3
	-"Forums give <b>twice</b> as much code.<br> <i>Pure Garcinia Cambogia helps remo- BAM. Gone. </i>"
	-costs 250000000000 code
	-unlocks at 20 forum
	-multiplies efficiency of forum by 200%
	-named Spambot Protection
	-picture : http://i.imgur.com/fCms0f2.png
	*forumUpgrade4
	-"Forums give <b>twice</b> as much code.<br> <i> There weren't really any rules to the forums before. Now that rules are in place, fewer rule-breaking posts are made. </i>"
	-costs 1000000000000 code
	-unlocks at 40 forum
	-multiplies efficiency of forum by 200%
	-named Forum Rules
	-picture : http://i.imgur.com/f8F8aRL.png
	*forumUpgrade5
	-"Forums give <b>twice</b> as much code.<br> <i> The forum design isn't very good at the moment. Let's improve the design and make the forum better! </i>"
	-costs 80000000000000 code
	-unlocks at 80 forum
	-multiplies efficiency of forum by 200%
	-named Improved Forum Design
	-picture : http://i.imgur.com/Z2DM9K0.png
	*forumUpgrade6
	-"Forums give <b>2.5 times</b> as much code.<br> <i> Now all the mods for your game get their own separate section. </i>"
	-costs 800000000000000 code
	-unlocks at 100 forum
	-multiplies efficiency of forum by 250%
	-named Modding Section
	-picture : http://i.imgur.com/f2QW0dH.png
	*forumUpgrade7
	-"Forums give <b>three times</b> as much code.<br> <i> We kept getting DDoS'd by some hacker. Can we fix this? Yes we can! </i>"
	-costs 80000000000000000 code
	-unlocks at 150 forum
	-multiplies efficiency of forum by 300%
	-named DDoS protection
	-picture : http://i.imgur.com/2cc7y5u.png
	*forumUpgrade8
	-"Forums give <b>four times</b> as much code.<br> <i> Some trolls kept coming back. Time to permanently ban their IP. </i>"
	-costs 8000000000000000000 code
	-unlocks at 200 forum
	-multiplies efficiency of forum by 400%
	-named IP bans
	-picture : http://i.imgur.com/KlboWRw.png
	*forumUpgrade9
	-"Forums give <b>4.5 times</b> as much code.<br> <i> Your forums are now some of the most popular on the internet! </i>"
	-costs 800000000000000000000 code
	-unlocks at 250 forum
	-multiplies efficiency of forum by 450%
	-named Popular Forums
	-picture : http://i.imgur.com/dFX5aXM.png
	*forumUpgrade10
	-"Forums give <b>five times</b> as much code.<br> <i> We can use this to virtually stop all spam. </i>"
	-costs 80000000000000000000000 code
	-unlocks at 300 forum
	-multiplies efficiency of forum by 500%
	-named Spamblock
	-picture : http://i.imgur.com/XdfzG7S.png
	*forumUpgrade11
	-"Forums give <b>five times</b> as much code.<br> <i> We finally stopped all rule-breaking posts! </i>"
	-costs 8000000000000000000000000 code
	-unlocks at 350 forum
	-multiplies efficiency of forum by 500%
	-named An end to rule-breaking
	-picture : http://i.imgur.com/PdeZShW.png
	*forumUpgrade12
	-"Forums give <b>7 times</b> as much code.<br> <i> We stopped all rule-breaking from all members except one. This member gets a lot of members to do illegal stuff with him. IP banning doesn't seem to work. Only one solution - destroy this member in real life.</i>"
	-costs 800000000000000000000000000 code
	-unlocks at 400 forum
	-multiplies efficiency of forum by 700%
	-named Destroy the Ultimate Troll
	-picture : http://i.imgur.com/RSPf8KB.png
	*forumUpgrade13
	-"Forums give <b>8 times</b> as much code.<br> <i> 1 in 10 people complained about the design before this update. When we updated it, 1 in 5 people complained. But that was only for two days. Then there were NO complaints.</i>"
	-costs 80000000000000000000000000000 code
	-unlocks at 450 forum
	-multiplies efficiency of forum by 800%
	-named The Perfect Design
	-picture : http://i.imgur.com/j2adTf3.png
        *forumUpgrade14
        -"Forums write <b>1%</b> more code for each forum. <br><i></i>"
        -costs 1e+32 code
        -unlocks at 500 forum
        -multiplies efficiency of forum by 1% per forum
        -named Forum Ascension
	-picture : http://i.imgur.com/HQEKjOR.png
        *forumUpgrade15
        -"Forums write <b>1%</b> more code for each forum. <br><i></i>"
        -costs 2.25e+36 code
        -unlocks at 600 forum
        -multiplies efficiency of forum by 1% per forum
        -named Forum Ascension Type Alpha
	-picture : http://i.imgur.com/HQEKjOR.png
        *forumUpgrade16
        -"Forums write <b>1%</b> more code for each forum. <br><i></i>"
        -costs 6e+40 code
        -unlocks at 700 forum
        -multiplies efficiency of forum by 1% per forum
        -named Forum Ascension Type Beta
	-picture : http://i.imgur.com/HQEKjOR.png
        *forumUpgrade17
        -"Forums write <b>1%</b> more code for each forum. <br><i></i>"
        -costs 1.5e+45 code
        -unlocks at 800 forum
        -multiplies efficiency of forum by 1% per forum
        -named Forum Ascension Type Gamma
	-picture : http://i.imgur.com/HQEKjOR.png
	*fanbaseAndForumUpgrade1
	-"Fanbases are 3.5% more efficient for each forum, and forums are 3% more efficient for each fanbase.<br><i>The fanbases have their own PM conversations on forums now.</i>
	-costs 8e+12 code
	-unlocks at 40 fanbase, 40 forum
	-multiplies efficiency of fanbase by 3.5% per forum
	-multiplies efficiency of forum by 3% per forum
	-named PM fanbases
	-picture : http://i.imgur.com/PNhdHvL.png
	*fanbaseAndForumUpgrade2
	-"Fanbases are 2.5% more efficient for each forum, and forums are 2% more efficient for each fanbase.<br><i>The fanbases now write fanfictions based on your games. Some of them are good...</i>
	-costs 8e+14 code
	-unlocks at 120 fanbase, 120 forum
	-multiplies efficiency of fanbase by 2.5% per forum
	-multiplies efficiency of forum by 2% per forum
	-named Fanfictions
	-picture : http://i.imgur.com/iqZm78q.png
	*fanbaseAndForumUpgrade3
	-"Fanbases are 2% more efficient for each forum, and forums are 1.5% more efficient for each fanbase.<br><i>The fanbases have been asking for this for some time...</i>
	-costs 8e+18 code
	-unlocks at 200 fanbase, 200 forum
	-multiplies efficiency of fanbase by 2% per forum
	-multiplies efficiency of forum by 1.5% per forum
	-named Fanbase Section
	-picture : http://i.imgur.com/FD1TttU.png
	*fanbaseAndForumUpgrade4
	-"Fanbases are 1.5% more efficient for each forum, and forums are 1% more efficient for each fanbase.<br><i>We finally made a forum for them. Shouldn't this have happened earlier?</i>
	-costs 8e+22 code
	-unlocks at 300 fanbase, 300 forum
	-multiplies efficiency of fanbase by 1.5% per forum
	-multiplies efficiency of forum by 1% per forum
	-named Fanbase Forum
	-picture : http://i.imgur.com/xx35xtb.png
	*fanbaseAndForumUpgrade5
	-"Fanbases are 1% more efficient for each forum, and forums are 0.6% more efficient for each fanbase.<br><i>Let's put all the improvements we put into the forums into the fanbase forum as well. There were some pretty nasty trolls on the fanbase forum...</i>
	-costs 8e+26 code
	-unlocks at 400 fanbase, 400 forum
	-multiplies efficiency of fanbase by 1% per forum
	-multiplies efficiency of forum by 0.6% per forum
	-named Improved Fanbase Forum
	-picture : http://i.imgur.com/Vw0wggm.png
	*fanbaseAndForumUpgrade6
	-"Fanbases are 1% more efficient for each forum, and forums are 1% more efficient for each fanbase.<br><i></i>
	-costs 2e+31 code
	-unlocks at 500 fanbase, 500 forum
	-multiplies efficiency of fanbase by 1% per forum
	-multiplies efficiency of forum by 1% per forum
	-named Joint Fanbase-Forum Ascension
	-picture : http://i.imgur.com/MBLIRVz.png
	*advertiseUpgrade1
	-"Advertisements give <b>20%</b> more code. <br><i> The ads were poorly designed before. We should add better design to them. </i>"
	-costs 400000000000 code
	-unlocks at 1 advertise
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of highReviewer by 120%
	-named Better design
	-picture : http://i.imgur.com/G3xMef4.png
	*advertiseUpgrade2
	-"Advertisements give <b>50%</b> more code. <br><i> The games previously got a mere 3/5. Now the scores have increased. </i>"
	-costs 1000000000000 code
	-costs 10 positiveReview
	-unlocks at 10 advertise
	-multiplies efficiency of advertise by 150%
	-multiplies efficiency of highReviewer by 150%
	-named Higher review scores
	-picture : http://i.imgur.com/xGf7dpa.png
	*advertiseUpgrade3
	-"Advertisements give <b>twice</b> as much code. <br><i> The people who sit at the TV most of the day now know about your game, so this is a good thing. </i>"
	-costs 3000000000000 code
	-unlocks at 20 advertise
	-multiplies efficiency of advertise by 200%
	-multiplies efficiency of highReviewer by 200%
	-named TV ads
	-picture : http://i.imgur.com/hERi3O0.png
	*advertiseUpgrade4
	-"Advertisements give <b>twice</b> as much code. <br><i> A nice slogan to go with your game company. Definitely a good idea. </i>"
	-costs 20000000000000 code
	-unlocks at 40 advertise
	-multiplies efficiency of advertise by 200%
	-multiplies efficiency of highReviewer by 200%
	-named Advertising slogans
	-picture : http://i.imgur.com/SQg31MR.png
	*advertiseUpgrade5
	-"Advertisements give <b>twice</b> as much code. <br><i> People didn't notice them much, so let's make them visually attractive. </i>"
	-costs 1500000000000000 code
	-unlocks at 80 advertise
	-multiplies efficiency of advertise by 200%
	-multiplies efficiency of highReviewer by 200%
	-named Visually attractive ads
	-picture : http://i.imgur.com/DSQIXVX.png
	*advertiseUpgrade6
	-"Advertisements give <b>2.5 times</b> as much code. <br> <i> ''best ever 5/5'' </i>"
	-costs 20000000000000000 code
	-unlocks at 100 advertise
	-multiplies efficiency of advertise by 250%
	-multiplies efficiency of highReviewer by 250%
	-named Top-score ads
	-picture : http://i.imgur.com/11YIDvf.png
	*advertiseUpgrade7
	-"Advertisements give <b>3 times</b> as much code.<br> <i> 5/5 ratings from a number of critics. </i>"
	-costs 5e+18 code
	-unlocks at 150 advertise
	-multiplies efficiency of advertise by 300%
	-multiplies efficiency of highReviewer by 300%
	-named Multiple top scores
	-picture : http://i.imgur.com/xTUTG6C.png
	*advertiseUpgrade8
	-"Advertisements give <b>3.5 times</b> as much code.<br> <i> This design is almost perfection... </i>"
	-costs 5e+20 code
	-unlocks at 200 advertise
	-multiplies efficiency of advertise by 350%
	-multiplies efficiency of highReviewer by 350%
	-named Near-flawless design
	-picture : http://i.imgur.com/CnQ34cp.png
	*advertiseUpgrade9
	-"Advertisements give <b>4 times</b> as much code.<br> <i> How can you miss them now? </i>"
	-costs 5e+22 code
	-unlocks at 250 advertise
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of highReviewer by 400%
	-named Unmissable ads
	-picture : http://i.imgur.com/GQRHykX.png
	*advertiseUpgrade10
	-"Advertisements give <b>4.5 times</b> as much code.<br> <i> These are the best reviews that exist on this planet... and they go to... your games. </i>"
	-costs 1e+25 code
	-unlocks at 300 advertise
	-multiplies efficiency of advertise by 450%
	-multiplies efficiency of highReviewer by 450%
	-named The Best Reviews
	-picture : http://i.imgur.com/anJKSUy.png
	*advertiseUpgrade11
	-"Advertisements give <b>5 times</b> as much code.<br> <i> They said perfection was impossible. Today we prove them wrong. </i>"
	-costs 2e+27 code
	-unlocks at 350 advertise
	-multiplies efficiency of advertise by 500%
	-multiplies efficiency of highReviewer by 500%
	-named The Flawless Design
	-picture : http://i.imgur.com/hZp8brX.png
	*advertiseUpgrade12
	-"Advertisements give <b>6 times</b> as much code.<br> <i> These ads give off a strange substance that makes you immediately buy your games. It might not be legal... but when the cops came round, they rushed off to buy your game. They're addicted now. They also got fired. </i>"
	-costs 5e+29 code
	-unlocks at 400 advertise
	-multiplies efficiency of advertise by 600%
	-multiplies efficiency of highReviewer by 600%
	-named Forcing ads
	-picture : http://i.imgur.com/zHke2OE.png
	*advertiseUpgrade13
	-"Advertisements give <b>7 times</b> as much code.<br> <i> Your ads have replaced every other single ad there is. Your ads are resulting in the others struggling to advertise now, but it also results in literally everyone over 10 years old in the home country to start playing your games. </i>"
	-costs 5e+31 code
	-unlocks at 450 advertise
	-multiplies efficiency of advertise by 700%
	-multiplies efficiency of highReviewer by 700%
	-named Ads replacing other ads
	-picture : http://i.imgur.com/YpL525v.png
        *advertiseUpgrade14
        -"Advertisements write <b>1%</b> more code for each advertisement. <br><i></i>"
        -costs 8e+33 code
        -unlocks at 500 advertise
        -multiplies efficiency of advertise by 1% per advertise
        -named Advertisements Ascension
	-picture : http://i.imgur.com/bdMGtEv.png
        *advertiseUpgrade15
        -"Advertisements write <b>1%</b> more code for each advertisement. <br><i></i>"
        -costs 1.5e+38 code
        -unlocks at 600 advertise
        -multiplies efficiency of advertise by 1% per advertise
        -named Advertisements Ascension Type Alpha
	-picture : http://i.imgur.com/bdMGtEv.png
        *advertiseUpgrade16
        -"Advertisements write <b>1%</b> more code for each advertisement. <br><i></i>"
        -costs 4e+42 code
        -unlocks at 700 advertise
        -multiplies efficiency of advertise by 1% per advertise
        -named Advertisements Ascension Type Beta
	-picture : http://i.imgur.com/bdMGtEv.png
        *advertiseUpgrade17
        -"Advertisements write <b>1%</b> more code for each advertisement. <br><i></i>"
        -costs 1e+47 code
        -unlocks at 800 advertise
        -multiplies efficiency of advertise by 1% per advertise
        -named Advertisements Ascension Type Gamma
	-picture : http://i.imgur.com/bdMGtEv.png
	*adAndConverter1
	-"Advertisements are 3% more efficient for each magic point converter, and magic point converters are 3% more efficient for each fanbase.<br><i>The ads now tell others to work at the magic point converters. Some come along every so often.</i>
	-costs 8e+12 code
	-unlocks at 40 magicPointBuilding, 40 advertise
	-multiplies efficiency of advertise by 3% per magicPointBuilding
	-multiplies efficiency of magicPointBuilding by 3% per advertise
	-named Recruiting Ads
	-picture : http://i.imgur.com/iuN7O8k.png
	*adAndConverter2
	-"Advertisements are 2% more efficient for each magic point converter, and magic point converters are 2% more efficient for each fanbase.<br><i>The ads now encourage others by listing the benefits of working there./i>
	-costs 8e+12 code
	-unlocks at 120 magicPointBuilding, 120 advertise
	-multiplies efficiency of advertise by 2% per magicPointBuilding
	-multiplies efficiency of magicPointBuilding by 2% per advertise
	-named Encouraging ads
	-picture : http://i.imgur.com/IbNeEhS.png
	*adAndConverter3
	-"Advertisements are 1.5% more efficient for each magic point converter, and magic point converters are 1.5% more efficient for each fanbase.<br><i>We can enhance them as we did with the game ads.</i>
	-costs 8e+12 code
	-unlocks at 200 magicPointBuilding, 200 advertise
	-multiplies efficiency of advertise by 1.5% per magicPointBuilding
	-multiplies efficiency of magicPointBuilding by 1.5% per advertise
	-named Enhanced recruiting ads
	-picture : http://i.imgur.com/LYJNZfS.png
	*adAndConverter4
	-"Advertisements are 1% more efficient for each magic point converter, and magic point converters are 1% more efficient for each fanbase.<br><i>It used to be dangerous working at the converters. It's now safer for workers.</i>
	-costs 8e+12 code
	-unlocks at 300 magicPointBuilding, 300 advertise
	-multiplies efficiency of advertise by 1% per magicPointBuilding
	-multiplies efficiency of magicPointBuilding by 1% per advertise
	-named Reduced danger
	-picture : http://i.imgur.com/jnCwZlJ.png
	*adAndConverter5
	-"Advertisements are 0.5% more efficient for each magic point converter, and magic point converters are 0.5% more efficient for each fanbase.<br><i>People come along really often, and help produce maximum magic.</i>
	-costs 8e+12 code
	-unlocks at 400 magicPointBuilding, 400 advertise
	-multiplies efficiency of advertise by 0.5% per magicPointBuilding
	-multiplies efficiency of magicPointBuilding by 0.5% per advertise
	-named Rapid hire
	-picture : http://i.imgur.com/yqStNi9.png
	*adAndConverter6
	-"Advertisements are 1% more efficient for each magic point converter, and magic point converters are 1% more efficient for each fanbase.<br><i></i>
	-costs 8e+12 code
	-unlocks at 500 magicPointBuilding, 500 advertise
	-multiplies efficiency of advertise by 1% per magicPointBuilding
	-multiplies efficiency of magicPointBuilding by 1% per advertise
	-named Joint Advertisement-Converter ascension
	-picture : http://i.imgur.com/zgqeWSf.png
	*studioUpgrade1
	-"Studios give <b>20%</b> more code. <br><i> To protect against natural events that could damage your game studio. </i>"
	-costs 9999999999999 code
	-unlocks at 1 studio
	-multiplies efficiency of studio by 120%
	-named Studio Reinforcements
	-picture : http://i.imgur.com/cTTotVI.png
	*studioUpgrade2
	-"Studios give <b>50%</b> more code. <br><i> God damn terrorists kept knocking down our stupid studios. <br><br>EDIT: Also, Developer Bakanium was seen attempting to blow up a studio. He is banned from all studios for seven days.</i>"
	-costs 29999999999999 code
	-unlocks at 10 studio
	-multiplies efficiency of studio by 150%
	-named Bomb-proof walls
	-picture : http://i.imgur.com/c5Cm2AV.png
	*studioUpgrade3
	-"Studios give <b>twice</b> as much code. <br><i> Lots of people are being recruited to design your game now. </i>"
	-costs 69999999999999 code
	-unlocks at 20 studio
	-multiplies efficiency of studio by 200%
	-named Better Recruitment
	-picture : http://i.imgur.com/aol0fVB.png
	*studioUpgrade4
	-"Studios give <b>twice</b> as much code. <br><i> A place where people come up with good ideas. </i>"
	-costs 599999999999999 code
	-unlocks at 40 studio
	-multiplies efficiency of studio by 200%
	-named Idea Facility
	-picture : http://i.imgur.com/bWzqzRW.png
	*studioUpgrade5
	-"Studios give <b>twice</b> as much code. <br><i> We have made a lot of money from our studios, which is pretty nice.<br><br>"Let's spend it all on decorations." ~Developer Bakanium </i>"
	-costs 3999999999999999 code
	-unlocks at 80 studio
	-multiplies efficiency of studio by 200%
	-named Lots of money
	-picture : http://i.imgur.com/O2sWdYC.png
	*studioUpgrade6
	-"Studios give <b>twice</b> as much code. <br><i> We can filter all the noobs out from recruitment now. </i>"
	-costs 39999999999999999 code
	-unlocks at 100 studio
	-multiplies efficiency of studio by 200%
	-named Noob-filtering recruitment
	-picture : http://i.imgur.com/bLWNW8d.png
	*studioUpgrade7
	-"Studios give <b>twice</b> as much code. <br><i> Winter is coming. Better upgrade your central heating system, or it will become too cold to work. <br><br>"Game of Thrones fucking sucks." ~Developer Kezelwal</i>"
	-costs 3999999999999999999 code
	-unlocks at 150 studio
	-multiplies efficiency of studio by 200%
	-named Better Heating
	-picture : http://i.imgur.com/kZeLWAl.png
	*studioUpgrade8
	-"Studios give <b>2.5 times</b> as much code. <br><i> Simply more comfortable. </i>"
	-costs 899999999999999999999 code
	-unlocks at 200 studio
	-multiplies efficiency of studio by 250%
	-named Better Workplace
	-picture : http://i.imgur.com/3nms1lh.png
	*studioUpgrade9
	-"Studios give <b>2.5 times</b> as much code. <br><i> They help build studios and maintain them. </i>"
	-costs 4e+23 code
	-unlocks at 250 studio
	-multiplies efficiency of studio by 250%
	-named Studio Engineers
	-picture : http://i.imgur.com/hntfWvV.png
	*studioUpgrade10
	-"Studios give <b>3 times</b> as much code. <br><i> To help improve the design of the studios. </i>"
	-costs 6e+25 code
	-unlocks at 300 studio
	-multiplies efficiency of studio by 300%
	-named Studio Architects
	-picture : http://i.imgur.com/QP6SzH3.png
	*studioUpgrade11
	-"Studios give <b>3 times</b> as much code. <br><i> You don't need to worry about the studio getting damaged. It repairs itself now. </i>"
	-costs 1e+28 code
	-unlocks at 350 studio
	-multiplies efficiency of studio by 300%
	-named Self-repairing studios
	-picture : http://i.imgur.com/EDB5L2x.png
	*studioUpgrade12
	-"Studios give <b>4 times</b> as much code. <br><i> We finally have the money to afford them. Now people are making jokes "(game company) called. They want their computer back." <br><br>RULES<br>1. Developer Bakanium is banned from using the supercomputers.</i>"
	-costs 1.5e+30 code
	-unlocks at 400 studio
	-multiplies efficiency of studio by 400%
	-named Supercomputers
	-picture : http://i.imgur.com/YabayLO.png
	*studioUpgrade13
	-"Studios give <b>5 times</b> as much code. <br><i> Maximum comfort, maximum efficiency, maximum design, maximum lots of other things. </i>"
	-costs 2.25e+32 code
	-unlocks at 450 studio
	-multiplies efficiency of studio by 500%
	-named The best game studios
	-picture : http://i.imgur.com/r1F3Ah9.png
        *studioUpgrade14
        -"Studios write <b>1%</b> more code for each studio. <br><i></i>"
        -costs 4e+34 code
        -unlocks at 500 studio
        -multiplies efficiency of studio by 1% per studio
        -named Studio Ascension
	-picture : http://i.imgur.com/81puUgR.png
        *studioUpgrade15
        -"Studios write <b>1%</b> more code for each studio. <br><i></i>"
        -costs 1e+39 code
        -unlocks at 600 studio
        -multiplies efficiency of studio by 1% per studio
        -named Studio Ascension Type Alpha
	-picture : http://i.imgur.com/81puUgR.png
        *studioUpgrade16
        -"Studios write <b>1%</b> more code for each studio. <br><i></i>"
        -costs 2.25e+43 code
        -unlocks at 700 studio
        -multiplies efficiency of studio by 1% per studio
        -named Studio Ascension Type Beta
	-picture : http://i.imgur.com/81puUgR.png
        *studioUpgrade17
        -"Studios write <b>1%</b> more code for each studio. <br><i></i>"
        -costs 6e+47 code
        -unlocks at 800 studio
        -multiplies efficiency of studio by 1% per studio
        -named Studio Ascension Type Gamma
	-picture : http://i.imgur.com/81puUgR.png
	*magicUpgrade1
	-"Magic code writers give <b>20%</b> more code. <br><i> Their spells kept failing. With a bit of teaching, our magic code writers </i>"
	-costs 87654321234567 code
	-requires 1 researchTime2
	-unlocks at 1 magic
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of magicPointBuilding by 120%
	-named Successful spells
	-picture : http://i.imgur.com/SF8q1Sj.png
	*magicUpgrade2
	-"Magic code writers give <b>50%</b> more code. <br><i> Now they can cast spells faster. </i>"
	-costs 212345678909876 code
	-requires 60 researchTime2
	-unlocks at 10 magic
	-multiplies efficiency of magic by 150%
	-multiplies efficiency of magicPointBuilding by 150%
	-named Faster Spells
	-picture : http://i.imgur.com/zW5C2IF.png
	*magicUpgrade3
	-"Magic code writers give <b>twice</b> as much code. <br><i> Their spells now produce more code than before! </i>"
	-costs 876543212345678 code
	-requires 300 researchTime2
	-unlocks at 20 magic
	-multiplies efficiency of magic by 200%
	-multiplies efficiency of magicPointBuilding by 200%
	-named Larger code quantities
	-picture : http://i.imgur.com/KOpw4Pz.png
	*magicUpgrade4
	-"Magic code writers give <b>twice</b> as much code. Objects give 50% more code. <br><i>They can summon objects now, resulting in a lot more code.</i>"
	-costs 5432123456789098 code
	-unlocks at 40 magic
	-requires 600 researchTime2
	-multiplies efficiency of magic by 200%
	-multiplies efficiency of object by 150%
	-multiplies efficiency of magicPointBuilding by 200%
	-named Object summoning
	-picture : http://i.imgur.com/BTeWu3v.png
	*magicUpgrade5
	-"Magic code writers give <b>twice</b> as much code. <br><i> WOAH CODE EVERYWHERE</i>"
	-costs 321234567890987654 code
	-requires 1800 researchTime2
	-unlocks at 80 magic
	-multiplies efficiency of magic by 200%
	-multiplies efficiency of magicPointBuilding by 200%
	-named Code Explosions
	-picture : http://i.imgur.com/7dw1ecy.png
	*magicUpgrade6
	-"Magic code writers give <b>twice</b> as much code. <br><i>We finally get their accuracy to be perfect. At last. </i>"
	-costs 3212345678909876543 code
	-requires 3600 researchTime2
	-unlocks at 100 magic
	-multiplies efficiency of magic by 200%
	-multiplies efficiency of magicPointBuilding by 200%
	-named Perfect accuracy
	-picture : http://i.imgur.com/0fP30EG.png
	*magicUpgrade7
	-"Magic code writers give <b>twice</b> as much code. <br><i> We discovered that they can potentially cast three spells at once. And it's working!</i>"
	-costs 2e+20 code
	-requires 7200 researchTime2
	-unlocks at 150 magic
	-multiplies efficiency of magic by 200%
	-multiplies efficiency of magicPointBuilding by 200%
	-named Triple spells
	-picture : http://i.imgur.com/M2dZlGq.png
	*magicUpgrade8
	-"Magic code writers give <b>twice</b> as much code. <br><i> The wizards can now shoot spells out of guns, and they shoot pretty quickly.</i>"
	-costs 3e+22 code
	-requires 43200 researchTime2
	-unlocks at 200 magic
	-multiplies efficiency of magic by 200%
	-multiplies efficiency of magicPointBuilding by 200%
	-named Spell Guns
	-picture : http://i.imgur.com/m514Xqw.png
	*magicUpgrade9
	-"Magic code writers give <b>2.5 times</b> as much code. <br><i> They shoot spells REALLY fast.</i>"
	-costs 4e+24 code
	-requires 86400 researchTime2
	-unlocks at 250 magic
	-multiplies efficiency of magic by 250%
	-multiplies efficiency of magicPointBuilding by 250%
	-named Machine guns
	-picture : http://i.imgur.com/VYUi2A5.png
	*magicUpgrade10
	-"Magic code writers give <b>2.5 times</b> as much code. <br><i> To make the machine guns even faster.</i>"
	-costs 6e+26 code
	-requires 200000 researchTime2
	-unlocks at 300 magic
	-multiplies efficiency of magic by 250%
	-multiplies efficiency of magicPointBuilding by 250%
	-named Magically Enhanced Machine Guns
	-picture : http://i.imgur.com/hce7Ula.png
	*magicUpgrade11
	-"Magic code writers give <b>3 times</b> as much code. <br><i> The magic code writers are of an advanced level now, and are therefore more powerful.</i>"
	-costs 1e+29 code
	-requires 400000 researchTime2
	-unlocks at 350 magic
	-multiplies efficiency of magic by 300%
	-multiplies efficiency of magicPointBuilding by 300%
	-named Advanced wizards
	-picture : http://i.imgur.com/aRo3B2X.png
	*magicUpgrade12
	-"Magic code writers give <b>4 times</b> as much code. <br><i> The Wizard Lord has been summoned. The spells are immensely powerful, and the end result is code everywhere.</i>"
	-costs 1.5e+32 code
	-requires 800000 researchTime2
	-unlocks at 400 magic
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-named The Wizard Lord
	-picture : http://i.imgur.com/MwZcjBN.png
	*magicUpgrade13
	-"Magic code writers give <b>4 times</b> as much code. <br><i> "Dupe." ~Developer VomitGhost</i>"
	-costs 2.25e+34 code
	-requires 1200000 researchTime2
	-unlocks at 450 magic
	-multiplies efficiency of magic by 500%
	-multiplies efficiency of magicPointBuilding by 500%
	-named Duplication
	-picture : http://i.imgur.com/VWxsHkU.png
        *magicUpgrade14
        -"Magic code writer write <b>1%</b> more code for each magic code writer. <br><i></i>"
        -costs 4e+36 code
	-requires 2000000 researchTime2
        -unlocks at 500 magic
        -multiplies efficiency of magic by 1% per magic
        -named Magic code writer Ascension
	-picture : http://i.imgur.com/gVQGjFF.png
        *magicUpgrade15
        -"Magic code writer write <b>1%</b> more code for each magic code writer. <br><i></i>"
        -costs 1e+41 code
        -unlocks at 600 magic
        -multiplies efficiency of magic by 1% per magic
        -named Magic code writer Ascension Type Alpha
	-picture : http://i.imgur.com/gVQGjFF.png
        *magicUpgrade16
        -"Magic code writer write <b>1%</b> more code for each magic code writer. <br><i></i>"
        -costs 2.25e+45 code
        -unlocks at 700 magic
        -multiplies efficiency of magic by 1% per magic
        -named Magic code writer Ascension Type Beta
	-picture : http://i.imgur.com/gVQGjFF.png
        *magicUpgrade17
        -"Magic code writer write <b>1%</b> more code for each magic code writer. <br><i></i>"
        -costs 6e+49 code
        -unlocks at 800 magic
        -multiplies efficiency of magic by 1% per magic
        -named Magic code writer Ascension Type Gamma
	-picture : http://i.imgur.com/gVQGjFF.png
	*studioAndMagicUpgrade1
	-"Studios are 1% more efficient for each magic code writer, and magic code writers are 2% more efficient for each studio.<br><i>The wizards have managed to enhance your studios with magic, making things more powerful.</i>
	-costs 5e+16 code
	-unlocks at 40 studio, 40 magic
	-multiplies efficiency of studio by 1% per magic
	-multiplies efficiency of magic by 2% per studio
	-named Magical Studios
	-picture : http://i.imgur.com/I08yb5V.png
	*studioAndMagicUpgrade2
	-"Studios are 1% more efficient for each magic code writer, and magic code writers are 2% more efficient for each studio.<br><i>The magic makes your studios invincible. They can't be destroyed anymore.</i>
	-costs 3212345678909876543 code
	-unlocks at 120 studio, 120 magic
	-multiplies efficiency of studio by 1% per magic
	-multiplies efficiency of magic by 2% per studio
	-named Invincible Studios
	-picture : http://i.imgur.com/SXhexMi.png
	*studioAndMagicUpgrade3
	-"Studios are 0.8% more efficient for each magic code writer, and magic code writers are 1% more efficient for each studio.<br><i>Everything in the studio is now magically enhanced, speeding things up a lot.</i>
	-costs 5e+22 code
	-unlocks at 200 studio, 200 magic
	-multiplies efficiency of studio by 0.8% per magic
	-multiplies efficiency of magic by 1% per studio
	-named Super Magic Enhancement
	-picture : http://i.imgur.com/B7wePxB.png
	*studioAndMagicUpgrade4
	-"Studios are 0.5% more efficient for each magic code writer, and magic code writers are 1% more efficient for each studio.<br><i>We should have done this first thing. The magic writers work at your studios now.</i>
	-costs 1e+27 code
	-unlocks at 300 studio, 300 magic
	-multiplies efficiency of studio by 0.5% per magic
	-multiplies efficiency of magic by 1% per studio
	-named Magic Code Writer hiring
	-picture : http://i.imgur.com/Pzn8c4h.png
	*studioAndMagicUpgrade5
	-"Studios are 0.2% more efficient for each magic code writer, and magic code writers are 0.8% more efficient for each studio.<br><i>These spells are the most powerful the wizards can cast on the studios without damaging everything. The spells basically make your studios run at godspeed.</i>
	-costs 5e+32 code
	-unlocks at 400 studio, 400 magic
	-multiplies efficiency of studio by 0.2% per magic
	-multiplies efficiency of magic by 0.8% per studio
	-named Ultimate Magic Enhancement
	-picture : http://i.imgur.com/BcbwnaO.png
	*studioAndMagicUpgrade6
	-"Studios are 1% more efficient for each magic code writer, and magic code writers are 1% more efficient for each studio.<br><i></i>
	-costs 1e+37 code
	-unlocks at 500 studio, 500 magic
	-multiplies efficiency of studio by 1% per magic
	-multiplies efficiency of magic by 1% per studio
	-named Joint Studio-Magic Writer Ascension
	-picture : http://i.imgur.com/09bhntf.png
	*gameSeriesUpgrade1
	-"Game series give <b>20%</b> more code. <br><i> A logical idea. </i>"
	-costs 1750000000000000 code
	-unlocks at 1 gameSeries
	-multiplies efficiency of gameSeries by 120%
	-named Sequels
	-picture : http://i.imgur.com/5mBFGVY.png
	*gameSeriesUpgrade2
	-"Game series give <b>50%</b> more code. <br><i>Now we know what happened before the first game. </i>"
	-costs 5000000000000000 code
	-unlocks at 10 gameSeries
	-multiplies efficiency of gameSeries by 150%
	-named Prequels
	-picture : http://i.imgur.com/yX6y6fG.png
	*gameSeriesUpgrade3
	-"Game series give <b>75%</b> more code. <br><i> Sequels to show what happens after the alternate ending.  </i>"
	-costs 15000000000000000 code
	-unlocks at 20 gameSeries
	-multiplies efficiency of gameSeries by 175%
	-named Alternate Sequels
	-picture : http://i.imgur.com/sGrxpST.png
	*gameSeriesUpgrade4
	-"Game series give <b>twice</b> as much code. <br><i> Games that aren't related to the main storyline. </i>"
	-costs 100000000000000000 code
	-unlocks at 40 gameSeries
	-multiplies efficiency of gameSeries by 200%
	-named Spinoff series
	-picture : http://i.imgur.com/0cduxl9.png
	*gameSeriesUpgrade5
	-"Game series give <b>twice</b> as much code. <br><i> Now we can play the games from a different point of view. </i>"
	-costs 1.5e+18 code
	-unlocks at 80 gameSeries
	-multiplies efficiency of gameSeries by 200%
	-named Different POV games
	-picture : http://i.imgur.com/lwTBZEJ.png
	*gameSeriesUpgrade6
	-"Game series give <b>twice</b> as much code. <br><i> Some of your series are in 2D, and some are in 3D. </i>"
	-costs 1.5e+19 code
	-unlocks at 100 gameSeries
	-multiplies efficiency of gameSeries by 200%
	-named Different dimension series
	-picture : http://i.imgur.com/GgHQitt.png
	*gameSeriesUpgrade7
	-"Game series give <b>twice</b> as much code. <br><i> Your games are getting released to all kinds of consoles now. </i>"
	-costs 2.25e+21 code
	-unlocks at 150 gameSeries
	-multiplies efficiency of gameSeries by 200%
	-named Multi-platform releases
	-picture : http://i.imgur.com/lF2mRqf.png
	*gameSeriesUpgrade8
	-"Game series give <b>twice</b> as much code. <br><i> Your games got ported to PC pretty well. Sadly, they're not on Steam.</i>"
	-costs 4e+23 code
	-unlocks at 200 gameSeries
	-multiplies efficiency of gameSeries by 200%
	-named PC release
	-picture : http://i.imgur.com/gMCecxH.png
	*gameSeriesUpgrade9
	-"Game series give <b>twice</b> as much code. <br><i> Now your games can be played on Steam! </i>"
	-costs 6e+25 code
	-unlocks at 250 gameSeries
	-multiplies efficiency of gameSeries by 200%
	-named Steam release
	-picture : http://i.imgur.com/6SNFsN7.png
	*gameSeriesUpgrade10
	-"Game series give <b>2.5 times</b> as much code. <br><i> Your game series gave a quite complex storyline new, with sequels and prequels and different timelines etc... </i>"
	-costs 1e+28 code
	-unlocks at 300 gameSeries
	-multiplies efficiency of gameSeries by 250%
	-named Complex series
	-picture : http://i.imgur.com/jKMbNeb.png
	*gameSeriesUpgrade11
	-"Game series give <b>3 times</b> as much code. <br><i>All the games in your game series now have reduced lag. </i>"
	-costs 1.5e+30 code
	-unlocks at 350 gameSeries
	-multiplies efficiency of gameSeries by 300%
	-named Reduced lag
	-picture : http://i.imgur.com/4ZhRJnE.png
	*gameSeriesUpgrade12
	-"Game series give <b>4 times</b> as much code. <br><i> Pretty much no lag. Neat. </i>"
	-costs 2.25e+32 code
	-unlocks at 400 gameSeries
	-multiplies efficiency of gameSeries by 400%
	-named No lag
	-picture : http://i.imgur.com/Z8pfhaR.png
	*gameSeriesUpgrade13
	-"Game series give <b>4 times</b> as much code. <br><i> There was still a bit of lag. Now there is LITERALLY none. </i>"
	-costs 4e+34 code
	-unlocks at 450 gameSeries
	-multiplies efficiency of gameSeries by 400%
	-named Literally no lag
	-picture : http://i.imgur.com/vD7yBye.png
        *gameSeriesUpgrade14
        -"Game series write <b>1%</b> more code for each game series. <br><i></i>"
        -costs 6e+36 code
        -unlocks at 500 gameSeries
        -multiplies efficiency of gameSeries by 1% per gameSeries
        -named Game Series Ascension
	-picture : http://i.imgur.com/VtQiwJv.png
        *gameSeriesUpgrade15
        -"Game series write <b>1%</b> more code for each game series. <br><i></i>"
        -costs 1.5e+41 code
        -unlocks at 600 gameSeries
        -multiplies efficiency of gameSeries by 1% per gameSeries
        -named Game Series Ascension Type Alpha
	-picture : http://i.imgur.com/VtQiwJv.png
        *gameSeriesUpgrade16
        -"Game series write <b>1%</b> more code for each game series. <br><i></i>"
        -costs 4e+45 code
        -unlocks at 700 gameSeries
        -multiplies efficiency of gameSeries by 1% per gameSeries
        -named Game Series Ascension Type Beta
	-picture : http://i.imgur.com/VtQiwJv.png
        *gameSeriesUpgrade17
        -"Game series write <b>1%</b> more code for each game series. <br><i></i>"
        -costs 1e+50 code
        -unlocks at 800 gameSeries
        -multiplies efficiency of gameSeries by 1% per gameSeries
        -named Game Series Ascension Type Gamma
	-picture : http://i.imgur.com/VtQiwJv.png
	*maganiumUpgrade1
	-"Ultra-magic generators give <b>20%</b> more code. <br><i> The engines were bad before. We can improve them.</i>"
	-costs 8666666666666666 code
	-requires 1 researchTime3
	-unlocks at 1 maganiumGenerator
	-multiplies efficiency of maganiumGenerator by 120%
	-named Better Engines
	-picture : http://i.imgur.com/lZnr4yP.png
	*maganiumUpgrade2
	-"Ultra-magic generators give <b>50%</b> more code. <br><i>It takes a while to start up, so reducing the crash rate is a good idea.</i>"
	-costs 26666666666666666 code
	-requires 60 researchTime3
	-unlocks at 10 maganiumGenerator
	-multiplies efficiency of maganiumGenerator by 150%
	-named Reduced crash rate
	-picture : http://i.imgur.com/PxabiAG.png
	*maganiumUpgrade3
	-"Ultra-magic generators give <b>twice</b> as much code. <br><i> Generally generates code quicker. </i>"
	-costs 86666666666666666 code
	-requires 300 researchTime3
	-unlocks at 20 maganiumGenerator
	-multiplies efficiency of maganiumGenerator by 200%
	-named Improved performance
	-picture : http://i.imgur.com/hcOXGTT.png
	*maganiumUpgrade4
	-"Ultra-magic generators give <b>twice</b> as much code. <br><i>It would be a disaster if one exploded. Making them safer would be great.</i>"
	-costs 566666666666666666 code
	-requires 600 researchTime3
	-unlocks at 40 maganiumGenerator
	-multiplies efficiency of maganiumGenerator by 200%
	-named Safer generators
	-picture : http://i.imgur.com/9dOu13u.png
	*maganiumUpgrade5
	-"Ultra-magic generators give <b>twice</b> as much code. <br><i>More code per generation.</i>"
	-costs 36666666666666666666 code
	-requires 1800 researchTime3
	-unlocks at 80 maganiumGenerator
	-multiplies efficiency of maganiumGenerator by 200%
	-named Bigger generations
	-picture : http://i.imgur.com/mYxqOfq.png
	*maganiumUpgrade6
	-"Ultra-magic generators give <b>twice</b> as much code. <br><i>There's a vast ultra-magic supply deep underground. If we get it, we can enhance our generators with it.</i>"
	-costs 366666666666666666666 code
	-requires 3600 researchTime3
	-unlocks at 100 maganiumGenerator
	-multiplies efficiency of maganiumGenerator by 200%
	-named Ultra-magic supply
	-picture : http://i.imgur.com/Ntlp4OT.png
	*maganiumUpgrade7
	-"Ultra-magic generators give <b>twice</b> as much code. <br><i> Takes longer to run out.</i>"
	-costs 2.66666e+22 code
	-requires 7200 researchTime3
	-unlocks at 150 maganiumGenerator
	-multiplies efficiency of maganiumGenerator by 200%
	-named Efficient ultra-magic usage
	-picture : http://i.imgur.com/dEIKIcN.pnghttp://i.imgur.com/dEIKIcN.png
	*maganiumUpgrade8
	-"Ultra-magic generators give <b>twice</b> as much code. <br><i>Ultra-magic in its pure form. Much better.</i>"
	-costs 3.66666e+24 code
	-requires 14400 researchTime3
	-unlocks at 200 maganiumGenerator
	-multiplies efficiency of maganiumGenerator by 200%
	-named Pure ultra-magic
	-picture : http://i.imgur.com/sCHapZj.png
	*maganiumUpgrade9
	-"Ultra-magic generators give <b>twice</b> as much code. <br><i>They maintain the generators to make sure nothing bad happens.</i>"
	-costs 4.66666e+26 code
	-requires 43200 researchTime3
	-unlocks at 250 maganiumGenerator
	-multiplies efficiency of maganiumGenerator by 200%
	-named Generator maintainers
	-picture : http://i.imgur.com/rxq5SCL.png
	*maganiumUpgrade10
	-"Ultra-magic generators give <b>twice</b> as much code. <br><i> Previously, we only got 40% - 60% of potential. Now we get 100%!</i>"
	-costs 6.66666e+28 code
	-requires 86400 researchTime3
	-unlocks at 300 maganiumGenerator
	-multiplies efficiency of maganiumGenerator by 200%
	-named Perfect generation
	-picture : http://i.imgur.com/tvNLXM8.png
	*maganiumUpgrade11
	-"Ultra-magic generators give <b>3 times</b> as much code. <br><i> They generate code at speeds never seen before.</i>"
	-costs 1.66666e+31 code
	-requires 200000 researchTime3
	-unlocks at 350 maganiumGenerator
	-multiplies efficiency of maganiumGenerator by 300%
	-named Ridiculously fast generation
	-picture : http://i.imgur.com/GPMu987.png
	*maganiumUpgrade12
	-"Ultra-magic generators give <b>4 times</b> as much code. <br><i> Each new generator now has four times the power as an old one!</i>"
	-costs 2.66666e+33 code
	-requires 400000 researchTime3
	-unlocks at 400 maganiumGenerator
	-multiplies efficiency of maganiumGenerator by 400%
	-named Larger generators
	-picture : http://i.imgur.com/wQe3mbu.png
	*maganiumUpgrade13
	-"Ultra-magic generators give <b>4 times</b> as much code. <br><i> They run 24-7, never crash, and will continue generating until the end of time.</i>"
	-costs 3.66666e+36 code
	-requires 800000 researchTime3
	-unlocks at 450 maganiumGenerator
	-multiplies efficiency of maganiumGenerator by 400%
	-named Infinite Generation
	-picture : http://i.imgur.com/v8W1oI3.png
        *maganiumUpgrade14
        -"Ultra-magic generators write <b>1%</b> more code for each ultra-magic generator. <br><i></i>"
        -costs 4.66666e+38 code
	-requires 1200000 researchTime3
        -unlocks at 500 maganiumGenerator
        -multiplies efficiency of maganiumGenerator by 1% per maganiumGenerator
        -named Ultra-magic Generator Ascension
	-picture : http://i.imgur.com/gT0CLNz.png
        *maganiumUpgrade15
        -"Ultra-magic generators write <b>1%</b> more code for each ultra-magic generator. <br><i></i>"
        -costs 1e+43 code
        -unlocks at 600 maganiumGenerator
        -multiplies efficiency of maganiumGenerator by 1% per maganiumGenerator
        -named Ultra-magic Generator Ascension Type Alpha
	-picture : http://i.imgur.com/gT0CLNz.png
        *maganiumUpgrade16
        -"Ultra-magic generators write <b>1%</b> more code for each ultra-magic generator. <br><i></i>"
        -costs 2.25e+47 code
        -unlocks at 700 maganiumGenerator
        -multiplies efficiency of maganiumGenerator by 1% per maganiumGenerator
        -named Ultra-magic Generator Ascension Type Beta
	-picture : http://i.imgur.com/gT0CLNz.png
        *maganiumUpgrade17
        -"Ultra-magic generators write <b>1%</b> more code for each ultra-magic generator. <br><i></i>"
        -costs 6e+51 code
        -unlocks at 800 maganiumGenerator
        -multiplies efficiency of maganiumGenerator by 1% per maganiumGenerator
        -named Ultra-magic Generator Ascension Type Gamma
	-picture : http://i.imgur.com/gT0CLNz.png
	*popularYoutuberUpgrade1
	-"Popular YouTubers give <b>20%</b> more code. <br><i> Popular YouTubers are now encouraging fans to play your games. </i>"
	-costs 40000000000000000 code
	-unlocks at 1 popularYoutuber
	-multiplies efficiency of popularYoutuber by 120%
	-named Encouragement
	-picture : http://i.imgur.com/FFxM1vH.png
	*popularYoutuberUpgrade2
	-"Popular YouTubers give <b>50%</b> more code. <br><i> The YouTubers are now famous, and are known by a lot of people. </i>"
	-costs 120000000000000000 code
	-unlocks at 10 popularYoutuber
	-multiplies efficiency of popularYoutuber by 150%
	-named Famous YouTubers
	-picture : http://i.imgur.com/n3P1zLk.png
	*popularYoutuberUpgrade3
	-"Popular YouTubers give <b>75%</b> more code. <br><i> The YouTubers give your games good reviews, encouraging more people to play your games. </i>"
	-costs 4e+16 code
	-unlocks at 20 popularYoutuber
	-multiplies efficiency of popularYoutuber by 175%
	-named Good-Review YouTubers
	-picture : http://i.imgur.com/m4oiISC.png
	*popularYoutuberUpgrade4
	-"Popular YouTubers give <b>twice</b> as much code. <br><i> Your popular YouTubers now have fanbases that try to encourage others to play. </i>"
	-costs 1e+18 code
	-unlocks at 40 popularYoutuber
	-multiplies efficiency of popularYoutuber by 200%
	-named YouTuber fanbases
	-picture : http://i.imgur.com/xvLoGVZ.png
	*popularYoutuberUpgrade5
	-"Popular YouTubers give <b>twice</b> as much code. <br><i> Guess what? Your fanbases were full of pricks. Now that the pricks are no longer pricks, people are more willing to play your games. </i>"
	-costs 1.5e+20 code
	-unlocks at 80 popularYoutuber
	-multiplies efficiency of popularYoutuber by 200%
	-named Better YouTuber Fanbases
	-picture : http://i.imgur.com/pMMqjYT.png
	*popularYoutuberUpgrade6
	-"Popular YouTubers give <b>twice</b> as much code. <br><i> The fanbases can help you write code for you now. </i>"
	-costs 2.25e+22 code
	-unlocks at 100 popularYoutuber
	-multiplies efficiency of popularYoutuber by 200%
	-named Helpful YouTuber fanbases
	-picture : http://i.imgur.com/lKIH7qf.png
	*popularYoutuberUpgrade7
	-"Popular YouTubers give <b>twice</b> as much code. <br><i> The most popular YouTubers on YouTube are now playing your games. </i>"
	-costs 4e+24 code
	-unlocks at 150 popularYoutuber
	-multiplies efficiency of popularYoutuber by 200%
	-named The Most Popular YouTubers
	-picture : http://i.imgur.com/pQDR2JR.png
	*popularYoutuberUpgrade8
	-"Popular YouTubers give <b>twice</b> as much code. <br><i>They now give various tips and tricks for your games. </i>"
	-costs 6e+26 code
	-unlocks at 200 popularYoutuber
	-multiplies efficiency of popularYoutuber by 200%
	-named Tips and Tricks
	-picture : http://i.imgur.com/VEYLmFl.png
	*popularYoutuberUpgrade9
	-"Popular YouTubers give <b>twice</b> as much code. <br><i> To help the newbs in their game. </i>"
	-costs 1e+29 code
	-unlocks at 250 popularYoutuber
	-multiplies efficiency of popularYoutuber by 200%
	-named Walkthroughs
	-picture : http://i.imgur.com/y3raVwG.png
	*popularYoutuberUpgrade10
	-"Popular YouTubers give <b>twice</b> as much code. <br><i> Now the experts receive advanced tips that make them even better. </i>"
	-costs 1.5e+31 code
	-unlocks at 300 popularYoutuber
	-multiplies efficiency of popularYoutuber by 200%
	-named Expert tips
	-picture : http://i.imgur.com/b5kjyCF.png
	*popularYoutuberUpgrade11
	-"Popular YouTubers give <b>2.5 times</b> as much code. <br><i> They now review your games. And they're generally pretty good. </i>"
	-costs 2.25e+33 code
	-unlocks at 350 popularYoutuber
	-multiplies efficiency of popularYoutuber by 250%
	-named Reviews
	-picture : http://i.imgur.com/ihZbL4Y.png
	*popularYoutuberUpgrade12
	-"Popular YouTubers give <b>3 times</b> as much code. <br><i> The YouTubers now tell everyone to buy your games, no matter what. And 99% of them do. </i>"
	-costs 4e+35 code
	-unlocks at 400 popularYoutuber
	-multiplies efficiency of popularYoutuber by 300%
	-named Ultimate Encouragement
	-picture : http://i.imgur.com/1WtCgn0.png
	*popularYoutuberUpgrade13
	-"Popular YouTubers give <b>3.5 times</b> as much code. <br><i> The 1% that wouldn't play your games are now playing your games thanks to this encouragement. And now the encouraged people encourage others to play your game, which encourage others to play your game, which...</i>"
	-costs 6e+37 code
	-unlocks at 450 popularYoutuber
	-multiplies efficiency of popularYoutuber by 350%
	-named Ultimate Encouragement (for real)
	-picture : http://i.imgur.com/H3azM4T.png
        *popularYoutuberUpgrade14
        -"Popular YouTubers write <b>1%</b> more code for each popular YouTuber. <br><i></i>"
        -costs 1e+40 code
        -unlocks at 500 popularYoutuber
        -multiplies efficiency of popularYoutuber by 1% per popularYoutuber
        -named Popular YouTuber Ascension
	-picture : http://i.imgur.com/DmviIKH.png
        *popularYoutuberUpgrade15
        -"Popular YouTubers write <b>1%</b> more code for each popular YouTuber. <br><i></i>"
        -costs 1.5e+44 code
        -unlocks at 600 popularYoutuber
        -multiplies efficiency of popularYoutuber by 1% per popularYoutuber
        -named Popular YouTuber Ascension Type Alpha
	-picture : http://i.imgur.com/DmviIKH.png
        *popularYoutuberUpgrade16
        -"Popular YouTubers write <b>1%</b> more code for each popular YouTuber. <br><i></i>"
        -costs 2.25e+48 code
        -unlocks at 700 popularYoutuber
        -multiplies efficiency of popularYoutuber by 1% per popularYoutuber
        -named Popular YouTuber Ascension Type Beta
	-picture : http://i.imgur.com/DmviIKH.png
        *popularYoutuberUpgrade17
        -"Popular YouTubers write <b>1%</b> more code for each popular YouTuber. <br><i></i>"
        -costs 4e+52 code
        -unlocks at 800 popularYoutuber
        -multiplies efficiency of popularYoutuber by 1% per popularYoutuber
        -named Popular YouTuber Ascension Type Gamma
	-picture : http://i.imgur.com/DmviIKH.png
	*popularYoutuberandSeriesUpgrade1
	-"Youtubers are 1% more efficient for each series, and series are 1% more efficient for each YouTuber.<br><i>The YouTubers now start playthroughs of your games series.</i>
	-costs 2.5e+18 code
	-unlocks at 40 popularYoutuber, 40 gameSeries
	-multiplies efficiency of popularYoutuber by 1% per gameSeries
	-multiplies efficiency of gameSeries by 1% per popularYoutuber
	-named Series Playthroughs
	-picture : http://i.imgur.com/QgCmS3R.png
	*popularYoutuberandSeriesUpgrade2
	-"Youtubers are 1% more efficient for each series, and series are 1% more efficient for each YouTuber.<br><i>The YouTubers now get their friends to play through your games series with the YouTuber.</i>
	-costs 2.5e+20 code
	-unlocks at 120 popularYoutuber, 120 gameSeries
	-multiplies efficiency of popularYoutuber by 1% per gameSeries
	-multiplies efficiency of gameSeries by 1% per popularYoutuber
	-named Multiplayer Playthroughs
	-picture : http://i.imgur.com/edJMK1z.png
	*popularYoutuberandSeriesUpgrade3
	-"Youtubers are 0.7% more efficient for each series, and series are 0.7% more efficient for each YouTuber.<br><i>The YouTubers have started doing marathon playthroughs of your game series. That'll take a while...</i>
	-costs 1e+25 code
	-unlocks at 200 popularYoutuber, 200 gameSeries
	-multiplies efficiency of popularYoutuber by 0.7% per gameSeries
	-multiplies efficiency of gameSeries by 0.7% per popularYoutuber
	-named Marathon Playthroughs
	-picture : http://i.imgur.com/cyIp93b.png
	*popularYoutuberandSeriesUpgrade4
	-"Youtubers are 3% more efficient for each series, and series are 3% more efficient for each YouTuber.<br><i>The YouTubers now do speedruns of your game series, aiming to complete it in the fastest time possible.</i>
	-costs 1e+30 code
	-unlocks at 300 popularYoutuber, 300 gameSeries
	-multiplies efficiency of popularYoutuber by 0.5% per gameSeries
	-multiplies efficiency of gameSeries by 0.5% per popularYoutuber
	-named Speedrun Playthroughs
	-picture : http://i.imgur.com/Fx0cesP.png
	*popularYoutuberandSeriesUpgrade5
	-"Youtubers are 0.2% more efficient for each series, and series are 0.2% more efficient for each YouTuber.<br><i>The YouTubers finally broke the world record for speedrunning your game series.</i>
	-costs 1e+34 code
	-unlocks at 400 popularYoutuber, 400 gameSeries
	-multiplies efficiency of popularYoutuber by 0.2% per gameSeries
	-multiplies efficiency of gameSeries by 0.2% per popularYoutuber
	-named World Record
	-picture : http://i.imgur.com/bVudbtg.png
	*popularYoutuberandSeriesUpgrade6
	-"Youtubers are 1% more efficient for each series, and series are 1% more efficient for each YouTuber.<br><i>The YouTubers finally broke the world record for speedrunning your game series.</i>
	-costs 2e+38 code
	-unlocks at 500 popularYoutuber, 500 gameSeries
	-multiplies efficiency of popularYoutuber by 1% per gameSeries
	-multiplies efficiency of gameSeries by 1% per popularYoutuber
	-named Joint YouTuber-Series ascension
	-picture : http://i.imgur.com/THPm6Jh.png
	*finalityUpgrade1
	-"Finalities give <b>20%</b> more code. <br><i>There was a secret organisation...</i>"
	-costs 1e+18 code
	-unlocks at 1 finality
	-requires 1 researchTime4
	-multiplies efficiency of finality by 120%
	-named The Secret Organisation
	-picture : http://i.imgur.com/zAJHtxm.png
	*finalityUpgrade2
	-"Finalities give <b>50%</b> more code. <br><i>That had one goal... </i>"
	-costs 3e+18 code
	-requires 60 researchTime4
	-unlocks at 10 finality
	-multiplies efficiency of finality by 150%
	-named The Growing Secret Organisation
	-picture : http://i.imgur.com/UACTea9.png
	*finalityUpgrade3
	-"Finalities give <b>75%</b> more code. <br><i> ...to get everyone in the world to play your games... </i>"
	-costs 8e+18 code
	-requires 300 researchTime4
	-unlocks at 20 finality
	-multiplies efficiency of finality by 175%
	-named Mysterious Secret Organisation
	-picture : http://i.imgur.com/HgvU8jA.png
	*finalityUpgrade4
	-"Finalities give <b>twice</b> as much code. <br><i>...members of this organisation included...</i>"
	-costs 6e+19 code
	-requires 600 researchTime4
	-unlocks at 40 finality
	-multiplies efficiency of finality by 200%
	-named Secret Organisation Members
	-picture : http://i.imgur.com/NdZb73G.png
	*finalityUpgrade5
	-"Finalities give <b>twice</b> as much code. <br><i>...some sort of master of sparks, an entity that gave walkthroughs, flames of dark matter, the fastest of mennest...</i>"
	-costs 4e+21 code
	-requires 1800 researchTime4
	-unlocks at 80 finality
	-multiplies efficiency of finality by 200%
	-named Secret Organisation Member List I
	-picture : http://i.imgur.com/M6PPWZy.png
	*finalityUpgrade6
	-"Finalities give <b>twice</b> as much code. <br><i>...an edible thing that was burnt, a ranger of Death, something that is either dromedary or bactrian that explodes, a team of people that force things to update...</i>"
	-costs 2.25e+23 code
	-requires 3600 researchTime4
	-unlocks at 100 finality
	-multiplies efficiency of finality by 200%
	-named Secret Organisation Member List II
	-picture : http://i.imgur.com/ARHJt56.png
	*finalityUpgrade7
	-"Finalities give <b>twice</b> as much code. <br><i>...the 52nd element, canines in a basket, a spectre that can click, and that which is love, and life.</i>"
	-costs 4e+25 code
	-requires 7200 researchTime4
	-unlocks at 150 finality
	-multiplies efficiency of finality by 200%
	-named Secret Organisation Member List III
	-picture : http://i.imgur.com/6yheSFQ.png
	*finalityUpgrade8
	-"Finalities give <b>twice</b> as much code. <br><i>The Secret Organisation gained power...</i>"
	-costs 6e+27 code
	-requires 14400 researchTime4
	-unlocks at 200 finality
	-multiplies efficiency of finality by 200%
	-named Secret Organisation Power
	-picture : http://i.imgur.com/HOvvD8P.png
	*finalityUpgrade9
	-"Finalities give <b>2.5 times</b> as much code. <br><i>...and in short time...</i>"
	-costs 1e+30 code
	-requires 43200 researchTime4
	-unlocks at 250 finality
	-multiplies efficiency of finality by 250%
	-named Secret Organisation World Power
	-picture : http://i.imgur.com/btKpO6A.png
	*finalityUpgrade10
	-"Finalities give <b>2.5 times</b> as much code. <br><i>...the secret organisation had control of the world.</i>"
	-costs 1.5e+32 code
	-requires 86400 researchTime4
	-unlocks at 300 finality
	-multiplies efficiency of finality by 250%
	-named Secret Organisation World Domination
	-picture : http://i.imgur.com/zIRd4CC.png
	*finalityUpgrade11
	-"Finalities give <b>3 times</b> as much code. <br><i>...one by one, other game franchises started declining... Call of Duty, Sonic...</i>"
	-costs 2.25e+34 code
	-requires 200000 researchTime4
	-unlocks at 350 finality
	-multiplies efficiency of finality by 300%
	-named Secret Organisation Wipeout
	-picture : http://i.imgur.com/ud9LhTf.png
	*finalityUpgrade12
	-"Finalities give <b>4 times</b> as much code. <br><i>GTA, Pokémon and Mario... their sales came to a halt...</i>"
	-costs 4e+36 code
	-requires 400000 researchTime4
	-unlocks at 400 finality
	-multiplies efficiency of finality by 400%
	-named Secret Organisation Total Wipeout
	-picture : http://i.imgur.com/CidwSOT.png
	*finalityUpgrade13
	-"Finalities give <b>4 times</b> as much code. <br><i>...and by the end, your game franchise was the only one left. Every single person knew how to play your games... ...the Finality was finished.</i>"
	-costs 6e+38 code
	-requires 800000 researchTime4
	-unlocks at 450 finality
	-multiplies efficiency of finality by 500%
	-named Secret Organisation Success
	-picture : http://i.imgur.com/FS8glrO.png
        *finalityUpgrade14
        -"Finalities write <b>1%</b> more code for each magic code writer. <br><i>The End.</i>"
        -costs 1e+41 code
	-requires 1200000 researchTime4
        -unlocks at 500 finality
        -multiplies efficiency of finality by 1% per finality
        -named Finality Ascension
	-picture : http://i.imgur.com/XChWrip.png
        *finalityUpgrade15
        -"Finalities write <b>1%</b> more code for each magic code writer. <br><i></i>"
        -costs 1.5e+45 code
        -unlocks at 600 finality
        -multiplies efficiency of finality by 1% per finality
        -named Finality Ascension Type Alpha
	-picture : http://i.imgur.com/XChWrip.png
        *finalityUpgrade16
        -"Finalities write <b>1%</b> more code for each magic code writer. <br><i></i>"
        -costs 6e+49 code
        -unlocks at 700 finality
        -multiplies efficiency of finality by 1% per finality
        -named Finality Ascension Type Beta
	-picture : http://i.imgur.com/XChWrip.png
        *finalityUpgrade17
        -"Finalities write <b>1%</b> more code for each magic code writer. <br><i></i>"
        -costs 1.5e+54 code
        -unlocks at 800 finality
        -multiplies efficiency of finality by 1% per finality
        -named Finality Ascension Type Gamma
	-picture : http://i.imgur.com/XChWrip.png
	*generatorAndFinalityUpgrade1
	-"Generators are 2% more efficient for each finality, and finalities are 2% more efficient for each generator.<br><i>Generators are now being built by the secret organisations, that not only give more code, but help them in world domination,</i>
	-costs 4e+20 code
	-unlocks at 40 maganiumGenerator, 40 finality
	-multiplies efficiency of maganiumGenerator by 2% per finality
	-multiplies efficiency of finality by 2% per maganiumGenerator
	-named Generators of the Secret Organisation
	-picture : http://i.imgur.com/5IQgjSQ.png
	*generatorAndFinalityUpgrade2
	-"Generators are 1.5% more efficient for each finality, and finalities are 1.5% more efficient for each generator.<br><i>The generators are now being maintained by the secret organisation. Occasionally they alter them to benefit the secret organisation.</i>
	-costs 6e+24 code
	-unlocks at 120 maganiumGenerator, 120 finality
	-multiplies efficiency of maganiumGenerator by 1.5% per finality
	-multiplies efficiency of finality by 1.5% per maganiumGenerator
	-named Secret Organisation Helpers
	-picture : http://i.imgur.com/mcApCP2.png
	*generatorAndFinalityUpgrade3
	-"Generators are 1% more efficient for each finality, and finalities are 1% more efficient for each generator.<br><i>The code now contains a strange substance, that not only makes code more powerful, but also helps the organisations.</i>
	-costs 1e+27 code
	-unlocks at 200 maganiumGenerator, 200 finality
	-multiplies efficiency of maganiumGenerator by 1% per finality
	-multiplies efficiency of finality by 1% per maganiumGenerator
	-named Strange Substance
	-picture : http://i.imgur.com/oebeYRX.png
	*generatorAndFinalityUpgrade4
	-"Generators are 0.5% more efficient for each finality, and finalities are 0.5% more efficient for each generator.<br><i>They found a secret code: P53YuLr. Entering this code in all generators will alter everyone that comes near them, and they will only play your games.</i>
	-costs 3e+31 code
	-unlocks at 300 maganiumGenerator, 300 finality
	-multiplies efficiency of maganiumGenerator by 0.5% per finality
	-multiplies efficiency of finality by 0.5% per maganiumGenerator
	-named The secret code
	-picture : http://i.imgur.com/P53YuLr.png
	*generatorAndFinalityUpgrade5
	-"Generators are 0.2% more efficient for each finality, and finalities are 0.2% more efficient for each generator.<br><i>The secret organisation </i>The Finality<i> managed to alter the machines, with another code: EvTXEpJ. It has some sort of dominating power. Hard to describe, but it boosts production.</i>
	-costs 1e+36 code
	-unlocks at 400 maganiumGenerator, 400 finality
	-multiplies efficiency of maganiumGenerator by 0.2% per finality
	-multiplies efficiency of finality by 0.2% per maganiumGenerator
	-named World-altering Machines
	-picture : http://i.imgur.com/EvTXEpJ.png
	*generatorAndFinalityUpgrade6
	-"Generators are 1% more efficient for each finality, and finalities are 1% more efficient for each generator.<br><i>All it took for those generators to dominate the world once and for all, and rule out all power sources was the code: 3jojv9G.</i>
	-costs 1.0101010101e+24 code
	-unlocks at 500 maganiumGenerator, 500 finality
	-multiplies efficiency of maganiumGenerator by 1% per finality
	-multiplies efficiency of finality by 1% per maganiumGenerator
	-named Joint Generator-Finality Ascension
	-picture : http://i.imgur.com/3jojv9G.png
	*magicPointUpgrade1
	-"Magic point converters are 20% more efficient. <br><i> They can now convert more things.</i>"
	-costs 8765432123456789 code
	-unlocks at 1 magicPointBuilding
	-multiplies efficiency of magicPointBuilding by 120%
	-named Better Converting
	-picture : http://i.imgur.com/jFbU9zq.png
	*magicPointUpgrade2
	-"Magic point converters are twice as efficient. <br><i> They are able to process things a lot faster.</i>"
	-costs 876543212345678987 code
	-unlocks at 40 magicPointBuilding
	-multiplies efficiency of magicPointBuilding by 200%
	-named Faster Converting
	-picture : http://i.imgur.com/uOfWqg7.png
	*magicPointUpgrade3
	-"Magic point converters are 3 times as efficient. <br><i> They now crash less often.</i>"
	-costs 87654321234567898765 code
	-unlocks at 100 magicPointBuilding
	-multiplies efficiency of magicPointBuilding by 300%
	-named Decreased Shutdown rate
	-picture : http://i.imgur.com/7mSNhSG.png
	*magicPointUpgrade4
	-"Magic point converters are 4 times as efficient. <br><i> They convert things really fast.</i>"
	-costs 43212345678987654321234 code
	-unlocks at 150 magicPointBuilding
	-multiplies efficiency of magicPointBuilding by 400%
	-named Supercharged converters
	-picture : http://i.imgur.com/y5osHOo.png
	*magicPointUpgrade5
	-"Magic point converters are 5 times as efficient. <br><i> People can now work as a team to increase the power of all the generators.</i>"
	-costs 4321234567898765432123456 code
	-unlocks at 200 magicPointBuilding
	-multiplies efficiency of magicPointBuilding by 500%
	-named Team Converting
	-picture : http://i.imgur.com/BVl60kW.png
	*magicPointUpgrade6
	-"Magic point converters are 7 times as efficient. <br><i> Bigger = better, obviously.</i>"
	-costs 123456789876543212345678987 code
	-unlocks at 300 magicPointBuilding
	-multiplies efficiency of magicPointBuilding by 700%
	-named Bigger Converters
	-picture : http://i.imgur.com/BqQXthS.png
	*magicPointUpgrade7
	-"Magic point converters are 10 times as efficient. <br><i> There are plenty of fish in the- wait, the fish got converted into magic. There are no fish- wait, the sea got converted also. Approach everything converters with extreme caution.</i>"
	-costs 12345678987654321234567898765 code
	-unlocks at 400 magicPointBuilding
	-multiplies efficiency of magicPointBuilding by 1000%
	-named Everything converters
	-picture : http://i.imgur.com/5zhYjh8.png
	*bonusUpgrade1
	-"Manual coding is 10% more efficient.<br><i></i>
	-costs 1 code
	-unlocks at 1 bonus
	-multiplies efficiency of writeCode by 110%
	-named First Bonus
	-picture : http://i.imgur.com/NlDq93z.png
	*bonusUpgrade2
	-"Game Producers are twice as efficient.<br><i></i>
	-costs 101 code
	-unlocks at 10 bonus
	-multiplies efficiency of gameProducer by 200%
	-named Second Bonus
	-picture : http://i.imgur.com/dzOVCRp.png
	*bonusUpgrade3
	-"Objects are 1% more efficient for each enemy. Positive reviewers are 4% more efficient for each advertisement.<br><i></i>
	-costs 10101 code
	-unlocks at 20 bonus
	-multiplies efficiency of highReviewer by 4% per advertise
	-multiplies efficiency of object by 1% per enemy
	-named Third Bonus
	-picture : http://i.imgur.com/uixH58d.png
	*bonusUpgrade4
	-"Everything is 20% more efficient.<br><i></i>
	-costs 1010101 code
	-unlocks at 40 bonus
	-multiplies efficiency of writeCode by 120%
	-multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of object by 120%
	-multiplies efficiency of enemy by 120%
	-multiplies efficiency of player by 120%
	-multiplies efficiency of level by 120%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of gameProducer by 120%
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of highReviewer by 120%
	-multiplies efficiency of studio by 120%
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of gameSeries by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-multiplies efficiency of finality by 120%
	-named Fourth Bonus
	-picture : http://i.imgur.com/vVRLTdB.png
	*bonusUpgrade5
	-"Manual coding is 30% more efficient.<br><i></i>
	-costs 101010101 code
	-unlocks at 80 bonus
	-multiplies efficiency of writeCode by 130%
	-named Fifth Bonus
	-picture : http://i.imgur.com/7cxT9Bp.png
	*bonusUpgrade6
	-"Game producers are 2% more efficient for each game.<br><i></i>
	-costs 10101010101 code
	-unlocks at 100 bonus
	-multiplies efficiency of gameProducer by 2% per game
	-named Sixth Bonus
	-picture : http://i.imgur.com/dWrcSHn.png
	*bonusUpgrade7
	-"Mystery effect.<br><i>What could it be?</i>
	-costs 1010101010101 code
	-unlocks at 150 bonus
	-multiplies efficiency of gameSeries by 200%
	-named Seventh Bonus
	-picture : http://i.imgur.com/9mEnvT1.png
	*bonusUpgrade8
	-"This does nothing. UMAD?.<br><i></i>
	-costs 101010101010101 code
	-unlocks at 200 bonus
	-unlocks iLied
	-multiplies efficiency of highReviewer by 300%
	-named Eighth Bonus
	-picture : http://i.imgur.com/UWez8YQ.png
	*bonusUpgrade9
	-"Manual coding is 50% more efficient.<br><i></i>
	-costs 10101010101010101 code
	-unlocks at 250 bonus
	-multiplies efficiency of writeCode by 150%
	-named Ninth Bonus
	-picture : http://i.imgur.com/6NOUO26.png
	*bonusUpgrade10
	-"Everything is more efficient the longer you've played.<br><i>You're still here?</i>
	-costs 1010101010101010101 code
	-unlocks at 300 bonus
	-multiplies efficiency of writeCode by 0.000005% per time
	-multiplies efficiency of codeWriter by 0.000005% per time
	-multiplies efficiency of object by 0.000005% per time
	-multiplies efficiency of enemy by 0.000005% per time
	-multiplies efficiency of player by 0.000005% per time
	-multiplies efficiency of level by 0.000004% per time
	-multiplies efficiency of game by 0.000004% per time
	-multiplies efficiency of fanbase by 0.000004% per time
	-multiplies efficiency of forum by 0.000004% per time
	-multiplies efficiency of advertise by 0.000003% per time
	-multiplies efficiency of highReviewer by 0.000003% per time
	-multiplies efficiency of studio by 0.000003% per time
	-multiplies efficiency of magic by 0.000003% per time
	-multiplies efficiency of gameSeries by 0.000003% per time
	-multiplies efficiency of popularYoutuber by 0.000003% per time
	-multiplies efficiency of maganiumGenerator by 0.000003% per time
	-multiplies efficiency of finality by 0.000002% per time
	-multiplies efficiency of magicPointBuilding by 0.000005% per time
	-named Tenth Bonus
	-picture : http://i.imgur.com/hFwXM2C.png
	*bonusUpgrade11
	-"Manual coding is 1.5 times as efficient.<br><i>Wow.</i>
	-costs 101010101010101010101 code
	-unlocks at 350 bonus
	-multiplies efficiency of writeCode by 150%
	-named Eleventh Bonus
	-picture : http://i.imgur.com/ifoLIQq.png
	*bonusUpgrade12
	-"Mystery effect again.<br><i></i>
	-costs 10101010101010101010101010101 code
	-unlocks at 400 bonus
	-multiplies efficiency of popularYoutuber by 200%
	-named Twelfth Bonus
	-picture : http://i.imgur.com/vFKoG3s.png
	*bonusUpgrade13
	-"Manual coding is 1.5 times as efficient.<br><i>Words: none.</i>
	-costs 10101010101010101010101010101010 code
	-unlocks at 450 bonus
	-multiplies efficiency of writeCode by 150%
	-named Thirteenth Bonus
	-picture : http://i.imgur.com/HMIRuv9.png
	*bonusUpgrade14
	-"[REDACTED BY THE FINALITY]<br><i>[REDACTED BY THE FINALITY]</i>
	-costs 10101010101010101010101010101010101 code
	-unlocks at 500 bonus
	-multiplies efficiency of finality by 99%
	-multiplies efficiency of writeCode by 420%
	-multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of object by 120%
	-multiplies efficiency of enemy by 120%
	-multiplies efficiency of player by 120%
	-multiplies efficiency of level by 120%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of gameProducer by 120%
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of highReviewer by 120%
	-multiplies efficiency of studio by 120%
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of gameSeries by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-multiplies efficiency of magicPointBuilding by 120%
	-named Ultimate Bonus
	-picture : http://i.imgur.com/rAi5gin.png
	*researchUpgrade1
	-"Everything is 20% more efficient.<br><i>Our advanced technology allows us to boost efficiency further!</i>
	-costs 616 code
	-unlocks at 100 researchTime
	-multiplies efficiency of writeCode by 120%
	-multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of object by 120%
	-multiplies efficiency of enemy by 120%
	-multiplies efficiency of player by 120%
	-multiplies efficiency of level by 120%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of gameProducer by 120%
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of highReviewer by 120%
	-multiplies efficiency of studio by 120%
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of gameSeries by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-multiplies efficiency of finality by 120%
	-multiplies efficiency of magicPointBuilding by 120%
	-named Technological Advance
	-picture : http://i.imgur.com/GS3JNtZ.png
	*researchUpgrade2
	-"Unlocks fast men related upgrades.<br><i>We can now code faster, like a menner.</i>
	-costs 61616 code
	-gives 1 fastMenResearch
	-unlocks at 500 researchTime
	-named Fast Men Research
	-picture : http://i.imgur.com/JUqLcP2.png
	*researchUpgrade3
	-"Unlocks magic code writers.<br><i>We finally have the technology to enhance code writers with magic.</i>
	-costs 6161616 code
	-unlocks magic
	-unlocks at 1000 researchTime
	-named Magic Research
	-picture : http://i.imgur.com/nhz8HjT.png
	*researchUpgrade4
	-"Studios are twice as efficient.<br><i>We use technology to enhance our game studios.</i>
	-costs 616161616 code
	-multiplies efficiency of studio by 200%
	-unlocks at 4000 researchTime
	-named Studio Technology
	-picture : http://i.imgur.com/hycQxGM.png
	*researchUpgrade5
	-"Manual code writing is 0.1% more efficient for each studio.<br><i>The technology from the studios enable you to write really fast.</i>
	-costs 61616161616 code
	-multiplies efficiency of writeCode by 0.1% per studio
	-unlocks at 10000 researchTime
	-named Studio Technology Boost
	-picture : http://i.imgur.com/L2SdPAH.png
	*researchUpgradeLol
	-"Unlocks the ability to speed up research. <br><i>Now you can help with research as well!</i>
	-costs 6161616161616 code
	-unlocks speedResearch
	-unlocks at 25000 researchTime
	-named Research Speed-Up
	-picture : http://i.imgur.com/GS3JNtZ.png
	*researchUpgrade6
	-"Studios are four times as efficient, but manual code writing is half as efficient.<br><i>The technology of the studios is starting to get out of hand....</i>
	-costs 6161616161616161 code
	-multiplies efficiency of writeCode by 50%
	-multiplies efficiency of studio by 400%
	-unlocks at 50000 researchTime
	-unlocks researchAchieve3
	-unlocks researchUpgrade7
	-named Unstable Studios
	-picture : http://i.imgur.com/3wQWoDT.png
	*researchUpgradeLol2
	-"Manual research  is <b>twice</b> as efficient.<br><i>People help you to research quicker. This is very useful.</i>
	-costs 6161616161616 code
	-multiplies efficiency of speedResearch by 200%
	-multiplies efficiency of speedResearch2 by 200%
	-multiplies efficiency of speedResearch3 by 200%
	-multiplies efficiency of speedResearch4 by 200%
	-unlocks at 75000 researchTime
	-named Enhanced Research
	-picture : http://i.imgur.com/GS3JNtZ.png
	*researchUpgrade7
	-"Studios are five times as efficient, but manual code writing is half as efficient.<br><i>This is a bad idea.</i>
	-costs 61616161616161616 code
	-multiplies efficiency of writeCode by 50%
	-multiplies efficiency of studio by 500%
	-requires 100000 researchTime
	-unlocks researchUpgrade8
	-named Corrupted Studios
	-picture : http://i.imgur.com/FAAmitz.png
	*researchUpgrade8
	-"Studios are ten times as efficient, but manual code writing is half as efficient.<br><i>They are going to explode the entire game and give you a hard reset... nah... just kidding... but this does ruin manual code writing.</i>
	-costs 6161616161616161616 code
	-multiplies efficiency of writeCode by 50%
	-multiplies efficiency of studio by 1000%
	-requires 250000 researchTime
	-unlocks researchAchieve4
	-unlocks researchUpgrade9
	-unlocks researchUpgrade10
	-named Excessively Unstable Studios
	-picture : http://i.imgur.com/v1YqEuF.png
	*researchUpgrade9
	-"Manual code writing is back to normal efficiency, but studios are 25% as efficient.<br><i>We must use our technology to wipe out the corruption and instability... at the cost of the productivity of the studios. This choice is irreversible, unless you hard reset.</i>
	-costs 6161616161616161616 code
	-multiplies efficiency of writeCode by 800%
	-multiplies efficiency of studio by 25%
	-named Stability Restoration (ALMOST IRREVERSIBLE)
	-unlocks researchAchieve5
	-unlocks researchUpgrade11
	-picture : http://i.imgur.com/VCF12TC.png
	*researchUpgrade10
	-"Everything is more efficient the longer you research.<i>As technology gradually gets better, we can make small improvements to our things.</i>
	-costs 6161616161616161616 code
	-multiplies efficiency of writeCode by 0.000005% per researchTime
	-multiplies efficiency of codeWriter by 0.000005% per researchTime
	-multiplies efficiency of object by 0.000005% per researchTime
	-multiplies efficiency of enemy by 0.000005% per researchTime
	-multiplies efficiency of player by 0.000005% per researchTime
	-multiplies efficiency of level by 0.000004% per researchTime
	-multiplies efficiency of game by 0.000004% per researchTime
	-multiplies efficiency of fanbase by 0.000004% per researchTime
	-multiplies efficiency of forum by 0.000004% per researchTime
	-multiplies efficiency of advertise by 0.000003% per researchTime
	-multiplies efficiency of highReviewer by 0.000003% per researchTime
	-multiplies efficiency of studio by 0.000003% per researchTime
	-multiplies efficiency of magic by 0.000003% per researchTime
	-multiplies efficiency of gameSeries by 0.000003% per researchTime
	-multiplies efficiency of popularYoutuber by 0.000003% per researchTime
	-multiplies efficiency of maganiumGenerator by 0.000003% per researchTime
	-multiplies efficiency of finality by 0.000003% per researchTime
	-multiplies efficiency of magicPointBuilding by 0.000005% per researchTime
	-named More Technological Advance
	-picture : http://i.imgur.com/oJsfL3G.png
	*researchUpgrade11
	-"Studios are twice as efficient.<br><i>We found it! At last!</i>
	-costs 61616161616161616161 code
	-requires 500000 researchTime
	-unlocks researchUpgrade12
	-multiplies efficiency of studio by 200%
	-named The Optimal Stage
	-picture : http://i.imgur.com/VCF12TC.png
	*researchUpgrade12
	-"Studios are twice as efficient.<br><i>Thanks to technological advances, we can push our studios to the max without any instability.</i>
	-costs 616161616161616161616 code
	-requires 1000000 researchTime
	-multiplies efficiency of studio by 200%
	-named The REAL Optimal Stage
	-picture : http://i.imgur.com/VCF12TC.png
	*researchUpgrade13
	-"Research labs are <b>2%</b> more efficient per breakthrough. Each research lab has a <b>1 in 15,000</b> chance of giving you a breakthrough every second. Breakthroughs <b>cannot</b> be kept through resets.<br><i>Every so often, we make a breakthrough, boosting our research.</i>
	-unlocks at 1 breakthrough
	-multiplies efficiency of research by 2% per breakthrough
	-multiplies efficiency of research2 by 2% per breakthrough
	-multiplies efficiency of research3 by 2% per breakthrough
	-multiplies efficiency of research4 by 2% per breakthrough
	-multiplies efficiency of speedResearch by 2% per breakthrough
	-multiplies efficiency of speedResearch2 by 2% per breakthrough
	-multiplies efficiency of speedResearch3 by 2% per breakthrough
	-multiplies efficiency of speedResearch4 by 2% per breakthrough
	-named Breakthroughs
	-picture : http://i.imgur.com/GS3JNtZ.png

	*researchAscend1
	-"Research is 10% faster.<br><i></i>
	-requires 10000 researchTime
	-unlocks at 61 prestige
	-multiplies efficiency of research by 110%
	-multiplies efficiency of research2 by 110%
	-multiplies efficiency of research3 by 110%
	-multiplies efficiency of research4 by 110%
	-multiplies efficiency of speedResearch by 110%
	-multiplies efficiency of speedResearch2 by 110%
	-multiplies efficiency of speedResearch3 by 110%
	-multiplies efficiency of speedResearch4 by 110%
	-named First Research Ascend
	-picture : http://i.imgur.com/5vOQOpP.png
	*researchAscend2
	-"Research is 25% faster.<br><i></i>
	-requires 50000 researchTime
	-unlocks at 616 prestige
	-multiplies efficiency of research by 125%
	-multiplies efficiency of research2 by 125%
	-multiplies efficiency of research3 by 125%
	-multiplies efficiency of research4 by 125%
	-multiplies efficiency of speedResearch by 125%
	-multiplies efficiency of speedResearch2 by 125%
	-multiplies efficiency of speedResearch3 by 125%
	-multiplies efficiency of speedResearch4 by 125%
	-named Second Research Ascend
	-picture : http://i.imgur.com/5vOQOpP.png
	*researchAscend3
	-"Research is 50% faster.<br><i></i>
	-requires 100000 researchTime
	-unlocks at 6161 prestige
	-multiplies efficiency of research by 150%
	-multiplies efficiency of research2 by 150%
	-multiplies efficiency of research3 by 150%
	-multiplies efficiency of research4 by 150%
	-multiplies efficiency of speedResearch by 150%
	-multiplies efficiency of speedResearch2 by 150%
	-multiplies efficiency of speedResearch3 by 150%
	-multiplies efficiency of speedResearch4 by 150%
	-named Third Research Ascend
	-picture : http://i.imgur.com/5vOQOpP.png
	*researchAscend4
	-"Research is twice as fast.<br><i></i>
	-requires 500000 researchTime
	-unlocks at 61616 prestige
	-multiplies efficiency of research by 200%
	-multiplies efficiency of research2 by 200%
	-multiplies efficiency of research3 by 200%
	-multiplies efficiency of research4 by 200%
	-multiplies efficiency of speedResearch by 200%
	-multiplies efficiency of speedResearch2 by 200%
	-multiplies efficiency of speedResearch3 by 200%
	-multiplies efficiency of speedResearch4 by 200%
	-named Fourth Research Ascend
	-picture : http://i.imgur.com/5vOQOpP.png
	*researchAscend5
	-"Research is three times as fast.<br><i></i>
	-requires 1000000 researchTime
	-unlocks at 616161 prestige
	-multiplies efficiency of research by 300%
	-multiplies efficiency of research2 by 300%
	-multiplies efficiency of research3 by 300%
	-multiplies efficiency of research4 by 300%
	-multiplies efficiency of speedResearch by 300%
	-multiplies efficiency of speedResearch2 by 300%
	-multiplies efficiency of speedResearch3 by 300%
	-multiplies efficiency of speedResearch4 by 300%
	-named Final Research Ascend
	-picture : http://i.imgur.com/5vOQOpP.png

	*alternateUniverseReset2
	-"Everything is 1% more efficient. <br><i>Using godly lines of code, it's possible to ascend. These ascends are pretty boring to start with.</i>
	-costs 1000 code
	-named First Ascend
	-unlocks at 1 prestige
	-gives 1 lel
	-multiplies efficiency of writeCode by 101%
	-multiplies efficiency of codeWriter by 101%
	-multiplies efficiency of object by 101%
	-multiplies efficiency of enemy by 101%
	-multiplies efficiency of player by 101%
	-multiplies efficiency of level by 101%
	-multiplies efficiency of game by 101%
	-multiplies efficiency of fanbase by 101%
	-multiplies efficiency of forum by 101%
	-multiplies efficiency of advertise by 101%
	-multiplies efficiency of studio by 101%
	-multiplies efficiency of magic by 101%
	-multiplies efficiency of gameSeries by 101%
	-multiplies efficiency of popularYoutuber by 101%
	-multiplies efficiency of gameProducer by 101%
	-multiplies efficiency of highReviewer by 101%
	-multiplies efficiency of maganiumGenerator by 101%
	-multiplies efficiency of finality by 101%
	-multiplies efficiency of magicPointBuilding by 101%
	-picture : http://i.imgur.com/m4x9kKH.png
	*alternateUniverseReset3
	-"Everything is 2% more efficient. <br><i></i>
	-costs 10000 code
	-named Second Ascend
	-unlocks at 2 prestige
	-multiplies efficiency of writeCode by 102%
	-multiplies efficiency of codeWriter by 102%
	-multiplies efficiency of object by 102%
	-multiplies efficiency of enemy by 102%
	-multiplies efficiency of player by 102%
	-multiplies efficiency of level by 102%
	-multiplies efficiency of game by 102%
	-multiplies efficiency of fanbase by 102%
	-multiplies efficiency of forum by 102%
	-multiplies efficiency of advertise by 102%
	-multiplies efficiency of studio by 102%
	-multiplies efficiency of magic by 102%
	-multiplies efficiency of gameSeries by 102%
	-multiplies efficiency of popularYoutuber by 102%
	-multiplies efficiency of gameProducer by 102%
	-multiplies efficiency of highReviewer by 102%
	-multiplies efficiency of maganiumGenerator by 102%
	-multiplies efficiency of finality by 102%
	-multiplies efficiency of magicPointBuilding by 102%
	-picture : http://i.imgur.com/WRfvElg.png
	*alternateUniverseReset4
	-"Everything is 4% more efficient. <br><i></i>
	-costs 100000 code
	-named Third Ascend
	-unlocks at 5 prestige
	-multiplies efficiency of writeCode by 104%
	-multiplies efficiency of codeWriter by 104%
	-multiplies efficiency of object by 104%
	-multiplies efficiency of enemy by 104%
	-multiplies efficiency of player by 104%
	-multiplies efficiency of level by 104%
	-multiplies efficiency of game by 104%
	-multiplies efficiency of fanbase by 104%
	-multiplies efficiency of forum by 104%
	-multiplies efficiency of advertise by 104%
	-multiplies efficiency of studio by 104%
	-multiplies efficiency of magic by 104%
	-multiplies efficiency of gameSeries by 104%
	-multiplies efficiency of popularYoutuber by 104%
	-multiplies efficiency of gameProducer by 104%
	-multiplies efficiency of highReviewer by 104%
	-multiplies efficiency of maganiumGenerator by 104%
	-multiplies efficiency of finality by 104%
	-multiplies efficiency of magicPointBuilding by 104%
	-picture : http://i.imgur.com/BbQLf4C.png
	*alternateUniverseReset5
	-"Everything is 10% more efficient. <br><i></i>
	-costs 1000000 code
	-named Fourth Ascend
	-unlocks at 8 prestige
	-gives 1 lel2
	-multiplies efficiency of writeCode by 110%
	-multiplies efficiency of codeWriter by 110%
	-multiplies efficiency of object by 110%
	-multiplies efficiency of enemy by 110%
	-multiplies efficiency of player by 110%
	-multiplies efficiency of level by 110%
	-multiplies efficiency of game by 110%
	-multiplies efficiency of fanbase by 110%
	-multiplies efficiency of forum by 110%
	-multiplies efficiency of advertise by 110%
	-multiplies efficiency of studio by 110%
	-multiplies efficiency of magic by 110%
	-multiplies efficiency of gameSeries by 110%
	-multiplies efficiency of popularYoutuber by 110%
	-multiplies efficiency of gameProducer by 110%
	-multiplies efficiency of highReviewer by 110%
	-multiplies efficiency of maganiumGenerator by 110%
	-multiplies efficiency of finality by 110%
	-multiplies efficiency of magicPointBuilding by 110%
	-picture : http://i.imgur.com/a60alv1.png
	*alternateUniverseReset6
	-"Everything is 10% more efficient. <br><i></i>
	-costs 10000000 code
	-named Fifth Ascend
	-unlocks at 12 prestige
	-multiplies efficiency of writeCode by 110%
	-multiplies efficiency of codeWriter by 110%
	-multiplies efficiency of object by 110%
	-multiplies efficiency of enemy by 110%
	-multiplies efficiency of player by 110%
	-multiplies efficiency of level by 110%
	-multiplies efficiency of game by 110%
	-multiplies efficiency of fanbase by 110%
	-multiplies efficiency of forum by 110%
	-multiplies efficiency of advertise by 110%
	-multiplies efficiency of studio by 110%
	-multiplies efficiency of magic by 110%
	-multiplies efficiency of gameSeries by 110%
	-multiplies efficiency of popularYoutuber by 110%
	-multiplies efficiency of gameProducer by 110%
	-multiplies efficiency of highReviewer by 110%
	-multiplies efficiency of maganiumGenerator by 110%
	-multiplies efficiency of finality by 110%
	-multiplies efficiency of magicPointBuilding by 110%
	-picture : http://i.imgur.com/6maaDax.png
	*alternateUniverseReset7
	-"Everything is 10% more efficient. <br><i></i>
	-costs 100000000 code
	-named Sixth Ascend
	-unlocks at 18 prestige
	-multiplies efficiency of writeCode by 110%
	-multiplies efficiency of codeWriter by 110%
	-multiplies efficiency of object by 110%
	-multiplies efficiency of enemy by 110%
	-multiplies efficiency of player by 110%
	-multiplies efficiency of level by 110%
	-multiplies efficiency of game by 110%
	-multiplies efficiency of fanbase by 110%
	-multiplies efficiency of forum by 110%
	-multiplies efficiency of advertise by 110%
	-multiplies efficiency of studio by 110%
	-multiplies efficiency of magic by 110%
	-multiplies efficiency of gameSeries by 110%
	-multiplies efficiency of popularYoutuber by 110%
	-multiplies efficiency of gameProducer by 110%
	-multiplies efficiency of highReviewer by 110%
	-multiplies efficiency of maganiumGenerator by 110%
	-multiplies efficiency of finality by 110%
	-multiplies efficiency of magicPointBuilding by 110%
	-picture : http://i.imgur.com/le5ERF7.png
	*alternateUniverseReset8
	-"Everything is 15% more efficient. <br><i></i>
	-costs 1000000000 code
	-named Seventh Ascend
	-unlocks at 25 prestige
	-gives 1 lel3
	-multiplies efficiency of writeCode by 115%
	-multiplies efficiency of codeWriter by 115%
	-multiplies efficiency of object by 115%
	-multiplies efficiency of enemy by 115%
	-multiplies efficiency of player by 115%
	-multiplies efficiency of level by 115%
	-multiplies efficiency of game by 115%
	-multiplies efficiency of fanbase by 115%
	-multiplies efficiency of forum by 115%
	-multiplies efficiency of advertise by 115%
	-multiplies efficiency of studio by 115%
	-multiplies efficiency of magic by 115%
	-multiplies efficiency of gameSeries by 115%
	-multiplies efficiency of popularYoutuber by 115%
	-multiplies efficiency of gameProducer by 115%
	-multiplies efficiency of highReviewer by 115%
	-multiplies efficiency of maganiumGenerator by 115%
	-multiplies efficiency of finality by 115%
	-multiplies efficiency of magicPointBuilding by 115%
	-picture : http://i.imgur.com/3r3GIJo.png
	*alternateUniverseReset9
	-"Everything is 15% more efficient. <br><i></i>
	-costs 10000000000 code
	-costs 1 game2
	-named First Red Ascend
	-unlocks at 35 prestige
	-multiplies efficiency of writeCode by 115%
	-multiplies efficiency of codeWriter by 115%
	-multiplies efficiency of object by 115%
	-multiplies efficiency of enemy by 115%
	-multiplies efficiency of player by 115%
	-multiplies efficiency of level by 115%
	-multiplies efficiency of game by 115%
	-multiplies efficiency of fanbase by 115%
	-multiplies efficiency of forum by 115%
	-multiplies efficiency of advertise by 115%
	-multiplies efficiency of studio by 115%
	-multiplies efficiency of magic by 115%
	-multiplies efficiency of gameSeries by 115%
	-multiplies efficiency of popularYoutuber by 115%
	-multiplies efficiency of gameProducer by 115%
	-multiplies efficiency of highReviewer by 115%
	-multiplies efficiency of maganiumGenerator by 115%
	-multiplies efficiency of finality by 115%
	-multiplies efficiency of magicPointBuilding by 115%
	-picture : http://i.imgur.com/vT325fp.png
	*alternateUniverseReset10
	-"Everything is 15% more efficient. <br><i></i>
	-costs 100000000000 code
	-costs 10 game2
	-named Second Red Ascend
	-unlocks at 50 prestige
	-multiplies efficiency of writeCode by 115%
	-multiplies efficiency of codeWriter by 115%
	-multiplies efficiency of object by 115%
	-multiplies efficiency of enemy by 115%
	-multiplies efficiency of player by 115%
	-multiplies efficiency of level by 115%
	-multiplies efficiency of game by 115%
	-multiplies efficiency of fanbase by 115%
	-multiplies efficiency of forum by 115%
	-multiplies efficiency of advertise by 115%
	-multiplies efficiency of studio by 115%
	-multiplies efficiency of magic by 115%
	-multiplies efficiency of gameSeries by 115%
	-multiplies efficiency of popularYoutuber by 115%
	-multiplies efficiency of gameProducer by 115%
	-multiplies efficiency of highReviewer by 115%
	-multiplies efficiency of maganiumGenerator by 115%
	-multiplies efficiency of finality by 115%
	-multiplies efficiency of magicPointBuilding by 115%
	-picture : http://i.imgur.com/pNHpBvV.png
	*alternateUniverseReset11
	-"Everything is 15% more efficient. <br><i></i>
	-costs 1000000000000 code
	-costs 100 game2
	-named Third Red Ascend
	-unlocks at 75 prestige
	-multiplies efficiency of writeCode by 115%
	-multiplies efficiency of codeWriter by 115%
	-multiplies efficiency of object by 115%
	-multiplies efficiency of enemy by 115%
	-multiplies efficiency of player by 115%
	-multiplies efficiency of level by 115%
	-multiplies efficiency of game by 115%
	-multiplies efficiency of fanbase by 115%
	-multiplies efficiency of forum by 115%
	-multiplies efficiency of advertise by 115%
	-multiplies efficiency of studio by 115%
	-multiplies efficiency of magic by 115%
	-multiplies efficiency of gameSeries by 115%
	-multiplies efficiency of popularYoutuber by 115%
	-multiplies efficiency of gameProducer by 115%
	-multiplies efficiency of highReviewer by 115%
	-multiplies efficiency of maganiumGenerator by 115%
	-multiplies efficiency of finality by 115%
	-multiplies efficiency of magicPointBuilding by 115%
	-picture : http://i.imgur.com/1NB75uw.png
	*alternateUniverseReset12
	-"Everything is 15% more efficient. <br><i></i>
	-costs 10000000000000 code
	-costs 1000 game2
	-named Fourth Red Ascend
	-unlocks at 100 prestige
	-gives 1 lel4
	-multiplies efficiency of writeCode by 115%
	-multiplies efficiency of codeWriter by 115%
	-multiplies efficiency of object by 115%
	-multiplies efficiency of enemy by 115%
	-multiplies efficiency of player by 115%
	-multiplies efficiency of level by 115%
	-multiplies efficiency of game by 115%
	-multiplies efficiency of fanbase by 115%
	-multiplies efficiency of forum by 115%
	-multiplies efficiency of advertise by 115%
	-multiplies efficiency of studio by 115%
	-multiplies efficiency of magic by 115%
	-multiplies efficiency of gameSeries by 115%
	-multiplies efficiency of popularYoutuber by 115%
	-multiplies efficiency of gameProducer by 115%
	-multiplies efficiency of highReviewer by 115%
	-multiplies efficiency of maganiumGenerator by 115%
	-multiplies efficiency of finality by 115%
	-multiplies efficiency of magicPointBuilding by 115%
	-picture : http://i.imgur.com/YLYb6NC.png
	*alternateUniverseReset13
	-"Everything is 20% more efficient. <br><i></i>
	-costs 100000000000000 code
	-costs 10000 game2
	-costs 1 positiveReview
	-named First Blue Ascend
	-unlocks at 150 prestige
	-multiplies efficiency of writeCode by 120%
	-multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of object by 120%
	-multiplies efficiency of enemy by 120%
	-multiplies efficiency of player by 120%
	-multiplies efficiency of level by 120%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of studio by 120%
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of gameSeries by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-multiplies efficiency of gameProducer by 120%
	-multiplies efficiency of highReviewer by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-multiplies efficiency of finality by 120%
	-multiplies efficiency of magicPointBuilding by 120%
	-picture : http://i.imgur.com/iu7gFGu.png
	*alternateUniverseReset14
	-"Everything is 20% more efficient. <br><i></i>
	-costs 500000000000000 code
	-costs 50000 game2
	-costs 5 positiveReview
	-named Second Blue Ascend
	-unlocks at 200 prestige
	-multiplies efficiency of writeCode by 120%
	-multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of object by 120%
	-multiplies efficiency of enemy by 120%
	-multiplies efficiency of player by 120%
	-multiplies efficiency of level by 120%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of studio by 120%
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of gameSeries by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-multiplies efficiency of gameProducer by 120%
	-multiplies efficiency of highReviewer by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-multiplies efficiency of finality by 120%
	-multiplies efficiency of magicPointBuilding by 120%
	-picture : http://i.imgur.com/pMXsNKg.png
	*alternateUniverseReset15
	-"Everything is 20% more efficient. <br><i></i>
	-costs 1000000000000000 code
	-costs 100000 game2
	-costs 10 positiveReview
	-named First Green Ascend
	-unlocks at 300 prestige
	-multiplies efficiency of writeCode by 120%
	-multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of object by 120%
	-multiplies efficiency of enemy by 120%
	-multiplies efficiency of player by 120%
	-multiplies efficiency of level by 120%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of studio by 120%
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of gameSeries by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-multiplies efficiency of gameProducer by 120%
	-multiplies efficiency of highReviewer by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-multiplies efficiency of finality by 120%
	-multiplies efficiency of magicPointBuilding by 120%
	-picture : http://i.imgur.com/X0ShkeK.png
	*alternateUniverseReset16
	-"Everything is 20% more efficient. <br><i></i>
	-costs 5000000000000000 code
	-costs 500000 game2
	-costs 50 positiveReview
	-named Second Green Ascend
	-unlocks at 400 prestige
	-multiplies efficiency of writeCode by 120%
	-multiplies efficiency of codeWriter by 120%
	-multiplies efficiency of object by 120%
	-multiplies efficiency of enemy by 120%
	-multiplies efficiency of player by 120%
	-multiplies efficiency of level by 120%
	-multiplies efficiency of game by 120%
	-multiplies efficiency of fanbase by 120%
	-multiplies efficiency of forum by 120%
	-multiplies efficiency of advertise by 120%
	-multiplies efficiency of studio by 120%
	-multiplies efficiency of magic by 120%
	-multiplies efficiency of gameSeries by 120%
	-multiplies efficiency of popularYoutuber by 120%
	-multiplies efficiency of gameProducer by 120%
	-multiplies efficiency of highReviewer by 120%
	-multiplies efficiency of maganiumGenerator by 120%
	-multiplies efficiency of finality by 120%
	-multiplies efficiency of magicPointBuilding by 120%
	-picture : http://i.imgur.com/CmXKgGY.png
	*alternateUniverseReset17
	-"Everything is 25% more efficient. <br><i></i>
	-costs 50000000000000000 code
	-costs 5000000 game2
	-costs 500 positiveReview
	-named First Bronze Ascend
	-unlocks at 500 prestige
	-gives 1 lel5
	-multiplies efficiency of writeCode by 125%
	-multiplies efficiency of codeWriter by 125%
	-multiplies efficiency of object by 125%
	-multiplies efficiency of enemy by 125%
	-multiplies efficiency of player by 125%
	-multiplies efficiency of level by 125%
	-multiplies efficiency of game by 125%
	-multiplies efficiency of fanbase by 125%
	-multiplies efficiency of forum by 125%
	-multiplies efficiency of advertise by 125%
	-multiplies efficiency of studio by 125%
	-multiplies efficiency of magic by 125%
	-multiplies efficiency of gameSeries by 125%
	-multiplies efficiency of popularYoutuber by 125%
	-multiplies efficiency of gameProducer by 125%
	-multiplies efficiency of highReviewer by 125%
	-multiplies efficiency of maganiumGenerator by 125%
	-multiplies efficiency of finality by 125%
	-multiplies efficiency of magicPointBuilding by 125%
	-picture : http://i.imgur.com/4MwNcq7.png
	*alternateUniverseReset18
	-"Everything is 25% more efficient. <br><i></i>
	-costs 100000000000000000 code
	-costs 10000000 game2
	-costs 1000 positiveReview
	-named Second Bronze Ascend
	-unlocks at 750 prestige
	-multiplies efficiency of writeCode by 125%
	-multiplies efficiency of codeWriter by 125%
	-multiplies efficiency of object by 125%
	-multiplies efficiency of enemy by 125%
	-multiplies efficiency of player by 125%
	-multiplies efficiency of level by 125%
	-multiplies efficiency of game by 125%
	-multiplies efficiency of fanbase by 125%
	-multiplies efficiency of forum by 125%
	-multiplies efficiency of advertise by 125%
	-multiplies efficiency of studio by 125%
	-multiplies efficiency of magic by 125%
	-multiplies efficiency of gameSeries by 125%
	-multiplies efficiency of popularYoutuber by 125%
	-multiplies efficiency of gameProducer by 125%
	-multiplies efficiency of highReviewer by 125%
	-multiplies efficiency of maganiumGenerator by 125%
	-multiplies efficiency of finality by 125%
	-multiplies efficiency of magicPointBuilding by 125%
	-picture : http://i.imgur.com/677ihdC.png
	*alternateUniverseReset19
	-"Everything is 25% more efficient. <br><i></i>
	-costs 500000000000000000 code
	-costs 50000000 game2
	-costs 5000 positiveReview
	-named First Silver Ascend
	-unlocks at 1000 prestige
	-multiplies efficiency of writeCode by 125%
	-multiplies efficiency of codeWriter by 125%
	-multiplies efficiency of object by 125%
	-multiplies efficiency of enemy by 125%
	-multiplies efficiency of player by 125%
	-multiplies efficiency of level by 125%
	-multiplies efficiency of game by 125%
	-multiplies efficiency of fanbase by 125%
	-multiplies efficiency of forum by 125%
	-multiplies efficiency of advertise by 125%
	-multiplies efficiency of studio by 125%
	-multiplies efficiency of magic by 125%
	-multiplies efficiency of gameSeries by 125%
	-multiplies efficiency of popularYoutuber by 125%
	-multiplies efficiency of gameProducer by 125%
	-multiplies efficiency of highReviewer by 125%
	-multiplies efficiency of maganiumGenerator by 125%
	-multiplies efficiency of finality by 125%
	-multiplies efficiency of magicPointBuilding by 125%
	-picture : http://i.imgur.com/imrBNOZ.png
	*alternateUniverseReset20
	-"Everything is 25% more efficient. <br><i></i>
	-costs 10000000000000000000 code
	-costs 1000000000 game2
	-costs 100000 positiveReview
	-named Second Silver Ascend
	-unlocks at 2000 prestige
	-multiplies efficiency of writeCode by 125%
	-multiplies efficiency of codeWriter by 125%
	-multiplies efficiency of object by 125%
	-multiplies efficiency of enemy by 125%
	-multiplies efficiency of player by 125%
	-multiplies efficiency of level by 125%
	-multiplies efficiency of game by 125%
	-multiplies efficiency of fanbase by 125%
	-multiplies efficiency of forum by 125%
	-multiplies efficiency of advertise by 125%
	-multiplies efficiency of studio by 125%
	-multiplies efficiency of magic by 125%
	-multiplies efficiency of gameSeries by 125%
	-multiplies efficiency of popularYoutuber by 125%
	-multiplies efficiency of gameProducer by 125%
	-multiplies efficiency of highReviewer by 125%
	-multiplies efficiency of maganiumGenerator by 125%
	-multiplies efficiency of finality by 125%
	-multiplies efficiency of magicPointBuilding by 125%
	-picture : http://i.imgur.com/jRGPhX4.png
	*alternateUniverseReset21
	-"Everything is 30% more efficient. <br><i></i>
	-costs 50000000000000000000 code
	-costs 5000000000 game2
	-costs 500000 positiveReview
	-named Golden Ascend
	-unlocks at 4000 prestige
	-multiplies efficiency of writeCode by 130%
	-multiplies efficiency of codeWriter by 130%
	-multiplies efficiency of object by 130%
	-multiplies efficiency of enemy by 130%
	-multiplies efficiency of player by 130%
	-multiplies efficiency of level by 130%
	-multiplies efficiency of game by 130%
	-multiplies efficiency of fanbase by 130%
	-multiplies efficiency of forum by 130%
	-multiplies efficiency of advertise by 130%
	-multiplies efficiency of studio by 130%
	-multiplies efficiency of magic by 130%
	-multiplies efficiency of gameSeries by 130%
	-multiplies efficiency of popularYoutuber by 130%
	-multiplies efficiency of gameProducer by 130%
	-multiplies efficiency of highReviewer by 130%
	-multiplies efficiency of maganiumGenerator by 130%
	-multiplies efficiency of finality by 130%
	-multiplies efficiency of magicPointBuilding by 130%
	-picture : http://i.imgur.com/aOnBOmK.png
	*alternateUniverseReset22
	-"Everything is 30% more efficient. <br><i></i>
	-costs 100000000000000000000 code
	-costs 10000000000 game2
	-costs 1000000 positiveReview
	-named Diamond Ascend
	-unlocks at 8000 prestige
	-gives 1 lel6
	-multiplies efficiency of writeCode by 130%
	-multiplies efficiency of codeWriter by 130%
	-multiplies efficiency of object by 130%
	-multiplies efficiency of enemy by 130%
	-multiplies efficiency of player by 130%
	-multiplies efficiency of level by 130%
	-multiplies efficiency of game by 130%
	-multiplies efficiency of fanbase by 130%
	-multiplies efficiency of forum by 130%
	-multiplies efficiency of advertise by 130%
	-multiplies efficiency of studio by 130%
	-multiplies efficiency of magic by 130%
	-multiplies efficiency of gameSeries by 130%
	-multiplies efficiency of popularYoutuber by 130%
	-multiplies efficiency of gameProducer by 130%
	-multiplies efficiency of highReviewer by 130%
	-multiplies efficiency of maganiumGenerator by 130%
	-multiplies efficiency of finality by 130%
	-multiplies efficiency of magicPointBuilding by 130%
	-picture : http://i.imgur.com/DULftRF.png
	*alternateUniverseReset23
	-"Everything is 30% more efficient. <br><i></i>
	-costs 500000000000000000000 code
	-costs 50000000000 game2
	-costs 5000000 positiveReview
	-named Rusting Ascend
	-unlocks at 16000 prestige
	-multiplies efficiency of writeCode by 130%
	-multiplies efficiency of codeWriter by 130%
	-multiplies efficiency of object by 130%
	-multiplies efficiency of enemy by 130%
	-multiplies efficiency of player by 130%
	-multiplies efficiency of level by 130%
	-multiplies efficiency of game by 130%
	-multiplies efficiency of fanbase by 130%
	-multiplies efficiency of forum by 130%
	-multiplies efficiency of advertise by 130%
	-multiplies efficiency of studio by 130%
	-multiplies efficiency of magic by 130%
	-multiplies efficiency of gameSeries by 130%
	-multiplies efficiency of popularYoutuber by 130%
	-multiplies efficiency of gameProducer by 130%
	-multiplies efficiency of highReviewer by 130%
	-multiplies efficiency of maganiumGenerator by 130%
	-multiplies efficiency of finality by 130%
	-multiplies efficiency of magicPointBuilding by 130%
	-picture : http://i.imgur.com/d4uu5ju.png
	*alternateUniverseReset24
	-"Everything is 35% more efficient. <br><i></i>
	-costs 1000000000000000000000 code
	-costs 100000000000 game2
	-costs 10000000 positiveReview
	-named Magic Ascend
	-unlocks at 32000 prestige
	-multiplies efficiency of writeCode by 135%
	-multiplies efficiency of codeWriter by 135%
	-multiplies efficiency of object by 135%
	-multiplies efficiency of enemy by 135%
	-multiplies efficiency of player by 135%
	-multiplies efficiency of level by 135%
	-multiplies efficiency of game by 135%
	-multiplies efficiency of fanbase by 135%
	-multiplies efficiency of forum by 135%
	-multiplies efficiency of advertise by 135%
	-multiplies efficiency of studio by 135%
	-multiplies efficiency of magic by 135%
	-multiplies efficiency of gameSeries by 135%
	-multiplies efficiency of popularYoutuber by 135%
	-multiplies efficiency of gameProducer by 135%
	-multiplies efficiency of highReviewer by 135%
	-multiplies efficiency of maganiumGenerator by 135%
	-multiplies efficiency of finality by 135%
	-multiplies efficiency of magicPointBuilding by 135%
	-picture : http://i.imgur.com/7GvZIi9.png
	*alternateUniverseReset25
	-"Everything is 40% more efficient. <br><i>"There should be a My Little Pony reference for this ascend." ~Developer Mlepfim</i>
	-costs 10000000000000000000000 code
	-costs 1000000000000 game2
	-costs 100000000 positiveReview
	-named Rainbow Ascend
	-unlocks at 128000 prestige
	-multiplies efficiency of writeCode by 140%
	-multiplies efficiency of codeWriter by 140%
	-multiplies efficiency of object by 140%
	-multiplies efficiency of enemy by 140%
	-multiplies efficiency of player by 140%
	-multiplies efficiency of level by 140%
	-multiplies efficiency of game by 140%
	-multiplies efficiency of fanbase by 140%
	-multiplies efficiency of forum by 140%
	-multiplies efficiency of advertise by 140%
	-multiplies efficiency of studio by 140%
	-multiplies efficiency of magic by 140%
	-multiplies efficiency of gameSeries by 140%
	-multiplies efficiency of popularYoutuber by 140%
	-multiplies efficiency of gameProducer by 140%
	-multiplies efficiency of highReviewer by 140%
	-multiplies efficiency of maganiumGenerator by 140%
	-multiplies efficiency of finality by 140%
	-multiplies efficiency of magicPointBuilding by 140%
	-picture : http://i.imgur.com/sbbljO0.png
	*alternateUniverseReset26
	-"Everything is 45% more efficient.  <br><i></i>
	-costs 100000000000000000000000 code
	-costs 10000000000000 game2
	-costs 1000000000 positiveReview
	-named RGB Ascend
	-unlocks at 1280000 prestige
	-multiplies efficiency of writeCode by 145%
	-multiplies efficiency of codeWriter by 145%
	-multiplies efficiency of object by 145%
	-multiplies efficiency of enemy by 145%
	-multiplies efficiency of player by 145%
	-multiplies efficiency of level by 145%
	-multiplies efficiency of game by 145%
	-multiplies efficiency of fanbase by 145%
	-multiplies efficiency of forum by 145%
	-multiplies efficiency of advertise by 145%
	-multiplies efficiency of studio by 145%
	-multiplies efficiency of magic by 145%
	-multiplies efficiency of gameSeries by 145%
	-multiplies efficiency of popularYoutuber by 145%
	-multiplies efficiency of gameProducer by 145%
	-multiplies efficiency of highReviewer by 145%
	-multiplies efficiency of maganiumGenerator by 145%
	-multiplies efficiency of finality by 145%
	-multiplies efficiency of magicPointBuilding by 145%
	-picture : http://i.imgur.com/nHbld8h.png
	*alternateUniverseReset27
	-"Everything is 50% more efficient.<br><i></i>
	-costs 500000000000000000000000 code
	-costs 50000000000000 game2
	-costs 5000000000 positiveReview
	-named Dark Ascend
	-unlocks at 2560000 prestige
	-multiplies efficiency of writeCode by 150%
	-multiplies efficiency of codeWriter by 150%
	-multiplies efficiency of object by 150%
	-multiplies efficiency of enemy by 150%
	-multiplies efficiency of player by 150%
	-multiplies efficiency of level by 150%
	-multiplies efficiency of game by 150%
	-multiplies efficiency of fanbase by 150%
	-multiplies efficiency of forum by 150%
	-multiplies efficiency of advertise by 150%
	-multiplies efficiency of studio by 150%
	-multiplies efficiency of magic by 150%
	-multiplies efficiency of gameSeries by 150%
	-multiplies efficiency of popularYoutuber by 150%
	-multiplies efficiency of gameProducer by 150%
	-multiplies efficiency of highReviewer by 150%
	-multiplies efficiency of maganiumGenerator by 150%
	-multiplies efficiency of finality by 150%
	-multiplies efficiency of magicPointBuilding by 150%
	-picture : http://i.imgur.com/AatSjPl.png
	*alternateUniverseReset28
	-"Everything is 55% more efficient. <br><i>Well, we did it. we finally reached the highest possible ascension tier. Congratulations.</i>
	-costs 1000000000000000000000000 code
	-costs 100000000000000 game2
	-costs 10000000000 positiveReview
	-named First Ultimate Ascend
	-unlocks at 10000000 prestige
	-gives 1 lel7
	-multiplies efficiency of writeCode by 155%
	-multiplies efficiency of codeWriter by 155%
	-multiplies efficiency of object by 155%
	-multiplies efficiency of enemy by 155%
	-multiplies efficiency of player by 155%
	-multiplies efficiency of level by 155%
	-multiplies efficiency of game by 155%
	-multiplies efficiency of fanbase by 155%
	-multiplies efficiency of forum by 155%
	-multiplies efficiency of advertise by 155%
	-multiplies efficiency of studio by 155%
	-multiplies efficiency of magic by 155%
	-multiplies efficiency of gameSeries by 155%
	-multiplies efficiency of popularYoutuber by 155%
	-multiplies efficiency of gameProducer by 155%
	-multiplies efficiency of highReviewer by 155%
	-multiplies efficiency of maganiumGenerator by 155%
	-multiplies efficiency of finality by 155%
	-multiplies efficiency of magicPointBuilding by 155%
	-picture : http://i.imgur.com/lioGdC4.png

	*alternateUniverseReset29
	-"Everything is 60% more efficient. <br><i>But it's still possible to make that ascension tier better.</i>
	-costs 10000000000000000000000000 code
	-costs 1000000000000000 game2
	-costs 100000000000 positiveReview
	-named Second Ultimate Ascend
	-unlocks at 100000000 prestige
	-multiplies efficiency of writeCode by 160%
	-multiplies efficiency of codeWriter by 160%
	-multiplies efficiency of object by 160%
	-multiplies efficiency of enemy by 160%
	-multiplies efficiency of player by 160%
	-multiplies efficiency of level by 160%
	-multiplies efficiency of game by 160%
	-multiplies efficiency of fanbase by 160%
	-multiplies efficiency of forum by 160%
	-multiplies efficiency of advertise by 160%
	-multiplies efficiency of studio by 160%
	-multiplies efficiency of magic by 160%
	-multiplies efficiency of gameSeries by 160%
	-multiplies efficiency of popularYoutuber by 160%
	-multiplies efficiency of gameProducer by 160%
	-multiplies efficiency of highReviewer by 160%
	-multiplies efficiency of maganiumGenerator by 160%
	-multiplies efficiency of finality by 160%
	-multiplies efficiency of magicPointBuilding by 160%
	-picture : http://i.imgur.com/lioGdC4.png

	*alternateUniverseReset30
	-"Everything is 70% more efficient. <br><i></i>
	-costs 100000000000000000000000000 code
	-costs 10000000000000000 game2
	-costs 1000000000000 positiveReview
	-named Third Ultimate Ascend
	-unlocks at 1000000000 prestige
	-multiplies efficiency of writeCode by 170%
	-multiplies efficiency of codeWriter by 170%
	-multiplies efficiency of object by 170%
	-multiplies efficiency of enemy by 170%
	-multiplies efficiency of player by 170%
	-multiplies efficiency of level by 170%
	-multiplies efficiency of game by 170%
	-multiplies efficiency of fanbase by 170%
	-multiplies efficiency of forum by 170%
	-multiplies efficiency of advertise by 170%
	-multiplies efficiency of studio by 170%
	-multiplies efficiency of magic by 170%
	-multiplies efficiency of gameSeries by 170%
	-multiplies efficiency of popularYoutuber by 170%
	-multiplies efficiency of gameProducer by 170%
	-multiplies efficiency of highReviewer by 170%
	-multiplies efficiency of maganiumGenerator by 170%
	-multiplies efficiency of finality by 170%
	-multiplies efficiency of magicPointBuilding by 170%
	-picture : http://i.imgur.com/lioGdC4.png

	*alternateUniverseReset31
	-"Everything is 80% more efficient. <br><i>Are you still doing this?</i>
	-costs 1000000000000000000000000000 code
	-costs 100000000000000000 game2
	-costs 10000000000000 positiveReview
	-named Fourth Ultimate Ascend
	-unlocks at 10000000000 prestige
	-multiplies efficiency of writeCode by 180%
	-multiplies efficiency of codeWriter by 180%
	-multiplies efficiency of object by 180%
	-multiplies efficiency of enemy by 180%
	-multiplies efficiency of player by 180%
	-multiplies efficiency of level by 180%
	-multiplies efficiency of game by 180%
	-multiplies efficiency of fanbase by 180%
	-multiplies efficiency of forum by 180%
	-multiplies efficiency of advertise by 180%
	-multiplies efficiency of studio by 180%
	-multiplies efficiency of magic by 180%
	-multiplies efficiency of gameSeries by 180%
	-multiplies efficiency of popularYoutuber by 180%
	-multiplies efficiency of gameProducer by 180%
	-multiplies efficiency of highReviewer by 180%
	-multiplies efficiency of maganiumGenerator by 180%
	-multiplies efficiency of finality by 180%
	-multiplies efficiency of magicPointBuilding by 180%
	-picture : http://i.imgur.com/lioGdC4.png

	*alternateUniverseReset32
	-"Everything is 90% more efficient. <br><i>You've got to be kidding me.</i>
	-costs 10000000000000000000000000000 code
	-costs 1000000000000000000 game2
	-costs 100000000000000 positiveReview
	-named Fifth Ultimate Ascend
	-unlocks at 100000000000 prestige
	-multiplies efficiency of writeCode by 190%
	-multiplies efficiency of codeWriter by 190%
	-multiplies efficiency of object by 190%
	-multiplies efficiency of enemy by 190%
	-multiplies efficiency of player by 190%
	-multiplies efficiency of level by 190%
	-multiplies efficiency of game by 190%
	-multiplies efficiency of fanbase by 190%
	-multiplies efficiency of forum by 190%
	-multiplies efficiency of advertise by 190%
	-multiplies efficiency of studio by 190%
	-multiplies efficiency of magic by 190%
	-multiplies efficiency of gameSeries by 190%
	-multiplies efficiency of popularYoutuber by 190%
	-multiplies efficiency of gameProducer by 190%
	-multiplies efficiency of highReviewer by 190%
	-multiplies efficiency of maganiumGenerator by 190%
	-multiplies efficiency of finality by 190%
	-multiplies efficiency of magicPointBuilding by 190%
	-picture : http://i.imgur.com/lioGdC4.png

	*alternateUniverseReset33
	-"Everything is twice efficient. <br><i>For being a tryhard.<br><br>Legend has it that there is an ascension castle in a far away land. Should we find it, we will be able to use the ascensions.</i>
	-costs 100000000000000000000000000000 code
	-costs 10000000000000000000 game2
	-costs 1000000000000000 positiveReview
	-named A trophy
	-unlocks at 1000000000000 prestige
	-multiplies efficiency of writeCode by 200%
	-multiplies efficiency of codeWriter by 200%
	-multiplies efficiency of object by 200%
	-multiplies efficiency of enemy by 200%
	-multiplies efficiency of player by 200%
	-multiplies efficiency of level by 200%
	-multiplies efficiency of game by 200%
	-multiplies efficiency of fanbase by 200%
	-multiplies efficiency of forum by 200%
	-multiplies efficiency of advertise by 200%
	-multiplies efficiency of studio by 200%
	-multiplies efficiency of magic by 200%
	-multiplies efficiency of gameSeries by 200%
	-multiplies efficiency of popularYoutuber by 200%
	-multiplies efficiency of gameProducer by 200%
	-multiplies efficiency of highReviewer by 200%
	-multiplies efficiency of maganiumGenerator by 200%
	-multiplies efficiency of finality by 200%
	-multiplies efficiency of magicPointBuilding by 200%
	-picture : http://i.imgur.com/ejDaFz2.png

	*alternateUniverseReset35
	-"Everything is 2.2 times as efficient. <br><i>The Ascension Castle contains the power of so many ascensions. 24, to be exact. There are orbs that carry the power of ascensions. To activate them, we need lots of godly lines of code, and ordinary code.<br>The first one was in the outer moat of the castle.</i>
	-costs 10000000000000000000000000000000 code
	-costs 1000000000000000000000 game2
	-costs 100000000000000000 positiveReview
	-named Ascension Type Alpha
	-unlocks at 100000000000000 prestige
	-multiplies efficiency of writeCode by 220%
	-multiplies efficiency of codeWriter by 220%
	-multiplies efficiency of object by 220%
	-multiplies efficiency of enemy by 220%
	-multiplies efficiency of player by 220%
	-multiplies efficiency of level by 220%
	-multiplies efficiency of game by 220%
	-multiplies efficiency of fanbase by 220%
	-multiplies efficiency of forum by 220%
	-multiplies efficiency of advertise by 220%
	-multiplies efficiency of studio by 220%
	-multiplies efficiency of magic by 220%
	-multiplies efficiency of gameSeries by 220%
	-multiplies efficiency of popularYoutuber by 220%
	-multiplies efficiency of gameProducer by 220%
	-multiplies efficiency of highReviewer by 220%
	-multiplies efficiency of maganiumGenerator by 220%
	-multiplies efficiency of finality by 220%
	-multiplies efficiency of magicPointBuilding by 220%
	-picture : http://i.imgur.com/r7zGlmm.png
	*alternateUniverseReset36
	-"Everything is 2.4 times as efficient. <br><i>We found a dungeon hidden in the outer moat. At the end of it, an orb rested on a pedestal. <br><br>This ascension is a beta. Expect things to be broken!</i>
	-costs 100000000000000000000000000000000 code
	-costs 10000000000000000000000 game2
	-costs 1000000000000000000 positiveReview
	-named Ascension Type Beta
	-unlocks at 1000000000000000 prestige
	-multiplies efficiency of writeCode by 240%
	-multiplies efficiency of codeWriter by 240%
	-multiplies efficiency of object by 240%
	-multiplies efficiency of enemy by 240%
	-multiplies efficiency of player by 240%
	-multiplies efficiency of level by 240%
	-multiplies efficiency of game by 240%
	-multiplies efficiency of fanbase by 240%
	-multiplies efficiency of forum by 240%
	-multiplies efficiency of advertise by 240%
	-multiplies efficiency of studio by 240%
	-multiplies efficiency of magic by 240%
	-multiplies efficiency of gameSeries by 240%
	-multiplies efficiency of popularYoutuber by 240%
	-multiplies efficiency of gameProducer by 240%
	-multiplies efficiency of highReviewer by 240%
	-multiplies efficiency of maganiumGenerator by 240%
	-multiplies efficiency of finality by 240%
	-multiplies efficiency of magicPointBuilding by 240%
	-picture : http://i.imgur.com/7YUsBOV.png
	*alternateUniverseReset37
	-"Everything is 2.6 times as efficient. <br><i>The inner moat was lava. After convincing the wizards to give us fore resistance, we went into the moat. We found another orb in there. <br><br>This ascension doesn't involve gamma rays.</i>
	-costs 1000000000000000000000000000000000 code
	-costs 100000000000000000000000 game2
	-costs 10000000000000000000 positiveReview
	-named Ascension Type Gamma
	-unlocks at 10000000000000000 prestige
	-multiplies efficiency of writeCode by 260%
	-multiplies efficiency of codeWriter by 260%
	-multiplies efficiency of object by 260%
	-multiplies efficiency of enemy by 260%
	-multiplies efficiency of player by 260%
	-multiplies efficiency of level by 260%
	-multiplies efficiency of game by 260%
	-multiplies efficiency of fanbase by 260%
	-multiplies efficiency of forum by 260%
	-multiplies efficiency of advertise by 260%
	-multiplies efficiency of studio by 260%
	-multiplies efficiency of magic by 260%
	-multiplies efficiency of gameSeries by 260%
	-multiplies efficiency of popularYoutuber by 260%
	-multiplies efficiency of gameProducer by 260%
	-multiplies efficiency of highReviewer by 260%
	-multiplies efficiency of maganiumGenerator by 260%
	-multiplies efficiency of finality by 260%
	-multiplies efficiency of magicPointBuilding by 260%
	-picture : http://i.imgur.com/6PcGic1.png
	*alternateUniverseReset38
	-"Everything is 2.8 times as efficient. <br><i>There were little ledges just outside the castle. Guess what was on one of them? Another ascension orb.</i>
	-costs 10000000000000000000000000000000000 code
	-costs 1000000000000000000000000 game2
	-costs 100000000000000000000 positiveReview
	-named Ascension Type Delta
	-unlocks at 100000000000000000 prestige
	-multiplies efficiency of writeCode by 280%
	-multiplies efficiency of codeWriter by 280%
	-multiplies efficiency of object by 280%
	-multiplies efficiency of enemy by 280%
	-multiplies efficiency of player by 280%
	-multiplies efficiency of level by 280%
	-multiplies efficiency of game by 280%
	-multiplies efficiency of fanbase by 280%
	-multiplies efficiency of forum by 280%
	-multiplies efficiency of advertise by 280%
	-multiplies efficiency of studio by 280%
	-multiplies efficiency of magic by 280%
	-multiplies efficiency of gameSeries by 280%
	-multiplies efficiency of popularYoutuber by 280%
	-multiplies efficiency of gameProducer by 280%
	-multiplies efficiency of highReviewer by 280%
	-multiplies efficiency of maganiumGenerator by 280%
	-multiplies efficiency of finality by 280%
	-multiplies efficiency of magicPointBuilding by 280%
	-picture : http://i.imgur.com/bYCLrSE.png
	*alternateUniverseReset39
	-"Everything is 3 times as efficient. <br><i>We found a switch hidden on a wall. After pressing it, we found another orb.</i>
	-costs 100000000000000000000000000000000000 code
	-costs 10000000000000000000000000 game2
	-costs 1000000000000000000000 positiveReview
	-named Ascension Type Epsilon
	-unlocks at 1000000000000000000 prestige
	-multiplies efficiency of writeCode by 300%
	-multiplies efficiency of codeWriter by 300%
	-multiplies efficiency of object by 300%
	-multiplies efficiency of enemy by 300%
	-multiplies efficiency of player by 300%
	-multiplies efficiency of level by 300%
	-multiplies efficiency of game by 300%
	-multiplies efficiency of fanbase by 300%
	-multiplies efficiency of forum by 300%
	-multiplies efficiency of advertise by 300%
	-multiplies efficiency of studio by 300%
	-multiplies efficiency of magic by 300%
	-multiplies efficiency of gameSeries by 300%
	-multiplies efficiency of popularYoutuber by 300%
	-multiplies efficiency of gameProducer by 300%
	-multiplies efficiency of highReviewer by 300%
	-multiplies efficiency of maganiumGenerator by 300%
	-multiplies efficiency of finality by 300%
	-multiplies efficiency of magicPointBuilding by 300%
	-picture : http://i.imgur.com/uiJkOOW.png
	*alternateUniverseReset40
	-"Everything is 3.2 times as efficient. <br><i>We went in and found a room to the left. There were three electric barriers. One orb was just to the left of us.</i>
	-costs 1000000000000000000000000000000000000 code
	-costs 100000000000000000000000000 game2
	-costs 10000000000000000000000 positiveReview
	-named Ascension Type Zeta
	-unlocks at 10000000000000000000 prestige
	-multiplies efficiency of writeCode by 320%
	-multiplies efficiency of codeWriter by 320%
	-multiplies efficiency of object by 320%
	-multiplies efficiency of enemy by 320%
	-multiplies efficiency of player by 320%
	-multiplies efficiency of level by 320%
	-multiplies efficiency of game by 320%
	-multiplies efficiency of fanbase by 320%
	-multiplies efficiency of forum by 320%
	-multiplies efficiency of advertise by 320%
	-multiplies efficiency of studio by 320%
	-multiplies efficiency of magic by 320%
	-multiplies efficiency of gameSeries by 320%
	-multiplies efficiency of popularYoutuber by 320%
	-multiplies efficiency of gameProducer by 320%
	-multiplies efficiency of highReviewer by 320%
	-multiplies efficiency of maganiumGenerator by 320%
	-multiplies efficiency of finality by 320%
	-multiplies efficiency of magicPointBuilding by 320%
	-picture : http://i.imgur.com/9Dou0sL.png
	*alternateUniverseReset41
	-"Everything is twice efficient. <br><i>When we deactivated the barriers, there was another orb, resting on a pedestal.</i>
	-costs 10000000000000000000000000000000000000 code
	-costs 1000000000000000000000000000 game2
	-costs 100000000000000000000000 positiveReview
	-named Ascension Type Eta
	-unlocks at 100000000000000000000 prestige
	-multiplies efficiency of writeCode by 340%
	-multiplies efficiency of codeWriter by 340%
	-multiplies efficiency of object by 340%
	-multiplies efficiency of enemy by 340%
	-multiplies efficiency of player by 340%
	-multiplies efficiency of level by 340%
	-multiplies efficiency of game by 340%
	-multiplies efficiency of fanbase by 340%
	-multiplies efficiency of forum by 340%
	-multiplies efficiency of advertise by 340%
	-multiplies efficiency of studio by 340%
	-multiplies efficiency of magic by 340%
	-multiplies efficiency of gameSeries by 340%
	-multiplies efficiency of popularYoutuber by 340%
	-multiplies efficiency of gameProducer by 340%
	-multiplies efficiency of highReviewer by 340%
	-multiplies efficiency of maganiumGenerator by 340%
	-multiplies efficiency of finality by 340%
	-multiplies efficiency of magicPointBuilding by 340%
	-picture : http://i.imgur.com/e3M7QWk.png
	*alternateUniverseReset42
	-"Everything is 3.6 times as efficient. <br><i>A scroll... which has a map. It tells us that an orb is buried outside. Let's find it.</i>
	-costs 100000000000000000000000000000000000000 code
	-costs 10000000000000000000000000000 game2
	-costs 1000000000000000000000000 positiveReview
	-named Ascension Type Theta
	-unlocks at 1000000000000000000000 prestige
	-multiplies efficiency of writeCode by 360%
	-multiplies efficiency of codeWriter by 360%
	-multiplies efficiency of object by 360%
	-multiplies efficiency of enemy by 360%
	-multiplies efficiency of player by 360%
	-multiplies efficiency of level by 360%
	-multiplies efficiency of game by 360%
	-multiplies efficiency of fanbase by 360%
	-multiplies efficiency of forum by 360%
	-multiplies efficiency of advertise by 360%
	-multiplies efficiency of studio by 360%
	-multiplies efficiency of magic by 360%
	-multiplies efficiency of gameSeries by 360%
	-multiplies efficiency of popularYoutuber by 360%
	-multiplies efficiency of gameProducer by 360%
	-multiplies efficiency of highReviewer by 360%
	-multiplies efficiency of maganiumGenerator by 360%
	-multiplies efficiency of finality by 360%
	-multiplies efficiency of magicPointBuilding by 360%
	-picture : http://i.imgur.com/F89UQY6.png
	*alternateUniverseReset43
	-"Everything is 3.8 times as efficient. <br><i>Another room of the ascension castle has just a wall. After destroying it, we found a pedestal with an orb.</i>
	-costs 1000000000000000000000000000000000000000 code
	-costs 100000000000000000000000000000 game2
	-costs 10000000000000000000000000 positiveReview
	-named Ascension Type Iota
	-unlocks at 10000000000000000000000 prestige
	-multiplies efficiency of writeCode by 380%
	-multiplies efficiency of codeWriter by 380%
	-multiplies efficiency of object by 380%
	-multiplies efficiency of enemy by 380%
	-multiplies efficiency of player by 380%
	-multiplies efficiency of level by 380%
	-multiplies efficiency of game by 380%
	-multiplies efficiency of fanbase by 380%
	-multiplies efficiency of forum by 380%
	-multiplies efficiency of advertise by 380%
	-multiplies efficiency of studio by 380%
	-multiplies efficiency of magic by 380%
	-multiplies efficiency of gameSeries by 380%
	-multiplies efficiency of popularYoutuber by 380%
	-multiplies efficiency of gameProducer by 380%
	-multiplies efficiency of highReviewer by 380%
	-multiplies efficiency of maganiumGenerator by 380%
	-multiplies efficiency of finality by 200%
	-multiplies efficiency of magicPointBuilding by 200%
	-picture : http://i.imgur.com/ySSI1io.png
	*alternateUniverseReset44
	-"Everything is 4 times as efficient. <br><i>We broke the wall behind the pedestal, and found yet another ascension orb.<br><br>"This ascension = Grey space (no face)" ~praisehelix008</i>
	-costs 10000000000000000000000000000000000000000 code
	-costs 1000000000000000000000000000000 game2
	-costs 100000000000000000000000000 positiveReview
	-named Ascension Type Kappa
	-unlocks at 100000000000000000000000 prestige
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-picture : http://i.imgur.com/oSeITBx.png
	*alternateUniverseReset45
	-"Everything is 4 times as efficient. <br><i>e broke every other wall and found an orb.</i>
	-costs 100000000000000000000000000000000000000000 code
	-costs 10000000000000000000000000000000 game2
	-costs 1000000000000000000000000000 positiveReview
	-named Ascension Type Lambda
	-unlocks at 1000000000000000000000000 prestige
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-picture : http://i.imgur.com/rdvL4Wm.png
	*alternateUniverseReset46
	-"Everything is 4 times as efficient. <br><i>We went to another room, which was nearly destroyed. An orb was underneath some rubble.</i>
	-costs 1000000000000000000000000000000000000000000 code
	-costs 100000000000000000000000000000000 game2
	-costs 10000000000000000000000000000 positiveReview
	-named Ascension Type Mu
	-unlocks at 10000000000000000000000000 prestige
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-picture : http://i.imgur.com/ADdTaqP.png
	*alternateUniverseReset47
	-"Everything is 4 times as efficient. <br><i>Another orb was hidden in the fireplace of another room.</i>
	-costs 10000000000000000000000000000000000000000000 code
	-costs 1000000000000000000000000000000000 game2
	-costs 100000000000000000000000000000 positiveReview
	-named Ascension Type Nu
	-unlocks at 100000000000000000000000000 prestige
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-picture : http://i.imgur.com/85Xxt8N.png
	*alternateUniverseReset48
	-"Everything is 4 times as efficient. <br><i>There was a hidden passage in the fireplace. It led to the 14th orb of the castle.</i>
	-costs 100000000000000000000000000000000000000000000 code
	-costs 10000000000000000000000000000000000 game2
	-costs 1000000000000000000000000000000 positiveReview
	-named Ascension Type Xi
	-unlocks at 1000000000000000000000000000 prestige
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-picture : http://i.imgur.com/mUk2XvG.png
	*alternateUniverseReset49
	-"Everything is 4 times as efficient. <br><i>There were some towers. An orb was at the top of one tower.</i>
	-costs 1000000000000000000000000000000000000000000000 code
	-costs 100000000000000000000000000000000000 game2
	-costs 10000000000000000000000000000000 positiveReview
	-named Ascension Type Omicron
	-unlocks at 10000000000000000000000000000 prestige
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-picture : http://i.imgur.com/OaQySax.png
	*alternateUniverseReset50
	-"Everything is 4 times as efficient. <br><i>We had to write down 1,000 digits of pi on the wall to get this one.</i>
	-costs 10000000000000000000000000000000000000000000000 code
	-costs 1000000000000000000000000000000000000 game2
	-costs 100000000000000000000000000000000 positiveReview
	-named Ascension Type Pi
	-unlocks at 100000000000000000000000000000 prestige
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-picture : http://i.imgur.com/zrkKKlK.png
	*alternateUniverseReset51
	-"Everything is 4 times as efficient. <br><i>We went into a "super difficult dungeon". The first round of monsters was easy. This was the reward for winning.</i>
	-costs 100000000000000000000000000000000000000000000000 code
	-costs 10000000000000000000000000000000000000 game2
	-costs 1000000000000000000000000000000000 positiveReview
	-named Ascension Type Rho
	-unlocks at 1000000000000000000000000000000 prestige
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-picture : http://i.imgur.com/ahdAE0W.png
	*alternateUniverseReset52
	-"Everything is 4 times as efficient. <br><i>The second round of monsters was a little harder. But, we dealt with it.</i>
	-costs 1000000000000000000000000000000000000000000000000 code
	-costs 100000000000000000000000000000000000000 game2
	-costs 10000000000000000000000000000000000 positiveReview
	-named Ascension Type Sigma
	-unlocks at 10000000000000000000000000000000 prestige
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-picture : http://i.imgur.com/Y8llCNd.png
	*alternateUniverseReset53
	-"Everything is 4 times as efficient. <br><i>The final round was against godly monsters. We're halfway through the battle, and we got this.</i>
	-costs 10000000000000000000000000000000000000000000000000 code
	-costs 1000000000000000000000000000000000000000 game2
	-costs 100000000000000000000000000000000000 positiveReview
	-named Ascension Type Tau
	-unlocks at 100000000000000000000000000000000 prestige
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-picture : http://i.imgur.com/xDoWC7n.png
	*alternateUniverseReset54
	-"Everything is 4 times as efficient. <br><i>At the end of the long battle, we were granted this ascension orb.</i>
	-costs 100000000000000000000000000000000000000000000000000 code
	-costs 10000000000000000000000000000000000000000 game2
	-costs 1000000000000000000000000000000000000 positiveReview
	-named Ascension Type Upsilon
	-unlocks at 1000000000000000000000000000000000 prestige
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-picture : http://i.imgur.com/0mfkdUB.png
	*alternateUniverseReset55
	-"Everything is 4 times as efficient. <br><i>At the top of the Giant Tower, there was a portal and another orb.</i>
	-costs 1000000000000000000000000000000000000000000000000000 code
	-costs 100000000000000000000000000000000000000000 game2
	-costs 10000000000000000000000000000000000000 positiveReview
	-named Ascension Type Phi
	-unlocks at 10000000000000000000000000000000000 prestige
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-picture : http://i.imgur.com/PL4Qg9z.png
	*alternateUniverseReset56
	-"Everything is 4 times as efficient. <br><i>The portal led to a Golden Temple. We went up a thousand steps to find the first orb there.<br><br>It is said that the three ascension orbs represented three different gods. The first one represented the Cookie...</i>
	-costs 10000000000000000000000000000000000000000000000000000 code
	-costs 1000000000000000000000000000000000000000000 game2
	-costs 100000000000000000000000000000000000000 positiveReview
	-named Ascension Type Chi
	-unlocks at 100000000000000000000000000000000000 prestige
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-picture : http://i.imgur.com/F9aiQUO.png
	*alternateUniverseReset58
	-"Everything is 4 times as efficient. <br><i>Eventually the steps stopped. We had to climb the slope to get to the ascension orb Psi.<br><br>...the second one represented "egg"...</i>
	-costs 10000000000000000000000000000000000000000000000000000 code
	-costs 1000000000000000000000000000000000000000000 game2
	-costs 100000000000000000000000000000000000000 positiveReview
	-named Ascension Type Psi
	-unlocks at 100000000000000000000000000000000000 prestige
	-multiplies efficiency of writeCode by 400%
	-multiplies efficiency of codeWriter by 400%
	-multiplies efficiency of object by 400%
	-multiplies efficiency of enemy by 400%
	-multiplies efficiency of player by 400%
	-multiplies efficiency of level by 400%
	-multiplies efficiency of game by 400%
	-multiplies efficiency of fanbase by 400%
	-multiplies efficiency of forum by 400%
	-multiplies efficiency of advertise by 400%
	-multiplies efficiency of studio by 400%
	-multiplies efficiency of magic by 400%
	-multiplies efficiency of gameSeries by 400%
	-multiplies efficiency of popularYoutuber by 400%
	-multiplies efficiency of gameProducer by 400%
	-multiplies efficiency of highReviewer by 400%
	-multiplies efficiency of maganiumGenerator by 400%
	-multiplies efficiency of finality by 400%
	-multiplies efficiency of magicPointBuilding by 400%
	-picture : http://i.imgur.com/DsAAlvh.png
	*alternateUniverseReset57
	-"Everything is 7 times as efficient. <br><i>Eventually, it was just straight up. It took ages to climb (we needed a lot of ascension power), but, we did it! There was a giant room that seemed to be made of code, and there was the ascension orb. The last one. Time to go home.<br><br>And the final one represented the God of Code. The third was said to be the most powerful, and it possibly had an influence on Earth, and developing games.</i>
	-costs 100000000000000000000000000000000000000000000000000000 code
	-costs 10000000000000000000000000000000000000000000 game2
	-costs 1000000000000000000000000000000000000000 positiveReview
	-named Ascension Type Omega
	-unlocks at 1000000000000000000000000000000000000 prestige
	-multiplies efficiency of writeCode by 700%
	-multiplies efficiency of codeWriter by 700%
	-multiplies efficiency of object by 700%
	-multiplies efficiency of enemy by 700%
	-multiplies efficiency of player by 700%
	-multiplies efficiency of level by 700%
	-multiplies efficiency of game by 700%
	-multiplies efficiency of fanbase by 700%
	-multiplies efficiency of forum by 700%
	-multiplies efficiency of advertise by 700%
	-multiplies efficiency of studio by 700%
	-multiplies efficiency of magic by 700%
	-multiplies efficiency of gameSeries by 700%
	-multiplies efficiency of popularYoutuber by 700%
	-multiplies efficiency of gameProducer by 700%
	-multiplies efficiency of highReviewer by 700%
	-multiplies efficiency of maganiumGenerator by 700%
	-multiplies efficiency of finality by 700%
	-multiplies efficiency of magicPointBuilding by 700%
	-picture : http://i.imgur.com/eB9fcKw.png


Achievements:


	*alltimeAchieve1
	-"Write one line of code."
	-unlocks at 1 totalCode
	-named Let's make a game!
	-picture : http://i.imgur.com/GsOKd4T.png
	*alltimeAchieve2
	-"Write 150 lines of code."
	-unlocks at 150 totalCode
	-named Adding objects
	-picture : http://i.imgur.com/jg25zTJ.png
	*alltimeAchieve3
	-"Write 800 lines of code."
	-unlocks at 800 totalCode
	-named Newbie coder
	-picture : http://i.imgur.com/78PdK8q.png
	*alltimeAchieve4
	-"Write 10,000 lines of code."
	-unlocks at 10000 totalCode
	-named Beginner coder
	-picture : http://i.imgur.com/MJ1j8uo.png
	*alltimeAchieve5
	-"Write 150,000 lines of code."
	-unlocks at 150000 totalCode
	-named Intermediate coder
	-picture : http://i.imgur.com/Nis3qlm.png
	*alltimeAchieve6
	-"Write 5,000,000 lines of code."
	-unlocks at 5000000 totalCode
	-named It's out
	-picture : http://i.imgur.com/SJaSIJa.png
	*alltimeAchieve7
	-"Write 100,000,000 lines of code."
	-unlocks at 100000000 totalCode
	-named Expert coder
	-picture : http://i.imgur.com/JpJVYph.png
	*alltimeAchieve8
	-"Write 10,000,000,000 lines of code."
	-unlocks at 10000000000 totalCode
	-named Famous company
	-picture : http://i.imgur.com/NJUk4tU.png
	*alltimeAchieve9
	-"Write 150,000,000,000 lines of code."
	-unlocks at 150000000000 totalCode
	-named ''best game ever 5/5''
	-picture : http://i.imgur.com/QE98zMD.png
	*alltimeAchieve10
	-"Write 2,000,000,000,000 lines of code."
	-unlocks at 2000000000000 totalCode
	-named Studio leader
	-picture : http://i.imgur.com/jfLf6WV.png
	*alltimeAchieve11
	-"Overtake Call of Duty.<br> <i> goddamn overrated game 1/5 ~xX420noscopeXx</i>"
	-unlocks at 1 overtake2
	-named Success!
	-picture : http://i.imgur.com/oObczjC.png
	*alltimeAchieve12
	-"Overtake Sonic.<br> <i>Gotta code fast!</i>"
	-unlocks at 1 overtake4
	-named World-famous
	-picture : http://i.imgur.com/Nf7rkFa.png
	*alltimeAchieve13
	-"Overtake GTA. <br><i>screw cod. this game is THE shit. 5/5 ~xX420noscopeXx"
	-unlocks at 1 overtake7
	-named Ascending
	-picture : http://i.imgur.com/kgXxI10.png
	*alltimeAchieve14
	-"Overtake Pokémon. <br><i>Your game company is essentially becoming an empire at this point.</i>"
	-unlocks at 1 overtake9
	-named Game company empire
	-picture : http://i.imgur.com/vfwJN5V.png
	*alltimeAchieve15
	-"Overtake Mario. <br><i>ggs ~MOUNTAINDEWHARDCORE"
	-unlocks at 1 overtake10
	-named Largest empire ever
	-picture : http://i.imgur.com/yXYKOiS.png
	*alltimeAchieve16
	-"Win the game with 200 of everything. <br><i>I think we can safely say that we have won now... or have we?"
	-unlocks at 1 win
	-named You're winner
	-picture : http://i.imgur.com/yXYKOiS.png
	*alltimeAchieve17
	-"Win the game with 300 of everything. <br><i>OK, we've definitely one now. Wait a moment..."
	-unlocks at 1 win2
	-named A winner is you
	-picture : http://i.imgur.com/yXYKOiS.png
	*alltimeAchieve18
	-"Win the game with 400 of everything. <br><i>''get a life lol'' ~xbox420blazeitguy"
	-unlocks at 1 win3
	-named You are a winrar
	-picture : http://i.imgur.com/yXYKOiS.png
	*alltimeAchieve19
	-"Win the game with 500 of everything. <br><i>"
	-unlocks at 1 win4
	-named Congraturation
	-picture : http://i.imgur.com/yXYKOiS.png
	*alltimeAchieve20
	-"Win the game with 700 of everything. <br><i>"
	-unlocks at 1 win6
	-named Pure Win
	-picture : http://i.imgur.com/yXYKOiS.png
	*alltimeAchieve21
	-"Win the game with 1,000 of everything. <br><i>This is not a true end! Win the game with 1,200 of everything."
	-unlocks at 1 win9
	-named Bad End
	-picture : http://i.imgur.com/yXYKOiS.png
	*alltimeAchieve22
	-"Win the game with 1,200 of everything. <br><i>"
	-unlocks at 1 win10
	-named Happy End!
	-picture : http://i.imgur.com/yXYKOiS.png

	*milestoneAchieve1
	-"Milestone for writing <b>1 million</b> code."
	-unlocks at 1e+6 totalCode
	-named Million Mark
	-picture : http://i.imgur.com/X57CrJe.png
	*milestoneAchieve2
	-"Milestone for writing <b>1 billion</b> code."
	-unlocks at 1e+9 totalCode
	-named Busting the Billion
	-picture : http://i.imgur.com/zgUVOwE.png
	*milestoneAchieve3
	-"Milestone for writing <b>1 trillion</b> code."
	-unlocks at 1e+12 totalCode
	-named That was Trillion
	-picture : http://i.imgur.com/xTR1HJj.png
	*milestoneAchieve4
	-"Milestone for writing <b>1 quadrillion</b> code."
	-unlocks at 1e+15 totalCode
	-named On Quads
	-picture : http://i.imgur.com/imzrJRJ.png
	*milestoneAchieve5
	-"Milestone for writing <b>1 quintillion</b> code."
	-unlocks at 1e+18 totalCode
	-named Don't Quint Yet
	-picture : http://i.imgur.com/t6M61Sj.png
	*milestoneAchieve6
	-"Milestone for writing <b>1 sextillion</b> code."
	-unlocks at 1e+21 totalCode
	-named Sextillion Club
	-picture : http://i.imgur.com/7bf6Gr0.png
	*milestoneAchieve7
	-"Milestone for writing <b>1 septillion</b> code."
	-unlocks at 1e+24 totalCode
	-named Septillion Club
	-picture : http://i.imgur.com/qNBMaat.png
	*milestoneAchieve8
	-"Milestone for writing <b>1 octillion</b> code."
	-unlocks at 1e+27 totalCode
	-named Octillion Club
	-picture : http://i.imgur.com/4Xs1YWG.png
	*milestoneAchieve9
	-"Milestone for writing <b>1 nonillion</b> code."
	-unlocks at 1e+30 totalCode
	-named Never Not Nonillion
	-picture : http://i.imgur.com/Bm5BzdL.png
	*milestoneAchieve10
	-"Milestone for writing <b>1 decillion</b> code."
	-unlocks at 1e+33 totalCode
	-named Decimating Decillion
	-picture : http://i.imgur.com/sqR7LlH.png
	*milestoneAchieve11
	-"Milestone for writing <b>1 undecillion</b> code."
	-unlocks at 1e+36 totalCode
	-named Undecillion Club
	-picture : http://i.imgur.com/i8Rqnag.png
	*milestoneAchieve12
	-"Milestone for writing <b>1 duodecillion</b> code."
	-unlocks at 1e+39 totalCode
	-named Duodecillion Club
	-picture : http://i.imgur.com/Du0py34.png
	*milestoneAchieve13
	-"Milestone for writing <b>1 tredecillion</b> code."
	-unlocks at 1e+42 totalCode
	-named Tredecillion Club
	-picture : http://i.imgur.com/QH4CMEa.png
	*milestoneAchieve14
	-"Milestone for writing <b>1 quattuorillion</b> code."
	-unlocks at 1e+45 totalCode
	-named Quattuordecillion Club
	-picture : http://i.imgur.com/5IcqcdV.png
	*milestoneAchieve15
	-"Milestone for writing <b>1 quindecillion</b> code."
	-unlocks at 1e+48 totalCode
	-named Quindecillion Club
	-picture : http://i.imgur.com/AODx7w2.png
	*milestoneAchieve16
	-"Milestone for writing <b>1 sexdecillion</b> code."
	-unlocks at 1e+51 totalCode
	-named Sexdecillion Club
	-picture : http://i.imgur.com/0dTGO9c.png
	*milestoneAchieve17
	-"Milestone for writing <b>1 septendecillion</b> code."
	-unlocks at 1e+54 totalCode
	-named Septendecillion Club
	-picture : http://i.imgur.com/oQcxoxm.png
	*milestoneAchieve18
	-"Milestone for writing <b>1 octodecillion</b> code."
	-unlocks at 1e+57 totalCode
	-named Octodecillion Club
	-picture : http://i.imgur.com/T4CdXt4.png
	*milestoneAchieve19
	-"Milestone for writing <b>1 novemdecillion</b> code."
	-unlocks at 1e+60 totalCode
	-named Novemdecillion Club
	-picture : http://i.imgur.com/TTiXCIj.png
	*milestoneAchieve20
	-"Milestone for writing <b>1 vigintillion</b> code."
	-unlocks at 1e+63 totalCode
	-named Vigintillion
	-picture : http://i.imgur.com/RtTsPSY.png

	*playtimeAchieve1
	-"Play the game for one minute.
	-unlocks at 60 time
	-named We've just started
	-picture : http://i.imgur.com/WjM2HmH.png
	*playtimeAchieve2
	-"Play the game for ten minutes.
	-unlocks at 600 time
	-named Ten-minute run
	-picture : http://i.imgur.com/KDOfNlq.png
	*playtimeAchieve3
	-"Play the game for one hour.
	-unlocks at 3600 time
	-named One hour wasted
	-picture : http://i.imgur.com/pivMW9X.png
	*playtimeAchieve4
	-"Play the game for three hours.
	-unlocks at 10800 time
	-named Wasting time
	-picture : http://i.imgur.com/86RAVM5.png
	*playtimeAchieve5
	-"Play the game for one day.
	-unlocks at 86400 time
	-named Daily Player
	-picture : http://i.imgur.com/CaYQJ8W.png
	*playtimeAchieve6
	-"Play the game for two days.
	-unlocks at 172800 time
	-named Badly spent time
	-picture : http://i.imgur.com/cmBW6mk.png
	*playtimeAchieve7
	-"Play the game for one week.
	-unlocks at 604800 time
	-named Weekly Player
	-picture : http://i.imgur.com/IV4zqxl.png
	*playtimeAchieve8
	-"Play the game for two weeks.
	-unlocks at 1209600 time
	-named Bored
	-picture : http://i.imgur.com/mw3Ql5t.png
	*playtimeAchieve9
	-"Play the game for four weeks.
	-unlocks at 2419200 time
	-named Insane player
	-picture : http://i.imgur.com/EycDBgR.png
	*playtimeAchieve10
	-"Play the game for two months.
	-unlocks at 5184000 time
	-named Addicted
	-picture : http://i.imgur.com/phuZIhK.png
	*playtimeAchieve11
	-"Play the game for three months.
	-unlocks at 7776000 time
	-named Seriously Addicted
	-picture : http://i.imgur.com/5dcDNsD.png
	*playtimeAchieve12
	-"Play the game for six months.
	-unlocks at 15552000 time
	-named Extremely Addicted
	-picture : http://i.imgur.com/ATzIrEX.png
	*playtimeAchieve13
	-"Play the game for nine months.
	-unlocks at 23328000 time
	-named Seriously?
	-picture : http://i.imgur.com/FgfebrM.png
	*playtimeAchieve14
	-"Play the game for one year.
	-unlocks at 31104000 time
	-named SERIOUSLY?!?
	-picture : http://i.imgur.com/LLxDPlr.png

	*manualAchieve1
	-"Write 101 lines of code manually.
	-unlocks at 101 manualWritten
	-named The beginning
	-picture : http://i.imgur.com/vSkVuYD.png
	*manualAchieve2
	-"Write 10,101 lines of code manually.
	-unlocks at 10101 manualWritten
	-named lrn2code
	-picture : http://i.imgur.com/rlS1gKM.png
	*manualAchieve3
	-"Write 1,010,101 lines of code manually.
	-unlocks at 1010101 manualWritten
	-named Coding for dummies
	-picture : http://i.imgur.com/fSkOz65.png
	*manualAchieve4
	-"Write 101,010,101 lines of code manually.
	-unlocks at 101010101 manualWritten
	-named The secret code
	-picture : http://i.imgur.com/Qvc4jgm.png
	*manualAchieve5
	-"Write 10,101,010,101 lines of code manually.
	-unlocks at 10101010101 manualWritten
	-named Codename
	-picture : http://i.imgur.com/YHvJv1o.png
	*manualAchieve6
	-"Write 1,010,101,010,101 lines of code manually.
	-unlocks at 1010101010101 manualWritten
	-named The decoder
	-picture : http://i.imgur.com/nThLiO3.png
	*manualAchieve7
	-"Write 101,010,101,010,101 lines of code manually.
	-unlocks at 101010101010101 manualWritten
	-named Coding day
	-picture : http://i.imgur.com/V1nDWoo.png
	*manualAchieve8
	-"Write 10 peta lines of code manually.
	-unlocks at 1e+16 manualWritten
	-named Year of the code
	-picture : http://i.imgur.com/HytnCzB.png
	*manualAchieve9
	-"Write 1 exa lines of code manually.
	-unlocks at 1e+18 manualWritten
	-named The Great Code
	-picture : http://i.imgur.com/68aLRXZ.png
	*manualAchieve10
	-"Write 101 exa lines of code manually.
	-unlocks at 1.01e+20 manualWritten
	-named Best coder ever
	-picture : http://i.imgur.com/V9PMrrm.png
	*manualAchieve11
	-"Write 10 zetta lines of code manually.
	-unlocks at 1e+22 manualWritten
	-named Coding to infinity
	-picture : http://i.imgur.com/6VQslWd.png
	*manualAchieve12
	-"Write 1 yotta lines of code manually.
	-unlocks at 1e+24 manualWritten
	-named Coding beyond infinity
	-picture : http://i.imgur.com/dajUAc5.png

	*writerAchieve1
	-"Have 1 code writer.
	-unlocks at 1 codeWriter
	-named The first building
	-picture : http://i.imgur.com/v3UN7Rk.png
	*writerAchieve2
	-"Have 10 code writers.
	-unlocks at 10 codeWriter
	-named Coding Team
	-picture : http://i.imgur.com/rEGTZV6.png
	*writerAchieve3
	-"Have 40 code writers.
	-unlocks at 40 codeWriter
	-named Coding Company
	-picture : http://i.imgur.com/9ax6pn4.png
	*writerAchieve4
	-"Have 100 code writers.
	-unlocks at 100 codeWriter
	-named The Hundred Helpers
	-picture : http://i.imgur.com/wsb2WtD.png
	*writerAchieve5
	-"Have 150 code writers.
	-unlocks at 150 codeWriter
	-named Coding the town
	-picture : http://i.imgur.com/QD1JfQK.png
	*writerAchieve6
	-"Have 200 code writers.
	-unlocks at 200 codeWriter
	-named Coding the country
	-picture : http://i.imgur.com/Vnikuhh.png
	*writerAchieve7
	-"Have 300 code writers.
	-unlocks at 300 codeWriter
	-named Coding the world
	-picture : http://i.imgur.com/OaEcSm8.png
	*writerAchieve8
	-"Have 400 code writers.
	-unlocks at 400 codeWriter
	-named Coding reality itself
	-picture : http://i.imgur.com/uwcdty9.png
	*writerAllTimeAchieve1
	-"Write <b>1,000,000,000</b> code with just your code writers."
	-unlocks at 1000000000 codeWriterWritten
	-named Endless Coding
	-picture : http://i.imgur.com/v3UN7Rk.png
	*writerAllTimeAchieve3
	-"Write <b>1,000,000,000,000</b> code with just your code writers."
	-unlocks at 1000000000000 codeWriterWritten
	-named Code Mode
	-picture : http://i.imgur.com/QD1JfQK.png
	*writerAllTimeAchieve2
	-"Write <b>1,000,000,000,000,000</b> code with just your code writers."
	-unlocks at 1000000000000000 codeWriterWritten
	-named Recoding
	-picture : http://i.imgur.com/uwcdty9.png

	*objectAchieve1
	-"Have 1 object.
	-unlocks at 1 object
	-named Object of the game
	-picture : http://i.imgur.com/wJmuYFc.png
	*objectAchieve2
	-"Have 10 objects.
	-unlocks at 10 object
	-named Group of objects
	-picture : http://i.imgur.com/4eQt0Xk.png
	*objectAchieve3
	-"Have 40 objects.
	-unlocks at 40 object
	-named Objection!
	-picture : http://i.imgur.com/5Q5hNcI.png
	*objectAchieve4
	-"Have 100 objects.
	-unlocks at 100 object
	-named Collection of objects
	-picture : http://i.imgur.com/HnGxy2l.png
	*objectAchieve5
	-"Have 150 objects.
	-unlocks at 150 object
	-named Object Hoard
	-picture : http://i.imgur.com/GnbmWWc.png
	*objectAchieve6
	-"Have 200 objects.
	-unlocks at 200 object
	-named Object Not found
	-picture : http://i.imgur.com/tbnjb1f.png
	*objectAchieve7
	-"Have 300 objects.
	-unlocks at 300 object
	-named GLORIOUS OBJECT MASTER RACE
	-picture : http://i.imgur.com/X0RfaIV.png
	*objectAchieve8
	-"Have 400 objects.
	-unlocks at 400 object
	-named Objective Complete
	-picture : http://i.imgur.com/FbO2UQ5.png
	*objectAllTimeAchieve1
	-"Get <b>10,000,000,000</b> code with just your objects."
	-unlocks at 1000000000 objectWritten
	-named Conscientious Objector
	-picture : http://i.imgur.com/wJmuYFc.png
	*objectAllTimeAchieve3
	-"Get <b>10,000,000,000,000</b> code with just your objects."
	-unlocks at 1000000000000 objectWritten
	-named Supreme Objects
	-picture : http://i.imgur.com/jQsfTWF.png
	*objectAllTimeAchieve2
	-"Get <b>10,000,000,000,000,000</b> code with just your objects."
	-unlocks at 1000000000000000 objectWritten
	-named The Last Objective
	-picture : http://i.imgur.com/FbO2UQ5.png

	*enemyAchieve1
	-"Have 1 enemy.
	-unlocks at 1 enemy
	-named This is the enemy
	-picture : http://i.imgur.com/YfeGZKu.png
	*enemyAchieve2
	-"Have 10 enemies.
	-unlocks at 10 enemy
	-named Say hello to...
	-picture : http://i.imgur.com/nyLlRda.png
	*enemyAchieve3
	-"Have 40 enemies.
	-unlocks at 40 enemy
	-named Friend or Foe
	-picture : http://i.imgur.com/EFtQuHn.png
	*enemyAchieve4
	-"Have 100 enemies.
	-unlocks at 100 enemy
	-named Attack of the enemies
	-picture : http://i.imgur.com/nzO1NgE.png
	*enemyAchieve5
	-"Have 150 enemies.
	-unlocks at 150 enemy
	-named Keep your friends close...
	-picture : http://i.imgur.com/LIfEHrf.png
	*enemyAchieve6
	-"Have 200 enemies.
	-unlocks at 200 enemy
	-named The Great Horde
	-picture : http://i.imgur.com/zBvgLwa.png
	*enemyAchieve7
	-"Have 300 enemies.
	-unlocks at 300 enemy
	-named Surrounded by enemies
	-picture : http://i.imgur.com/6IMWnuf.png
	*enemyAchieve8
	-"Have 400 enemies.
	-unlocks at 400 enemy
	-named The Ultimate Challenge
	-picture : http://i.imgur.com/mKpNKQs.png
	*enemyAllTimeAchieve1
	-"Get <b>100,000,000,000</b> code with just your enemies."
	-unlocks at 10000000000 enemyWritten
	-named The extreme attack
	-picture : http://i.imgur.com/YfeGZKu.png
	*enemyAllTimeAchieve3
	-"Get <b>100,000,000,000,000</b> code with just your enemies."
	-unlocks at 10000000000000 enemyWritten
	-named Everything is an enemy
	-picture : http://i.imgur.com/LIfEHrf.png
	*enemyAllTimeAchieve2
	-"Get <b>100,000,000,000,000,000</b> code with just your enemies."
	-unlocks at 10000000000000000 enemyWritten
	-named The never-ending attack
	-picture : http://i.imgur.com/mKpNKQs.png

	*playerAchieve1
	-"Have 1 player.
	-unlocks at 1 player
	-named Forever alone
	-picture : http://i.imgur.com/BOiRUjn.png
	*playerAchieve2
	-"Have 10 players.
	-unlocks at 10 player
	-named A company
	-picture : http://i.imgur.com/DCyWQIm.png
	*playerAchieve3
	-"Have 40 players.
	-unlocks at 40 player
	-named A crowd
	-picture : http://i.imgur.com/C1b0bQs.png
	*playerAchieve4
	-"Have 100 players.
	-unlocks at 100 player
	-named A party
	-picture : http://i.imgur.com/wR9pPTy.png
	*playerAchieve5
	-"Have 150 players.
	-unlocks at 150 player
	-named The great regroup
	-picture : http://i.imgur.com/sUdjmIQ.png
	*playerAchieve6
	-"Have 200 players.
	-unlocks at 200 player
	-named Massive Team
	-picture : http://i.imgur.com/IPDhQPc.png
	*playerAchieve7
	-"Have 300 players.
	-unlocks at 300 player
	-named Unstoppable Team
	-picture : http://i.imgur.com/LErjwv2.png
	*playerAchieve8
	-"Have 400 players.
	-unlocks at 400 player
	-named The best team
	-picture : http://i.imgur.com/fghLz8P.png
	*playerAllTimeAchieve1
	-"Get <b>1,000,000,000,000</b> code with just your players."
	-unlocks at 100000000000 playerWritten
	-named Play on
	-picture : http://i.imgur.com/BOiRUjn.png
	*playerAllTimeAchieve3
	-"Get <b>1,000,000,000,000,000</b> code with just your players."
	-unlocks at 100000000000000 playerWritten
	-named Play Day
	-picture : http://i.imgur.com/sUdjmIQ.png
	*playerAllTimeAchieve2
	-"Get <b>1 exa</b> code with just your players."
	-unlocks at 100000000000000000 playerWritten
	-named Play like there's no tomorrow
	-picture : http://i.imgur.com/fghLz8P.png

	*levelAchieve1
	-"Have 1 level.
	-unlocks at 1 level
	-named The Tutorial
	-picture : http://i.imgur.com/XoJpr1j.png
	*levelAchieve2
	-"Have 10 levels.
	-unlocks at 10 level
	-named The first world
	-picture : http://i.imgur.com/ekkhMyg.png
	*levelAchieve3
	-"Have 40 levels.
	-unlocks at 40 level
	-named The differently-themed levels
	-picture : http://i.imgur.com/AL9i7gY.png
	*levelAchieve4
	-"Have 100 levels.
	-unlocks at 100 level
	-named All the worlds
	-picture : http://i.imgur.com/xUvpwWs.png
	*levelAchieve5
	-"Have 150 levels.
	-unlocks at 150 level
	-named The boss levels
	-picture : http://i.imgur.com/En42hhm.png
	*levelAchieve6
	-"Have 200 levels.
	-unlocks at 200 level
	-named The bonus levels
	-picture : http://i.imgur.com/kpTIoKo.png
	*levelAchieve7
	-"Have 300 levels.
	-unlocks at 300 level
	-named The ultimate levels
	-picture : http://i.imgur.com/QU0nvGx.png
	*levelAchieve8
	-"Have 400 levels.
	-unlocks at 400 level
	-named The super ultimate levels
	-picture : http://i.imgur.com/tcHgenb.png
	*levelAllTimeAchieve1
	-"Get <b>10,000,000,000,000</b> code with just your levels."
	-unlocks at 1000000000000 levelWritten
	-named Leveling Up
	-picture : http://i.imgur.com/XoJpr1j.png
	*levelAllTimeAchieve3
	-"Get <b>10,000,000,000,000,000</b> code with just your levels."
	-unlocks at 1000000000000000 levelWritten
	-named Completely Level
	-picture : http://i.imgur.com/En42hhm.png
	*levelAllTimeAchieve2
	-"Get <b>10 exa</b> code with just your levels."
	-unlocks at 1000000000000000000 levelWritten
	-named Max level
	-picture : http://i.imgur.com/tcHgenb.png

	*gameAchieve1
	-"Have 1 game."
	-unlocks at 1 game
	-named The First Attempt
	-picture : http://i.imgur.com/g1FeDYT.png
	*gameAchieve2
	-"Have 10 games."
	-unlocks at 10 game
	-named Scrub Developer
	-picture : http://i.imgur.com/17MMlJo.png
	*gameAchieve3
	-"Have 40 games."
	-unlocks at 40 game
	-named Newbie developer
	-picture : http://i.imgur.com/GtnzjUk.png
	*gameAchieve4
	-"Have 100 games."
	-unlocks at 100 game
	-named Good Developer
	-picture : http://i.imgur.com/ScAuqAP.png
	*gameAchieve5
	-"Have 150 games."
	-unlocks at 150 game
	-named Big Developer
	-picture : http://i.imgur.com/uPWpPuL.png
	*gameAchieve6
	-"Have 200 games."
	-unlocks at 200 game
	-named Epic Developer
	-picture : http://i.imgur.com/UpalcvO.png
	*gameAchieve7
	-"Have 300 games."
	-unlocks at 300 game
	-named World-known developer
	-picture : http://i.imgur.com/GHNj9oQ.png
	*gameAchieve8
	-"Have 400 games. <i>Isn't that the name of this idle game?</i>"
	-unlocks at 400 game
	-named Game Developer
	-picture : http://i.imgur.com/ybh1Owt.png

	*gameAllTimeAchieve1
	-"Get <b>100,000,000,000,000</b> code with just your games."
	-unlocks at 10000000000000 gameWritten
	-named Casual Gamer
	-picture : http://i.imgur.com/g1FeDYT.png
	*gameAllTimeAchieve3
	-"Get <b>100,000,000,000,000,000</b> code with just your games."
	-unlocks at 10000000000000000 gameWritten
	-named Gamer
	-picture : http://i.imgur.com/uPWpPuL.png
	*gameAllTimeAchieve2
	-"Get <b>100 exa</b> code with just your games."
	-unlocks at 10000000000000000000 gameWritten
	-named Hardcore Gamer
	-picture : http://i.imgur.com/ybh1Owt.png

	*fanbaseAchieve1
	-"Have 1 fanbase."
	-unlocks at 1 fanbase
	-named Tiny community
	-picture : http://i.imgur.com/LIK7AJC.png
	*fanbaseAchieve2
	-"Have 10 fanbases. <br> <i>Sadly, not the developing as in developing your game.</i>"
	-unlocks at 10 fanbase
	-named Developing community
	-picture : http://i.imgur.com/KUjPpzg.png
	*fanbaseAchieve3
	-"Have 40 fanbases."
	-unlocks at 40 fanbase
	-named Growing community
	-picture : http://i.imgur.com/S8eQa4n.png
	*fanbaseAchieve4
	-"Have 100 fanbases."
	-unlocks at 100 fanbase
	-named Thriving community
	-picture : http://i.imgur.com/2GjucxV.png
	*fanbaseAchieve5
	-"Have 150 fanbases."
	-unlocks at 150 fanbase
	-named Internet-famous community
	-picture : http://i.imgur.com/TcWWOrJ.png
	*fanbaseAchieve6
	-"Have 200 fanbases. <br> <i>The fanbases of your games combined now have more people than the MLP fanbase!"
	-unlocks at 200 fanbase
	-named Friendship is magic
	-picture : http://i.imgur.com/utALJmr.png
	*fanbaseAchieve7
	-"Have 300 fanbases. <br> <i>This time, it is the developing as in developing your game."
	-unlocks at 300 fanbase
	-named Developing community
	-picture : http://i.imgur.com/cQnJdTp.png
	*fanbaseAchieve8
	-"Have 400 fanbases."
	-unlocks at 400 fanbase
	-named Epic Community
	-picture : http://i.imgur.com/jmJWslm.png
	*fanbaseAllTimeAchieve1
	-"Get <b>1,000,000,000,000,000</b> code with just your fanbases."
	-unlocks at 100000000000000 fanbaseWritten
	-named Attack of the fanbases
	-picture : http://i.imgur.com/LIK7AJC.png
	*fanbaseAllTimeAchieve3
	-"Get <b>1 exa</b> code with just your fanbases."
	-unlocks at 1000000000000000000 fanbaseWritten
	-named Fanbase helpers
	-picture : http://i.imgur.com/TcWWOrJ.png
	*fanbaseAllTimeAchieve2
	-"Get <b>1 zetta</b> code with just your games."
	-unlocks at 1000000000000000000000 fanbaseWritten
	-named Number one fanbase
	-picture : http://i.imgur.com/jmJWslm.png

	*forumAchieve1
	-"Have 1 forum."
	-unlocks at 1 forum
	-named The First Discussion
	-picture : http://i.imgur.com/HnWCXzQ.png
	*forumAchieve2
	-"Have 10 forums. <br> <i>Your post is a break-rules. If that post five times, a perma-ban!</i>"
	-unlocks at 10 forum
	-named A break-rules
	-picture : http://i.imgur.com/UiiqBJ8.png
	*forumAchieve3
	-"Have 40 forums."
	-unlocks at 40 forum
	-named Forumal
	-picture : http://i.imgur.com/V1dhW1T.png
	*forumAchieve4
	-"Have 100 forums."
	-unlocks at 100 forum
	-named Message City
	-picture : http://i.imgur.com/hi1yTYU.png
	*forumAchieve5
	-"Have 150 forums."
	-unlocks at 150 forum
	-named Message Country
	-picture : http://i.imgur.com/qBGPjMH.png
	*forumAchieve6
	-"Have 200 forums. <br> "
	-unlocks at 200 forum
	-named Message World
	-picture : http://i.imgur.com/OBhliau.png
	*forumAchieve7
	-"Have 300 forums. <br> "
	-unlocks at 300 forum
	-named This isn't even my final forum
	-picture : http://i.imgur.com/tUqysKk.png
	*forumAchieve8
	-"Have 400 forums."
	-unlocks at 400 forum
	-named This is my true forum
	-picture : http://i.imgur.com/QHsVu0q.png
	*forumAllTimeAchieve1
	-"Get <b>10,000,000,000,000,000</b> code with just your forums."
	-unlocks at 1000000000000000 forumWritten
	-named Discussing
	-picture : http://i.imgur.com/HnWCXzQ.png
	*forumAllTimeAchieve3
	-"Get <b>10 exa</b> code with just your forums."
	-unlocks at 10000000000000000000 forumWritten
	-named The Great Discussion
	-picture : http://i.imgur.com/qBGPjMH.png
	*forumAllTimeAchieve2
	-"Get <b>10 zetta</b> code with just your forum."
	-unlocks at 10000000000000000000000 forumWritten
	-named The Infinite Discussion
	-picture : http://i.imgur.com/QHsVu0q.png

	*advertiseAchieve1
	-"Have 1 advertisement."
	-unlocks at 1 advertise
	-named Advertising
	-picture : http://i.imgur.com/QcKrzxp.png
	*advertiseAchieve2
	-"Have 10 advertisements. <br> <i></i>"
	-unlocks at 10 advertise
	-named Advertse effect
	-picture : http://i.imgur.com/kSJsiPU.png
	*advertiseAchieve3
	-"Have 40 advertisements."
	-unlocks at 40 advertise
	-named On Air
	-picture : http://i.imgur.com/gKsULeh.png
	*advertiseAchieve4
	-"Have 100 advertisements."
	-unlocks at 100 advertise
	-named ADding Up
	-picture : http://i.imgur.com/13TklwI.png
	*advertiseAchieve5
	-"Have 150 advertisements."
	-unlocks at 150 advertise
	-named No side effects
	-picture : http://i.imgur.com/WRL856n.png
	*advertiseAchieve6
	-"Have 200 advertisements. <br> "
	-unlocks at 200 advertise
	-named Kills 99.9% of boredom
	-picture : http://i.imgur.com/TdEJyuY.png
	*advertiseAchieve7
	-"Have 300 advertisements."
	-unlocks at 300 advertise
	-named Ad it's here
	-picture : http://i.imgur.com/jCPE3Tm.png
	*advertiseAchieve8
	-"Have 400 advertisements."
	-unlocks at 400 advertise
	-named "Gaming. Reinvented."
	-picture : http://i.imgur.com/zX6w9t9.png
	*advertiseAllTimeAchieve1
	-"Get <b>100,000,000,000,000,000</b> code with just your advertisements."
	-unlocks at 10000000000000000 advertiseWritten
	-named We'll be back after the Break
	-picture : http://i.imgur.com/QcKrzxp.png
	*advertiseAllTimeAchieve3
	-"Get <b>100 exa</b> code with just your advertisements."
	-unlocks at 100000000000000000000 advertiseWritten
	-named Ads and ads and ads
	-picture : http://i.imgur.com/WRL856n.png
	*advertiseAllTimeAchieve2
	-"Get <b>100 zetta</b> code with just your advertisements."
	-unlocks at 100000000000000000000000 advertiseWritten
	-named Advertising monopoly
	-picture : http://i.imgur.com/zX6w9t9.png

	*studioAchieve1
	-"Have 1 game studio."
	-unlocks at 1 studio
	-named Studio Founder
	-picture : http://i.imgur.com/YdPquWG.png
	*studioAchieve2
	-"Have 10 game studios. <br> <i></i>"
	-unlocks at 10 studio
	-named Home of the Games
	-picture : http://i.imgur.com/CUnhuhS.png
	*studioAchieve3
	-"Have 40 game studios."
	-unlocks at 40 studio
	-named At your local studio
	-picture : http://i.imgur.com/gHbv5N6.png
	*studioAchieve4
	-"Have 100 game studios."
	-unlocks at 100 studio
	-named Growing code empire
	-picture : http://i.imgur.com/ZsNefex.png
	*studioAchieve5
	-"Have 150 game studios."
	-unlocks at 150 studio
	-named (insert company name here) world
	-picture : http://i.imgur.com/jti47F2.png
	*studioAchieve6
	-"Have 200 game studios. <br> "
	-unlocks at 200 studio
	-named Coder's link
	-picture : http://i.imgur.com/zHCri6W.png
	*studioAchieve7
	-"Have 300 game studios."
	-unlocks at 300 studio
	-named Massive company
	-picture : http://i.imgur.com/49zevUi.png
	*studioAchieve8
	-"Have 400 game studios."
	-unlocks at 400 studio
	-named Game studio conquest
	-picture : http://i.imgur.com/55x56S1.png
	*studioAllTimeAchieve1
	-"Get <b>1 exa</b> code with just your game studios."
	-unlocks at 100000000000000000 studioWritten
	-named Serious Business
	-picture : http://i.imgur.com/YdPquWG.png
	*studioAllTimeAchieve3
	-"Get <b>1 zetta</b> code with just your game studios."
	-unlocks at 1000000000000000000000 studioWritten
	-named Home of the Coders
	-picture : http://i.imgur.com/jti47F2.png
	*studioAllTimeAchieve2
	-"Get <b>1 yotta</b> code with just your game studios."
	-unlocks at 1000000000000000000000000 studioWritten
	-named Never-dying studios
	-picture : http://i.imgur.com/55x56S1.png

	*magicAchieve1
	-"Have 1 magic code writer."
	-unlocks at 1 magic
	-named The beginning of a Magical Adventure
	-picture : http://i.imgur.com/SF8q1Sj.png
	*magicAchieve2
	-"Have 10 magic code writers. <br> <i></i>"
	-unlocks at 10 magic
	-named The Gathering
	-picture : http://i.imgur.com/NW5tqkO.png
	*magicAchieve3
	-"Have 40 magic code writers."
	-unlocks at 40 magic
	-named The Magician
	-picture : http://i.imgur.com/T5AI2Zz.png
	*magicAchieve4
	-"Have 100 magic code writers."
	-unlocks at 100 magic
	-named Installation Wizard
	-picture : http://i.imgur.com/ThDRhz6.png
	*magicAchieve5
	-"Have 150 magic code writers."
	-unlocks at 150 magic
	-named There is such thing as magic
	-picture : http://i.imgur.com/DtnrN27.png
	*magicAchieve6
	-"Have 200 magic code writers. <br> "
	-unlocks at 200 magic
	-named Dark mage
	-picture : http://i.imgur.com/SRP88yP.png
	*magicAchieve7
	-"Have 300 magic code writers."
	-unlocks at 300 magic
	-named It just happened like magic
	-picture : http://i.imgur.com/YBnOnX6.png
	*magicAchieve8
	-"Have 400 magic code writers."
	-unlocks at 400 magic
	-named Lord of the wizards
	-picture : http://i.imgur.com/9Pjfygq.png
	*magicAllTimeAchieve1
	-"Get <b>10 exa</b> code with just your magic code writers."
	-unlocks at 1000000000000000000 magicWritten
	-named Magic Tricked
	-picture : http://i.imgur.com/SF8q1Sj.png
	*magicAllTimeAchieve3
	-"Get <b>10 zetta</b> code with just your magic code writers."
	-unlocks at 10000000000000000000000 magicWritten
	-named Sunny (magic) spells
	-picture : http://i.imgur.com/DtnrN27.png
	*magicAllTimeAchieve2
	-"Get <b>10 yotta</b> code with just your magic code writers."
	-unlocks at 10000000000000000000000000 magicWritten
	-named Dark magic Storm
	-picture : http://i.imgur.com/9Pjfygq.png

	*gameSeriesAchieve1
	-"Have 1 game series."
	-unlocks at 1 gameSeries
	-named Start of a franchise
	-picture : http://i.imgur.com/lzFeUVJ.png
	*gameSeriesAchieve2
	-"Have 10 game series. <br> <i></i>"
	-unlocks at 10 gameSeries
	-named The Sequels
	-picture : http://i.imgur.com/jScQ4sf.png
	*gameSeriesAchieve3
	-"Have 40 game series."
	-unlocks at 40 gameSeries
	-named The Storyline
	-picture : http://i.imgur.com/ZgWfkU6.png
	*gameSeriesAchieve4
	-"Have 100 game series."
	-unlocks at 100 gameSeries
	-named Series Developer
	-picture : http://i.imgur.com/sm7iWg2.png
	*gameSeriesAchieve5
	-"Have 150 game series."
	-unlocks at 150 gameSeries
	-named Great Series Developer
	-picture : http://i.imgur.com/EVPKgON.png
	*gameSeriesAchieve6
	-"Have 200 game series. <br> "
	-unlocks at 200 gameSeries
	-named Epic Series Developer
	-picture : http://i.imgur.com/zA3N8gJ.png
	*gameSeriesAchieve7
	-"Have 300 game series."
	-unlocks at 300 gameSeries
	-named Master Series Developer
	-picture : http://i.imgur.com/A034CIe.png
	*gameSeriesAchieve8
	-"Have 400 game series."
	-unlocks at 400 gameSeries
	-named Ultimate Series Developer
	-picture : http://i.imgur.com/bK4p9By.png
	*gameSeriesAllTimeAchieve1
	-"Get <b>100 exa</b> code with just your game series."
	-unlocks at 10000000000000000000 gameSeriesWritten
	-named Series Business
	-picture : http://i.imgur.com/lzFeUVJ.png
	*gameSeriesAllTimeAchieve3
	-"Get <b>100 zetta</b> code with just your game series."
	-unlocks at 100000000000000000000000 gameSeriesWritten
	-named Never-ending Series
	-picture : http://i.imgur.com/EVPKgON.png
	*gameSeriesAllTimeAchieve2
	-"Get <b>100 yotta</b> code with just your game series."
	-unlocks at 100000000000000000000000000 gameSeriesWritten
	-named Seriesly
	-picture : http://i.imgur.com/bK4p9By.png

	*maganiumGeneratorAchieve1
	-"Have 1 ultra-magic generator."
	-unlocks at 1 maganiumGenerator
	-named It begins
	-picture : http://i.imgur.com/AxHgS0u.png
	*maganiumGeneratorAchieve2
	-"Have 10 ultra-magic generator. <br> <i></i>"
	-unlocks at 10 maganiumGenerator
	-named Ultra-power
	-picture : http://i.imgur.com/vObmzb9.png
	*maganiumGeneratorAchieve3
	-"Have 40 ultra-magic generator."
	-unlocks at 40 maganiumGenerator
	-named Next Generation
	-picture : http://i.imgur.com/bgVAlDe.png
	*maganiumGeneratorAchieve4
	-"Have 100 ultra-magic generator."
	-unlocks at 100 maganiumGenerator
	-named Great Generator
	-picture : http://i.imgur.com/zWgZrDB.png
	*maganiumGeneratorAchieve5
	-"Have 150 ultra-magic generator."
	-unlocks at 150 maganiumGenerator
	-named Ultra-magic expert
	-picture : http://i.imgur.com/yKsqeSv.png
	*maganiumGeneratorAchieve6
	-"Have 200 ultra-magic generator. <br> "
	-unlocks at 200 maganiumGenerator
	-named Ultra-magic fanatic
	-picture : http://i.imgur.com/fGp62fa.png
	*maganiumGeneratorAchieve7
	-"Have 300 ultra-magic generator."
	-unlocks at 300 maganiumGenerator
	-named Ultra-mage
	-picture : http://i.imgur.com/Bu1Rdh8.png
	*maganiumGeneratorAchieve8
	-"Have 400 ultra-magic generator."
	-unlocks at 400 maganiumGenerator
	-named Ultra-magic overlord
	-picture : http://i.imgur.com/Z9yolDc.png
	*maganiumGeneratorAllTimeAchieve1
	-"Get <b>1 zetta</b> code with just your ultra-magic generator."
	-unlocks at 100000000000000000000 maganiumWritten
	-named Learning to use Ultra-Magic
	-picture : http://i.imgur.com/AxHgS0u.png
	*maganiumGeneratorAllTimeAchieve3
	-"Get <b>1 yotta</b> code with just your ultra-magic generator."
	-unlocks at 1000000000000000000000000 maganiumWritten
	-named Unstoppable
	-picture : http://i.imgur.com/yKsqeSv.png
	*maganiumGeneratorAllTimeAchieve2
	-"Get <b>1 xatta (octillion)</b> code with just your ultra-magic generator."
	-unlocks at 1000000000000000000000000000 maganiumWritten
	-named Dominating Power Source
	-picture : http://i.imgur.com/Z9yolDc.png

	*popularYoutuberAchieve1
	-"Have 1 popular YouTuber."
	-unlocks at 1 popularYoutuber
	-named Broadcast Yourself
	-picture : http://i.imgur.com/X4BEZG2.png
	*popularYoutuberAchieve2
	-"Have 10 popular YouTubers. <br> <i></i>"
	-unlocks at 10 popularYoutuber
	-named Video Series
	-picture : http://i.imgur.com/5QAnoob.png
	*popularYoutuberAchieve3
	-"Have 40 popular YouTubers."
	-unlocks at 40 popularYoutuber
	-named Entire Playthrough
	-picture : http://i.imgur.com/Pf7LHrb.png
	*popularYoutuberAchieve4
	-"Have 100 popular YouTubers."
	-unlocks at 100 popularYoutuber
	-named Team of YouTubers
	-picture : http://i.imgur.com/Y8hjea1.png
	*popularYoutuberAchieve5
	-"Have 150 popular YouTubers."
	-unlocks at 150 popularYoutuber
	-named The Extremely Popular
	-picture : http://i.imgur.com/VnArJS1.png
	*popularYoutuberAchieve6
	-"Have 200 popular YouTubers. <br> "
	-unlocks at 200 popularYoutuber
	-named The Experts
	-picture : http://i.imgur.com/JKeVsW3.png
	*popularYoutuberAchieve7
	-"Have 300 popular YouTubers."
	-unlocks at 300 popularYoutuber
	-named The Masters
	-picture : http://i.imgur.com/yISj9l7.png
	*popularYoutuberAchieve8
	-"Have 400 popular YouTubers."
	-unlocks at 400 popularYoutuber
	-named xXmlgpro420blazeithashswagyoloXx
	-picture : http://i.imgur.com/KqwNm2V.png
	*popularYoutuberAllTimeAchieve1
	-"Get <b>10 zetta</b> code with just your popular YouTubers."
	-unlocks at 1000000000000000000000 popularYoutuberWritten
	-named Livestreaming
	-picture : http://i.imgur.com/X4BEZG2.png
	*popularYoutuberAllTimeAchieve3
	-"Get <b>10 yotta</b> code with just your popular YouTubers."
	-unlocks at 10000000000000000000000000 popularYoutuberWritten
	-named Popularity Boost
	-picture : http://i.imgur.com/VnArJS1.png
	*popularYoutuberAllTimeAchieve2
	-"Get <b>10 xatta (octillion)</b> code with just your popular YouTubers."
	-unlocks at 10000000000000000000000000000 popularYoutuberWritten
	-named YouTube takeover
	-picture : http://i.imgur.com/KqwNm2V.png

	*finalityAchieve1
	-"Have 1 finalities."
	-unlocks at 1 finality
	-named It's a secret to everyone
	-picture : http://i.imgur.com/VIHqFJh.png
	*finalityAchieve2
	-"Have 10 finalities. <br> <i></i>"
	-unlocks at 10 finality
	-named The Beginning of the End
	-picture : http://i.imgur.com/AUPVLJ0.png
	*finalityAchieve3
	-"Have 40 finalities."
	-unlocks at 40 finality
	-named In control
	-picture : http://i.imgur.com/7ImY6oX.png
	*finalityAchieve4
	-"Have 100 finalities."
	-unlocks at 100 finality
	-named Finalising
	-picture : http://i.imgur.com/d6k1tn0.png
	*finalityAchieve5
	-"Have 150 finalities."
	-unlocks at 150 finality
	-named Top Secret
	-picture : http://i.imgur.com/qRNLxjT.png
	*finalityAchieve6
	-"Have 200 finalities. <br> "
	-unlocks at 200 finality
	-named Secrets of the Universe
	-picture : http://i.imgur.com/34YMXGK.png
	*finalityAchieve7
	-"Have 300 finalities."
	-unlocks at 300 finality
	-named The Final Countdown
	-picture : http://i.imgur.com/ComWP0M.png
	*finalityAchieve8
	-"Have 400 finalities."
	-unlocks at 400 finality
	-named The Illuminati
	-picture : http://i.imgur.com/ZQRn5AC.png
	*finalityAllTimeAchieve1
	-"Get <b>100 zetta</b> code with just your finalities."
	-unlocks at 10000000000000000000000 finalityWritten
	-named Taking Control
	-picture : http://i.imgur.com/VIHqFJh.png
	*finalityAllTimeAchieve3
	-"Get <b>100 yotta</b> code with just your finalities."
	-unlocks at 100000000000000000000000000 finalityWritten
	-named Major Power
	-picture : http://i.imgur.com/qRNLxjT.png
	*finalityAllTimeAchieve2
	-"Get <b>100 xatta (octillion)</b> code with just your finalities."
	-unlocks at 100000000000000000000000000000 finalityWritten
	-named Global Domination
	-picture : http://i.imgur.com/ZQRn5AC.png

	*bonusAchieve1
	-"have <b>1</b> bonus."
	-unlocks at 1 bonus
	-named Bonus Points
	-picture : http://i.imgur.com/UD0jYCm.png
	*bonusAchieve2
	-"have <b>10</b> bonuses."
	-unlocks at 10 bonus
	-named Starring...
	-picture : http://i.imgur.com/ifdnM8f.png
	*bonusAchieve3
	-"have <b>40</b> bonuses."
	-unlocks at 40 bonus
	-named Lucky Star
	-picture : http://i.imgur.com/fXzn7F0.png
	*bonusAchieve4
	-"have <b>100</b> bonuses."
	-unlocks at 100 bonus
	-named Gold Stars
	-picture : http://i.imgur.com/5XtJfmA.png
	*bonusAchieve5
	-"have <b>150</b> bonuses."
	-unlocks at 150 bonus
	-named Rising Star
	-picture : http://i.imgur.com/LIVHPTp.png
	*bonusAchieve6
	-"have <b>200</b> bonuses."
	-unlocks at 200 bonus
	-named Big Star
	-picture : http://i.imgur.com/P17AJAF.png
	*bonusAchieve7
	-"have <b>300</b> bonuses."
	-unlocks at 300 bonus
	-named Starshine
	-picture : http://i.imgur.com/Tpvp49E.png
	*bonusAchieve8
	-"have <b>400</b> bonuses."
	-unlocks at 400 bonus
	-named Megabonus
	-picture : http://i.imgur.com/Wj8svTe.png
	*bonusAchieve9
	-"have <b>500</b> bonuses."
	-unlocks at 500 bonus
	-named Fault in our Stars
	-picture : http://i.imgur.com/xHBZR5z.png
	*bonusAchieve10
	-"have <b>600</b> bonuses."
	-unlocks at 600 bonus
	-named Gigabonus
	-picture : http://i.imgur.com/yTfGtkd.png
	*bonusAchieve11
	-"have <b>700</b> bonuses."
	-unlocks at 700 bonus
	-named Night Sky
	-picture : http://i.imgur.com/yTfGtkd.png
	*bonusAchieve12
	-"have <b>800</b> bonuses."
	-unlocks at 800 bonus
	-named Terabonus
	-picture : http://i.imgur.com/aIEwwOR.png
	*bonusAchieve13
	-"have <b>900</b> bonuses."
	-unlocks at 900 bonus
	-named Shooting Star
	-picture : http://i.imgur.com/aIEwwOR.png
	*bonusAchieve14
	-"have <b>1,000</b> bonuses."
	-unlocks at 1000 bonus
	-named Star of the North
	-picture : http://i.imgur.com/CR37oFU.png
	*bonusAchieve15
	-"have <b>1,200</b> bonuses."
	-unlocks at 1200 bonus
	-named Petabonus
	-picture : http://i.imgur.com/CR37oFU.png
	*bonusAchieve16
	-"have <b>1,400</b> bonuses. <br><i>Right before crossing the finish line.</i>"
	-unlocks at 1400 bonus
	-named Red shelled, starred and bullet billed
	-picture : http://i.imgur.com/1LfYdDi.png
	*bonusAchieve17
	-"have <b>1,600</b> bonuses."
	-unlocks at 1600 bonus
	-named Star Spirits
	-picture : http://i.imgur.com/1LfYdDi.png
	*bonusAchieve18
	-"have <b>1,800</b> bonuses."
	-unlocks at 1800 bonus
	-named Exabonus
	-picture : http://i.imgur.com/ArfERiP.png
	*bonusAchieve19
	-"have <b>2,000</b> bonuses."
	-unlocks at 2000 bonus
	-named May the stars shine down upon you
	-picture : http://i.imgur.com/ArfERiP.png


	*everythingAchieve1
	-"Have <b>one</b> of every building, up to studios.<br><i>Isn't that an achievement in Cookie Clicker? Such a copier...</i>
	-unlocks at 1 codeWriter, 1 object, 1 enemy, 1 player, 1 level, 1 game, 1 fanbase, 1 forum, 1 advertise, 1 studio
	-named One With Everything
	-picture : http://i.imgur.com/8Tk44xT.png
	*everythingAchieve2
	-"Have <b>10</b> of every building, up to studios.<br><i></i>
	-unlocks at 10 codeWriter, 10 object, 10 enemy, 10 player, 10 level, 10 game, 10 fanbase, 10 forum, 10 advertise, 10 studio
	-named In Tens
	-picture : http://i.imgur.com/R2xhSvR.png
	*everythingAchieve3
	-"Have <b>40</b> of every building, up to magic code writers.<br><i></i>
	-unlocks at 40 codeWriter, 40 object, 40 enemy, 40 player, 40 level, 40 game, 40 fanbase, 40 forum, 40 advertise, 40 studio, 40 magic
	-named Building Up
	-picture : http://i.imgur.com/LXayqUf.png
	*everythingAchieve4
	-"Have <b>100</b> of every building, up to magic point converters.<br><i></i>
	-unlocks at 100 codeWriter, 100 object, 100 enemy, 100 player, 100 level, 100 game, 100 fanbase, 100 forum, 100 advertise, 100 studio, 100 magic, 100 gameSeries, 100 maganiumGenerator, 100 magicPointBuilding
	-named The Centenary Coders
	-picture : http://i.imgur.com/eLSZsdD.png
	*everythingAchieve5
	-"Have <b>150</b> of every building, up to popular YouTubers.<br><i></i>
	-unlocks at 150 codeWriter, 150 object, 150 enemy, 150 player, 150 level, 150 game, 150 fanbase, 150 forum, 150 advertise, 150 studio, 150 magic, 150 gameSeries, 150 maganiumGenerator, 150 magicPointBuilding, 150 popularYoutuber
	-named Collection
	-picture : http://i.imgur.com/N6IIVMr.png
	*everythingAchieve6
	-"Have <b>200</b> of every building, up to finalities.<br><i></i>
	-unlocks at 200 codeWriter, 200 object, 200 enemy, 200 player, 200 level, 200 game, 200 fanbase, 200 forum, 200 advertise, 200 studio, 200 magic, 200 gameSeries, 200 maganiumGenerator, 200 magicPointBuilding, 200 popularYoutuber, 200 finality
	-named Large collection
	-picture : http://i.imgur.com/ygzYeg4.png
	*everythingAchieve7
	-"Have <b>300</b> of every building, up to finalities.<br><i></i>
	-unlocks at 300 codeWriter, 300 object, 300 enemy, 300 player, 300 level, 300 game, 300 fanbase, 300 forum, 300 advertise, 300 studio, 300 magic, 300 gameSeries, 300 maganiumGenerator, 300 magicPointBuilding, 300 popularYoutuber, 300 finality
	-named Epic Collection
	-picture : http://i.imgur.com/CML1yuO.png
	*everythingAchieve8
	-"Have <b>400</b> of every building, up to finalities.<br><i></i>
	-unlocks at 400 codeWriter, 400 object, 400 enemy, 400 player, 400 level, 400 game, 400 fanbase, 400 forum, 400 advertise, 400 studio, 400 magic, 400 gameSeries, 400 maganiumGenerator, 400 magicPointBuilding, 400 popularYoutuber, 400 finality
	-named Never-Ending Collection
	-picture : http://i.imgur.com/PxFf9nF.png
	*everythingAchieve9
	-"Have <b>500</b> of every building, up to finalities.<br><i></i>
	-unlocks at 500 codeWriter, 500 object, 500 enemy, 500 player, 500 level, 500 game, 500 fanbase, 500 forum, 500 advertise, 500 studio, 500 magic, 500 gameSeries, 500 maganiumGenerator, 500 magicPointBuilding, 500 popularYoutuber, 500 finality
	-named Ascended Collection
	-picture : http://i.imgur.com/agtoDM0.png

	*buildingAchieve1
	-"Have <b>100</b> buildings.<br><i></i>
	-unlocks at 100 buildings
	-named Learning to Build
	-picture : http://i.imgur.com/8Tk44xT.png
	*buildingAchieve2
	-"Have <b>300</b> buildings.<br><i></i>
	-unlocks at 300 buildings
	-named Bob the Builder
	-picture : http://i.imgur.com/R2xhSvR.png
	*buildingAchieve3
	-"Have <b>750</b> buildings.<br><i></i>
	-unlocks at 750 buildings
	-named Building Worker
	-picture : http://i.imgur.com/aufjvya.png
	*buildingAchieve4
	-"Have <b>1,500</b> buildings.<br><i></i>
	-unlocks at 1500 buildings
	-named Building Engineer
	-picture : http://i.imgur.com/LXayqUf.png
	*buildingAchieve5
	-"Have <b>2,500</b> buildings.<br><i></i>
	-unlocks at 2500 buildings
	-named Building Overseer
	-picture : http://i.imgur.com/6gVWBRU.png
	*buildingAchieve6
	-"Have <b>3,500</b> buildings.<br><i></i>
	-unlocks at 3500 buildings
	-named Building Architect
	-picture : http://i.imgur.com/eLSZsdD.png
	*buildingAchieve7
	-"Have <b>5,000</b> buildings.<br><i></i>
	-unlocks at 5000 buildings
	-named Building Manager
	-picture : http://i.imgur.com/N6IIVMr.png
	*buildingAchieve8
	-"Have <b>7,000</b> buildings.<br><i></i>
	-unlocks at 7000 buildings
	-named Building Master
	-picture : http://i.imgur.com/ygzYeg4.png
	*buildingAchieve9
	-"Have <b>9,001</b> buildings.<br><i></i>
	-unlocks at 9001 buildings
	-named It's OVAR 9000!!1!1!!1! LE MAY MAYS xD!1!
	-picture : http://i.imgur.com/Z7ob1lw.png
	*buildingAchieve10
	-"Have <b>12,000</b> buildings.<br><i></i>
	-unlocks at 12000 buildings
	-named Building King
	-picture : http://i.imgur.com/CML1yuO.png
	*buildingAchieve11
	-"Have <b>16,000</b> buildings.<br><i></i>
	-unlocks at 16000 buildings
	-named Building Overlord
	-picture : http://i.imgur.com/aAIbpDR.png
	*buildingAchieve12
	-"Have <b>20,000</b> buildings.<br><i></i>
	-unlocks at 20000 buildings
	-named CantStopBuildnugget
	-picture : http://i.imgur.com/PxFf9nF.png
	*buildingAchieve13
	-"Have <b>24,000</b> buildings.<br><i></i>
	-unlocks at 20000 buildings
	-named Building God
	-picture : http://i.imgur.com/j3tNsPW.png
	*researchAchieve1
	-"Build a research lab.
	-unlocks at 1 research
	-named Enhancing
	-picture : http://i.imgur.com/GS3JNtZ.png
	*researchAchieve2
	-"Unlock five upgrades from research. <br><i>Our game studios now have the same technological level as an antimatter condenser!</i>
	-unlocks at 10000 researchTime
	-named We Have The Technology
	-picture : http://i.imgur.com/L2SdPAH.png
	*researchAchieve3
	-"Buy the upgrade Unstable Game Studios.<br><i>Unstable Game Studios. Executive Producer: fireore</i>
	-named Unstable Game Studios
	-picture : http://i.imgur.com/3wQWoDT.png
	*researchAchieve4
	-"Have your game studios reach maximum instability.<br><i>A hard reset will happen in the next five hours. (just kidding)</i>
	-named Maximum instability
	-picture : http://i.imgur.com/v1YqEuF.png
	*researchAchieve5
	-"Restore stability in your game studios.<br><i>Thanks, charge alters!</i>
	-named Restoring Stability
	-picture : http://i.imgur.com/VCF12TC.png
	*researchAchieve6
	-"Have <b>every</b> research upgrade.<br><i></i>
	-named Master of Technology
	-picture : http://i.imgur.com/oJsfL3G.png

	*breakthroughAchieve1
	-"Make <b>1</b> breakthrough.<br>
	-named Breaking through
	-unlocks at 1 breakthrough
	-picture : http://i.imgur.com/GS3JNtZ.png
	*breakthroughAchieve2
	-"Make <b>5</b> breakthroughs.<br>
	-named Technology boost
	-unlocks at 5 breakthrough
	-picture : http://i.imgur.com/GS3JNtZ.png
	*breakthroughAchieve3
	-"Make <b>15</b> breakthroughs.<br>
	-named Great discoveries
	-unlocks at 15 breakthrough
	-picture : http://i.imgur.com/GS3JNtZ.png
	*breakthroughAchieve4
	-"Make <b>30</b> breakthrougsh.<br>
	-named Massive breakthrough
	-unlocks at 30 breakthrough
	-picture : http://i.imgur.com/GS3JNtZ.png
	*breakthroughAchieve5
	-"Make <b>60</b> breakthroughs.<br>
	-named Master of Breakthroughs
	-unlocks at 60 breakthrough
	-picture : http://i.imgur.com/GS3JNtZ.png
	*breakthroughAchieve6
	-"Make <b>100</b> breakthroughs.<br>
	-named The Ultimate Breakthrough
	-unlocks at 100 breakthrough
	-picture : http://i.imgur.com/GS3JNtZ.png
	*breakthroughAchieve7
	-"Make <b>150</b> breakthroughs.<br>
	-named Lucker
	-unlocks at 150 breakthrough
	-picture : http://i.imgur.com/GS3JNtZ.png

	*ascendAchieve1
	-"Ascend for the first time."
	-named The First Ascension
	-unlocks at 1 lel
	-picture : http://i.imgur.com/m4x9kKH.png
	*ascendAchieve2
	-"Ascend for the 4th time."
	-named Ascending
	-unlocks at 1 lel2
	-picture : http://i.imgur.com/a60alv1.png
	*ascendAchieve3
	-"Ascend for the 7th time."
	-named Into The Sky
	-unlocks at 1 lel3
	-picture : http://i.imgur.com/3r3GIJo.png
	*ascendAchieve4
	-"Ascend for the 11th time."
	-named Great Ascension
	-unlocks at 1 lel4
	-picture : http://i.imgur.com/YLYb6NC.png
	*ascendAchieve5
	-"Ascend for the 16th time."
	-named Into Space
	-unlocks at 1 lel5
	-picture : http://i.imgur.com/4MwNcq7.png
	*ascendAchieve6
	-"Ascend for the 21st time."
	-named Extreme Ascension
	-unlocks at 1 lel6
	-picture : http://i.imgur.com/DULftRF.png
	*ascendAchieve7
	-"Ascend for the final time."
	-named The Final Ascension
	-unlocks at 1 lel7
	-picture : http://i.imgur.com/lioGdC4.png
	*ascendAchieve8
	-"Become an official Game Developer tryhard."
	-named The Prize
	-picture : http://i.imgur.com/ejDaFz2.png

	*iLied
	-"Find out that the eighth bonus upgrade actually does give a bonus."
	-named I LIED!
	-unlocks at 201 bonus
	-picture : http://i.imgur.com/1LeGwS1.png

	*noEffect
	-"Click on the golden box info upgrades.
	-named It doesn't do anything
	-picture : http://i.imgur.com/TkCSZup.png

	*fastMenAchieve
	-"Find every single FASTER MENNER reference in this game.
	-unlocks at 450 codeWriter, 64 studio
	-named FASTEST MENNEST!!!!
	-picture : http://i.imgur.com/JUqLcP2.png
