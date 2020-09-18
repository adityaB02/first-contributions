[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.svg)](https://github.com/firstcontributions/open-source-badges)
[<img align="right" width="150" src="assets/join-slack-team.png">](https://join.slack.com/t/firstcontributors/shared_invite/enQtNjkxNzQwNzA2MTMwLTVhMWJjNjg2ODRlNWZhNjIzYjgwNDIyZWYwZjhjYTQ4OTBjMWM0MmFhZDUxNzBiYzczMGNiYzcxNjkzZDZlMDM)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open Source Helpers](https://www.codetriage.com/roshanjossey/first-contributions/badges/users.svg)](https://www.codetriage.com/roshanjossey/first-contributions)


# Kontributet e Para


Është e vështirë. Është gjithmonë e vështirë hera e parë kur bën diçka. Sidomos kur bashkëpunon, të bësh gabime nuk është një ndjenjë e mirë. Ne duam ta thjeshtësojmë mënyrën se si kontribuesit e open-source mësojnë dhe kontribuojnë për herë të parë.
Leximi i artikujve & shikimi i tutorialve ndihmojnë, por ç'është më mirë se sa ta bësh këtë gjë në një vend praktike? Ky projekt synon të udhëzojë & të thjeshtësojë mënyrën se si fillestarët bëjnë kontributin e tyre të parë. Nëse dëshiron të bësh kontributin tënd të parë, ndiqi hapat më poshtë.

#### *Nëse ende nuk ndjehesh komod me command line, [këtu ke tutoriale që përdorin veglat e GUI]( #tutorials-using-other-tools )*

<img align="right" width="300" src="assets/fork.png" alt="fork this repository" />

Nëse nuk ke Git të instaluar në pajisjen tënde, [instaloje]( https://help.github.com/articles/set-up-git/).

## Bëje fork këtë repozitor

Për të bërë fork këtë repozitor kliko butonin fork në majë të kësaj faqeje. Kjo do të krijojë një kopje të ketij repozitori në llogarinë tënde.

## Klonoje këtë repozitor

<img align="right" width="300" src="assets/clone.png" alt="clone this repository" />

Tani klonoje në pajisjen tënde repozitorin që bëre fork. Shko te llogaria e GitHub, hap forked repository, kliko butonin Code dhe pastaj kliko ikonën *copy to clipboard*.

Hap terminalin dhe bëje run git komandën në vazhdim:

```
git clone "url që sapo ke kopjuar"
```
ku "url që sapo ke kopjuar" (pa thonjëzat) është url e këtij repozitori (repozitori që bëre fork). Shiko hapat e mëparshëm për të marrë url-në.

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

Për shembull:
```
git clone https://github.com/ky-je-ti/first-contributions.git
```
ku `ky-je-ti` është emri jot në GitHub. Këtu ti e kopjon përmbajtjen e repozitorit first-contributions në GitHub te kompjuteri jot.

## Krijo një degë (branch)

Ndryshoje lokacionin te repozitori në kompjuterin tënd (nëse nuk je në lokacionin e duhur):

```
cd first-contributions
```
Tani krijo një degë duke përdorur komandën `git checkout`:
```
git checkout -b <emri-i-degës-tënde>
```

Për shembull:
```
git checkout -b add-filan-fisteku
```
(Emri i degës nuk është e nevojshme të ketë fjalën *add* në të, por është e arsyeshme të përfshihet pasi që qëllimi i kësaj dege është të shtojë emrin tënd në një listë.)

## Bëji ndryshimet e nevojshme dhe bëji commit

Tani hap fajllin `Contributors.md` në një program për editim të tekstit dhe shto emrin tënd. Mos e shto në fillim ose në fund. Shtoje ku të duash në mes. Tani, ruaj fajllin.

<img align="right" width="450" src="assets/git-status.png" alt="git status" />


Nëse shkon te lokacioni i projektit dhe e ekzekuton komandën `git status`, do shohësh se ka ndryshime.


Shtoji këto ndryshime te dega që sapo krijove duke përdorur komandën `git add`:

```
git add Contributors.md
```

Tani bëji commit këto ndryshime duke përdorur komandën `git commit`:
```
git commit -m "Add <emri-jot> to Contributors list"
```
zëvendëso `<emri-jot>` me emrin tënd.

## Bëji push (shtyji) ndryshimet në GitHub

Bëji push ndryshimet duke përdorur komandën `git push`: 
```
git push origin <emri-i-degës-tënde>
```
zëvendëso `<emri-i-degës-tënde>` me emrin e degës që krijove më herët.

## Bëji ndryshimet submit për shqyrtim

Nëse shkon te repozitori jot në GitHub, do të shohësh një buton `Compare & pull request`. Klikoje.

<img style="float: right;" src="assets/compare-and-pull.png" alt="create a pull request" />

Tani bëje submit këtë pull request.

<img style="float: right;" src="assets/submit-pull-request.png" alt="submit pull request" />

Së shpejti do të bashkoj (bëj merge) të gjitha ndryshimet te dega master e këtij projekti. Ti do të njoftohesh me email kur të bëhen ndryshimet.

## Ku të shkosh nga këtu?

Urime!  Ti sapo ke kompletuar procesin _fork -> clone -> edit -> PR_ që do ta hasësh shpesh si kontributor!

Festoje kontributin tënd dhe ndaje me shokët dhe ndjekësit duke shkuar te  [web aplikacioni](https://firstcontributions.github.io/#social-share).

Ti mund të bashkohesh në ekipin tonë në slack nëse të duhet ndihmë ose nëse ke ndonjë pyetje. [Bashkohu ekipit në slack](https://join.slack.com/t/firstcontributors/shared_invite/enQtNjkxNzQwNzA2MTMwLTVhMWJjNjg2ODRlNWZhNjIzYjgwNDIyZWYwZjhjYTQ4OTBjMWM0MmFhZDUxNzBiYzczMGNiYzcxNjkzZDZlMDM).

Tani të të ndihmojmë që të kontribuosh në projekte tjera. Ne kemi krijuar një listë projektesh me probleme të lehta tek të cilat mund të fillosh. Shiko [listën e projekteve në web apliacion](https://firstcontributions.github.io/#project-list).

### [Materiale shtesë](additional-material/git_workflow_scenarios/additional-material.md)


## Tutoriale duke përdorur vegla tjera

| <a href="github-desktop-tutorial.md"><img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"></a> | <a href="github-windows-vs2017-tutorial.md"><img alt="Visual Studio 2017" src="https://upload.wikimedia.org/wikipedia/commons/c/cd/Visual_Studio_2017_Logo.svg" width="100"></a> | <a href="gitkraken-tutorial.md"><img alt="GitKraken" src="./assets/gk-icon.png" width="100"></a> | <a href="github-windows-vs-code-tutorial.md"><img alt="VS Code" src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Visual_Studio_Code_1.18_icon.svg" width=100></a> | <a href="sourcetree-macos-tutorial.md"><img alt="Sourcetree App" src="https://wac-cdn.atlassian.com/dam/jcr:81b15cde-be2e-4f4a-8af7-9436f4a1b431/Sourcetree-icon-blue.svg" width=100></a> | <a href="github-windows-intellij-tutorial.md"><img alt="IntelliJ IDEA" src="https://upload.wikimedia.org/wikipedia/commons/d/d5/IntelliJ_IDEA_Logo.svg" width=100></a> |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [GitHub Desktop](gui-tool-tutorials/github-desktop-tutorial.md)                 | [Visual Studio 2017](gui-tool-tutorials/github-windows-vs2017-tutorial.md)      | [GitKraken](gui-tool-tutorials/gitkraken-tutorial.md)                           | [Visual Studio Code](gui-tool-tutorials/github-windows-vs-code-tutorial.md)     | [Atlassian Sourcetree](gui-tool-tutorials/sourcetree-macos-tutorial.md)         | [IntelliJ IDEA](gui-tool-tutorials/github-windows-intellij-tutorial.md)         |
