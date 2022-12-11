Curriculum Vitae
# Dmitry Kolesnikov
# Dzmitry Kalesnikau
===================================


@@ -8,12 +8,19 @@
>Tel.: *+375-24-**930-00-16***
>Discord: *sugeb#1175*
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


