#Curriculum Vitae
# Dzmitry Kalesnikau
===================================


## Contact information
>Tel.: *+375-24-**930-00-16***
>Discord: *sugeb#1175*
>E-Mail: *chem@chem.by*


## About me
Programming is part of my hobbies. My main hobby is chemistry and radio electronics (HAM radio, sci-tech devices). 
I have some experience in repairing and developing electronic devices. Including for the purposes of scientific research, and I can also conduct research work myself.

I am a chemist-researcher-teacher by first profession. And a software engineer for the second (development of applied software).
Has over 10 years of teaching experience.

I want to learn modern web application development techniques.

At the moment I think that I would like to make my hobby as a form of my main activity.

## Skills
* Programming languages
    + Delphi (7)
    + C (Atmel)
    + SQL (MySql)
    + HTML (old, 2005)
    + JavaScript (old, 2005)
    + PHP (old, 2005)
* Operation systems
    + Windows (all versions from 95/NT4.0, including server)
* Development tools
    + Borland Delphi 7
    + Embarcadero RAD Studio 11
    + CodeVision AVR
    + DipTrace
    + UltraEdit
    + MMANA-GAL
    + Proteus
    

## Sample code
```
procedure GroupNameToGroupData(var mcgdata:TMCServerGroups);
 var i:integer;
 const DEF_PREF='&7[&7Unknown&7]&9';
       DEF_SUFF='&r&8%!187!% &7';
begin
 mcgdata.is_enabled:=false;
 for i:=0 to MAX_GROUPS do
  if grops[i].is_enabled then
   if ((mcgdata.server_id=grops[i].server_id) and
    (AnsiLowerCase(mcgdata.group_name)=AnsiLowerCase(grops[i].group_name))) then
    begin
     mcgdata:=grops[i];
     Break;
    end;
 if not mcgdata.is_enabled then
  for i:=0 to MAX_GROUPS do
   if grops[i].is_enabled then
    if ((mcgdata.server_id=grops[i].server_id) and
    (AnsiLowerCase(grops[i].group_name)=AnsiLowerCase(UNK_GROUP_NAME))) then
     begin
      mcgdata:=grops[i];
      mcgdata.group_name:=DEF_GROUP_NAME;
      Break;
     end;
 if not mcgdata.is_enabled then SetDefaultMCGD(mcgdata);
end;
```


## Work experience
- Diagnostics and repair of electronic and electrical equipment (from the 2000s);
- Design and manufacture of electronic devices (from the 2000s);
- Chemistry, Biology & IT Teacher (from 2003);
- Software Engineering, work with Delphi, C, PHP (from 2005);
- Research activities in the field of information security (from 2007);
- Creation, management and protection of Quake3 (from 2009) and Minecraft (from 2018) game servers;
- Welding, Plumbing and construction work (from 2010);
- Design and construction of engineering networks: electrical, plumbing, sewerage, alarm, video surveillance (from 2010);
- Designing the construction and operation of enterprise computer networks, Windows Server configuration and administration (from 2011);
- Creation of an online cat care system (2012);
- Development of detectors of concealed wear headphones (2012-2018);
- Development of a reagent and property accounting database (2012-2013);
- Development of the synthesis of fire-resistant oils (2016-2017);
- Development and manufacture of radiation measuring devices (2016-2018).

I have several working websites, before I started learning in course RS School "JavaScript/Front-end. Stage 0" . For example, this website was written in notepad, 2009: [Chem.by](http://chem.by "Simple html site")
And this - in Delphi 7, a few years ago: [Chemistry.by](http://chemistry.by "Simple d7 site")


## Education, training and certificates 
- Chemistry & Biology Teacher University Diploma (2009)
- Software Engineering University Retraining Diploma (2012)
- 4 certificates of honor (state award) for scientific and pedagogical activities in the field of energy saving
- 2 certificates for active participation in competitions of scientific and technical creativity
- 5 certificates of advanced training in educational activities, teacher of the 1st category
- Amateur radio license, 1st class


## Languages
- Belorussian, C2
- Russian, C2
- English, A2/B1 (verbal/written)