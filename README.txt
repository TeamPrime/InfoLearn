***************WELKOM*****************************
Dit is de repository voor de applicatie InfoLearn. Dit is een digitale leeromgeving voor de medewerkers van InfoSupport. Het is de bedoeling dat de applicatie ook geschikt gemaakt kan worden om bij andere bedrijven in te zetten.

Deze repository is gemaakt voor en door team Prime, studenten van de Hogeschool van Amsterdam (deeltijd Informatica en cursus "Software Engineering").
**************************************************

*************INSTALLATIE**************************
1. Installeer "GitHub for Windows"
	- Het bestand kun je vinden op de Google Drive \Mijn Schijf\GitHub\GitHubSetup.exe
2. Voeg de repository InfoLearn.git toe
	- Username: TeamPrime
	- Password: *****
3. Geef je naam op zodat we weten wie bepaalde veranderingen heeft toegevoegd
	- Naam: <Voornaam>
	- E-mail: <e-mailadres>
**************************************************

*************WIJZIGINGEN**************************
1. Open de Git Shell
2. Bestanden toevoegen
	>git push origin master
	# Pushes commits to your remote repository stored on GitHub
3. Bestanden ophalen
	>git fetch upstream
	# Fetches any new changes from the original repository
4. Bestanden ophalen en samenvoegen
	>git merge upstream/master
	# Merges any changes fetched into your working files
Zie bestand FETCH_PULL.txt voor meer details

******BRANCHES*********
Branches stellen je in staat om nieuwe code te schrijven en/of testen zonder risico voor het hoofd project.
5. Een nieuwe branch aanmaken
	>git branch mybranch
6. Branch actief maken
	>git checkout mybranch

Als je klaar bent met je branch en je wilt de nieuwe code samenvoegen met de master branch, dan gebruik je het commando merge
7. Maak de master branch actief
	>git checkout master
8. Jouw branch samenvoegen met de master branch
	>git merge mybranch
9. Jouw branch weggooien
	>git branch -d mybranch
Zie BRANCHES.txt voor meer details
************************