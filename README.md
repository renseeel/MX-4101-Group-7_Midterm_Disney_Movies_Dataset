   ![WnDrzn](https://github.com/renseeel/MX-4101-Group-7_Midterm_Disney_Movies_Dataset/assets/92082602/204a3d53-6b5b-4a46-b0c5-c8ee987652de)

# *DISNEY MOVIES DATASET*
MX 4101 - Group 7

MexEE 402 - Elective 2 

## Text Functions
A text function is a type of function that takes text as input and returns text as output. Text functions can be used to manipulate text 

>>Length (LEN): *Returns the length of a text string.*

>>Upper (UPPER): *Converts all characters in a text string to uppercase.*

>>Lower (LOWER): *Converts all characters in a text string to lowercase.*

>>Mid (MID): *Extracts a specific number of characters from a text string, starting at a specified position.*

>>Replace (REPLACE): *Replaces all occurrences of a specified text string with another specified text string.*

[U<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
  <head>
      <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
      <meta name="generator" content="PhpSpreadsheet, https://github.com/PHPOffice/PhpSpreadsheet">
      <meta name="author" content="Hannah" />
      <meta name="company" content="Microsoft Corporation" />
    <style type="text/css">
      html { font-family:Calibri, Arial, Helvetica, sans-serif; font-size:11pt; background-color:white }
      a.comment-indicator:hover + div.comment { background:#ffd; position:absolute; display:block; border:1px solid black; padding:0.5em }
      a.comment-indicator { background:red; display:inline-block; border:1px solid black; width:0.5em; height:0.5em }
      div.comment { display:none }
      table { border-collapse:collapse; page-break-after:always }
      .gridlines td { border:1px dotted black }
      .gridlines th { border:1px dotted black }
      .b { text-align:center }
      .e { text-align:center }
      .f { text-align:right }
      .inlineStr { text-align:left }
      .n { text-align:right }
      .s { text-align:left }
      td.style0 { vertical-align:bottom; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      th.style0 { vertical-align:bottom; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      td.style1 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      th.style1 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      td.style2 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; font-weight:bold; color:#F2F2F2; font-family:'Calibri'; font-size:12pt; background-color:#ACAFD5 }
      th.style2 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; font-weight:bold; color:#F2F2F2; font-family:'Calibri'; font-size:12pt; background-color:#ACAFD5 }
      td.style3 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:#EEEEF6 }
      th.style3 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:#EEEEF6 }
      td.style4 { vertical-align:middle; text-align:center; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      th.style4 { vertical-align:middle; text-align:center; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      td.style5 { vertical-align:bottom; text-align:center; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      th.style5 { vertical-align:bottom; text-align:center; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      td.style6 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; font-weight:bold; color:#F2F2F2; font-family:'Calibri'; font-size:12pt; background-color:#ACAFD5 }
      th.style6 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; font-weight:bold; color:#F2F2F2; font-family:'Calibri'; font-size:12pt; background-color:#ACAFD5 }
      td.style7 { vertical-align:bottom; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; font-weight:bold; color:#F2F2F2; font-family:'Calibri'; font-size:12pt; background-color:#ACAFD5 }
      th.style7 { vertical-align:bottom; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; font-weight:bold; color:#F2F2F2; font-family:'Calibri'; font-size:12pt; background-color:#ACAFD5 }
      td.style8 { vertical-align:bottom; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      th.style8 { vertical-align:bottom; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      table.sheet0 col.col0 { width:241.28888612pt }
      table.sheet0 col.col1 { width:58.96666599pt }
      table.sheet0 col.col2 { width:208.75555316pt }
      table.sheet0 col.col3 { width:172.83333135pt }
      table.sheet0 col.col4 { width:86.07777679pt }
      table.sheet0 col.col5 { width:194.52221999pt }
      table.sheet0 tr { height:15pt }
      table.sheet0 tr.row0 { height:16.3pt }
    </style>
  </head>

  <body>
<style>
@page { margin-left: 0.7in; margin-right: 0.7in; margin-top: 0.75in; margin-bottom: 0.75in; }
body { margin-left: 0.7in; margin-right: 0.7in; margin-top: 0.75in; margin-bottom: 0.75in; }
</style>
    <table border="0" cellpadding="0" cellspacing="0" id="sheet0" class="sheet0 gridlines">
        <col class="col0">
        <col class="col1">
        <col class="col2">
        <col class="col3">
        <col class="col4">
        <col class="col5">
        <tbody>
          <tr class="row0">
            <td class="column0 style2 s">MOVIE TITLE</td>
            <td class="column1 style6 s">Length</td>
            <td class="column2 style6 s">Upper</td>
            <td class="column3 style7 s">Lower</td>
            <td class="column4 style7 s">Mid</td>
            <td class="column5 style6 s">Replace</td>
          </tr>
          <tr class="row1">
            <td class="column0 style3 s">Flight of the Navigator</td>
            <td class="column1 style1 f">23</td>
            <td class="column2 style1 f">FLIGHT OF THE NAVIGATOR</td>
            <td class="column3 style8 f">flight of the navigator</td>
            <td class="column4 style8 f">ht of the </td>
            <td class="column5 style1 f">MIDTERM CUTIE  of the Navigator</td>
          </tr>
          <tr class="row2">
            <td class="column0 style1 s">Tarzan</td>
            <td class="column1 style1 f">6</td>
            <td class="column2 style1 f">TARZAN</td>
            <td class="column3 style8 f">tarzan</td>
            <td class="column4 style8 f">an</td>
            <td class="column5 style1 f">MIDTERM CUTIE </td>
          </tr>
          <tr class="row3">
            <td class="column0 style3 s">Summer of Sam</td>
            <td class="column1 style1 f">13</td>
            <td class="column2 style1 f">SUMMER OF SAM</td>
            <td class="column3 style8 f">summer of sam</td>
            <td class="column4 style8 f">er of Sam</td>
            <td class="column5 style1 f">MIDTERM CUTIE  of Sam</td>
          </tr>
          <tr class="row4">
            <td class="column0 style1 s">Inspector Gadget</td>
            <td class="column1 style1 f">16</td>
            <td class="column2 style1 f">INSPECTOR GADGET</td>
            <td class="column3 style8 f">inspector gadget</td>
            <td class="column4 style8 f">ector Gadg</td>
            <td class="column5 style1 f">MIDTERM CUTIE tor Gadget</td>
          </tr>
          <tr class="row5">
            <td class="column0 style3 s">The Sixth Sense</td>
            <td class="column1 style1 f">15</td>
            <td class="column2 style1 f">THE SIXTH SENSE</td>
            <td class="column3 style8 f">the sixth sense</td>
            <td class="column4 style8 f">Sixth Sens</td>
            <td class="column5 style1 f">MIDTERM CUTIE xth Sense</td>
          </tr>
          <tr class="row6">
            <td class="column0 style1 s">The 13th Warrior</td>
            <td class="column1 style1 f">16</td>
            <td class="column2 style1 f">THE 13TH WARRIOR</td>
            <td class="column3 style8 f">the 13th warrior</td>
            <td class="column4 style8 f">13th Warri</td>
            <td class="column5 style1 f">MIDTERM CUTIE th Warrior</td>
          </tr>
          <tr class="row7">
            <td class="column0 style3 s">Breakfast of Champions</td>
            <td class="column1 style1 f">22</td>
            <td class="column2 style1 f">BREAKFAST OF CHAMPIONS</td>
            <td class="column3 style8 f">breakfast of champions</td>
            <td class="column4 style8 f">kfast of C</td>
            <td class="column5 style1 f">MIDTERM CUTIE ast of Champions</td>
          </tr>
          <tr class="row8">
            <td class="column0 style1 s">Mumford</td>
            <td class="column1 style1 f">7</td>
            <td class="column2 style1 f">MUMFORD</td>
            <td class="column3 style8 f">mumford</td>
            <td class="column4 style8 f">ord</td>
            <td class="column5 style1 f">MIDTERM CUTIE d</td>
          </tr>
          <tr class="row9">
            <td class="column0 style3 s">Mystery, Alaska</td>
            <td class="column1 style1 f">15</td>
            <td class="column2 style1 f">MYSTERY, ALASKA</td>
            <td class="column3 style8 f">mystery, alaska</td>
            <td class="column4 style8 f">ery, Alask</td>
            <td class="column5 style1 f">MIDTERM CUTIE y, Alaska</td>
          </tr>
          <tr class="row10">
            <td class="column0 style1 s">The Straight Story</td>
            <td class="column1 style1 f">18</td>
            <td class="column2 style1 f">THE STRAIGHT STORY</td>
            <td class="column3 style8 f">the straight story</td>
            <td class="column4 style8 f">Straight S</td>
            <td class="column5 style1 f">MIDTERM CUTIE raight Story</td>
          </tr>
          <tr class="row11">
            <td class="column0 style3 s">The Insider</td>
            <td class="column1 style1 f">11</td>
            <td class="column2 style1 f">THE INSIDER</td>
            <td class="column3 style8 f">the insider</td>
            <td class="column4 style8 f">Insider</td>
            <td class="column5 style1 f">MIDTERM CUTIE sider</td>
          </tr>
          <tr class="row12">
            <td class="column0 style1 s">Toy Story 2</td>
            <td class="column1 style1 f">11</td>
            <td class="column2 style1 f">TOY STORY 2</td>
            <td class="column3 style8 f">toy story 2</td>
            <td class="column4 style8 f">Story 2</td>
            <td class="column5 style1 f">MIDTERM CUTIE ory 2</td>
          </tr>
          <tr class="row13">
            <td class="column0 style3 s">Cradle Will Rock</td>
            <td class="column1 style1 f">16</td>
            <td class="column2 style1 f">CRADLE WILL ROCK</td>
            <td class="column3 style8 f">cradle will rock</td>
            <td class="column4 style8 f">le Will Ro</td>
            <td class="column5 style1 f">MIDTERM CUTIE  Will Rock</td>
          </tr>
          <tr class="row14">
            <td class="column0 style1 s">Deuce Bigalow: Male Gigolo</td>
            <td class="column1 style1 f">26</td>
            <td class="column2 style1 f">DEUCE BIGALOW: MALE GIGOLO</td>
            <td class="column3 style8 f">deuce bigalow: male gigolo</td>
            <td class="column4 style8 f">e Bigalow:</td>
            <td class="column5 style1 f">MIDTERM CUTIE Bigalow: Male Gigolo</td>
          </tr>
          <tr class="row15">
            <td class="column0 style3 s">Bicentennial Man</td>
            <td class="column1 style1 f">16</td>
            <td class="column2 style1 f">BICENTENNIAL MAN</td>
            <td class="column3 style8 f">bicentennial man</td>
            <td class="column4 style8 f">ntennial M</td>
            <td class="column5 style1 f">MIDTERM CUTIE ennial Man</td>
          </tr>
          <tr class="row16">
            <td class="column0 style1 s">Play it to the Bone</td>
            <td class="column1 style1 f">19</td>
            <td class="column2 style1 f">PLAY IT TO THE BONE</td>
            <td class="column3 style8 f">play it to the bone</td>
            <td class="column4 style8 f">&nbsp;it to the</td>
            <td class="column5 style1 f">MIDTERM CUTIE t to the Bone</td>
          </tr>
          <tr class="row17">
            <td class="column0 style3 s">Fantasia 2000 (IMAX)</td>
            <td class="column1 style1 f">20</td>
            <td class="column2 style1 f">FANTASIA 2000 (IMAX)</td>
            <td class="column3 style8 f">fantasia 2000 (imax)</td>
            <td class="column4 style8 f">asia 2000 </td>
            <td class="column5 style1 f">MIDTERM CUTIE ia 2000 (IMAX)</td>
          </tr>
          <tr class="row18">
            <td class="column0 style1 s">Gun Shy</td>
            <td class="column1 style1 f">7</td>
            <td class="column2 style1 f">GUN SHY</td>
            <td class="column3 style8 f">gun shy</td>
            <td class="column4 style8 f">Shy</td>
            <td class="column5 style1 f">MIDTERM CUTIE y</td>
          </tr>
          <tr class="row19">
            <td class="column0 style3 s">The Tigger Movie</td>
            <td class="column1 style1 f">16</td>
            <td class="column2 style1 f">THE TIGGER MOVIE</td>
            <td class="column3 style8 f">the tigger movie</td>
            <td class="column4 style8 f">Tigger Mov</td>
            <td class="column5 style1 f">MIDTERM CUTIE gger Movie</td>
          </tr>
          <tr class="row20">
            <td class="column0 style1 s">Mission to Mars</td>
            <td class="column1 style1 f">15</td>
            <td class="column2 style1 f">MISSION TO MARS</td>
            <td class="column3 style8 f">mission to mars</td>
            <td class="column4 style8 f">ion to Mar</td>
            <td class="column5 style1 f">MIDTERM CUTIE n to Mars</td>
          </tr>
          <tr class="row21">
            <td class="column0 style3 s">High Fidelity</td>
            <td class="column1 style1 f">13</td>
            <td class="column2 style1 f">HIGH FIDELITY</td>
            <td class="column3 style8 f">high fidelity</td>
            <td class="column4 style8 f">&nbsp;Fidelity</td>
            <td class="column5 style1 f">MIDTERM CUTIE idelity</td>
          </tr>
          <tr class="row22">
            <td class="column0 style1 s">Keeping the Faith</td>
            <td class="column1 style1 f">17</td>
            <td class="column2 style1 f">KEEPING THE FAITH</td>
            <td class="column3 style8 f">keeping the faith</td>
            <td class="column4 style8 f">ing the Fa</td>
            <td class="column5 style1 f">MIDTERM CUTIE g the Faith</td>
          </tr>
          <tr class="row23">
            <td class="column0 style3 s">Dinosaur</td>
            <td class="column1 style1 f">8</td>
            <td class="column2 style1 f">DINOSAUR</td>
            <td class="column3 style8 f">dinosaur</td>
            <td class="column4 style8 f">saur</td>
            <td class="column5 style1 f">MIDTERM CUTIE ur</td>
          </tr>
          <tr class="row24">
            <td class="column0 style1 s">Shanghai Noon</td>
            <td class="column1 style1 f">13</td>
            <td class="column2 style1 f">SHANGHAI NOON</td>
            <td class="column3 style8 f">shanghai noon</td>
            <td class="column4 style8 f">ghai Noon</td>
            <td class="column5 style1 f">MIDTERM CUTIE ai Noon</td>
          </tr>
          <tr class="row25">
            <td class="column0 style3 s">Gone in 60 Seconds</td>
            <td class="column1 style1 f">18</td>
            <td class="column2 style1 f">GONE IN 60 SECONDS</td>
            <td class="column3 style8 f">gone in 60 seconds</td>
            <td class="column4 style8 f">&nbsp;in 60 Sec</td>
            <td class="column5 style1 f">MIDTERM CUTIE n 60 Seconds</td>
          </tr>
          <tr class="row26">
            <td class="column0 style1 s">Fantasia 2000 (Theatrical Release)</td>
            <td class="column1 style1 f">34</td>
            <td class="column2 style1 f">FANTASIA 2000 (THEATRICAL RELEASE)</td>
            <td class="column3 style8 f">fantasia 2000 (theatrical release)</td>
            <td class="column4 style8 f">asia 2000 </td>
            <td class="column5 style1 f">MIDTERM CUTIE ia 2000 (Theatrical Release)</td>
          </tr>
          <tr class="row27">
            <td class="column0 style3 s">The Kid</td>
            <td class="column1 style1 f">7</td>
            <td class="column2 style1 f">THE KID</td>
            <td class="column3 style8 f">the kid</td>
            <td class="column4 style8 f">Kid</td>
            <td class="column5 style1 f">MIDTERM CUTIE d</td>
          </tr>
          <tr class="row28">
            <td class="column0 style1 s">Coyote Ugly</td>
            <td class="column1 style1 f">11</td>
            <td class="column2 style1 f">COYOTE UGLY</td>
            <td class="column3 style8 f">coyote ugly</td>
            <td class="column4 style8 f">te Ugly</td>
            <td class="column5 style1 f">MIDTERM CUTIE  Ugly</td>
          </tr>
          <tr class="row29">
            <td class="column0 style3 s">The Crew</td>
            <td class="column1 style1 f">8</td>
            <td class="column2 style1 f">THE CREW</td>
            <td class="column3 style8 f">the crew</td>
            <td class="column4 style8 f">Crew</td>
            <td class="column5 style1 f">MIDTERM CUTIE ew</td>
          </tr>
          <tr class="row30">
            <td class="column0 style1 s">Duets</td>
            <td class="column1 style1 f">5</td>
            <td class="column2 style1 f">DUETS</td>
            <td class="column3 style8 f">duets</td>
            <td class="column4 style8 f">s</td>
            <td class="column5 style1 f">MIDTERM CUTIE #VALUE!</td>
          </tr>
          <tr class="row31">
            <td class="column0 style3 s">Remember the Titans</td>
            <td class="column1 style1 f">19</td>
            <td class="column2 style1 f">REMEMBER THE TITANS</td>
            <td class="column3 style8 f">remember the titans</td>
            <td class="column4 style8 f">mber the T</td>
            <td class="column5 style1 f">MIDTERM CUTIE er the Titans</td>
          </tr>
          <tr class="row32">
            <td class="column0 style1 s">Unbreakable</td>
            <td class="column1 style1 f">11</td>
            <td class="column2 style1 f">UNBREAKABLE</td>
            <td class="column3 style8 f">unbreakable</td>
            <td class="column4 style8 f">eakable</td>
            <td class="column5 style1 f">MIDTERM CUTIE kable</td>
          </tr>
          <tr class="row33">
            <td class="column0 style3 s">102 Dalmatians</td>
            <td class="column1 style1 f">14</td>
            <td class="column2 style1 f">102 DALMATIANS</td>
            <td class="column3 style8 f">102 dalmatians</td>
            <td class="column4 style8 f">Dalmatians</td>
            <td class="column5 style1 f">MIDTERM CUTIE lmatians</td>
          </tr>
          <tr class="row34">
            <td class="column0 style1 s">The Emperor's New Groove</td>
            <td class="column1 style1 f">24</td>
            <td class="column2 style1 f">THE EMPEROR'S NEW GROOVE</td>
            <td class="column3 style8 f">the emperor's new groove</td>
            <td class="column4 style8 f">Emperor's </td>
            <td class="column5 style1 f">MIDTERM CUTIE peror's New Groove</td>
          </tr>
          <tr class="row35">
            <td class="column0 style3 s">O Brother, Where Art Thou?</td>
            <td class="column1 style1 f">26</td>
            <td class="column2 style1 f">O BROTHER, WHERE ART THOU?</td>
            <td class="column3 style8 f">o brother, where art thou?</td>
            <td class="column4 style8 f">other, Whe</td>
            <td class="column5 style1 f">MIDTERM CUTIE her, Where Art Thou?</td>
          </tr>
          <tr class="row36">
            <td class="column0 style1 s">Double Take</td>
            <td class="column1 style1 f">11</td>
            <td class="column2 style1 f">DOUBLE TAKE</td>
            <td class="column3 style8 f">double take</td>
            <td class="column4 style8 f">le Take</td>
            <td class="column5 style1 f">MIDTERM CUTIE  Take</td>
          </tr>
          <tr class="row37">
            <td class="column0 style3 s">Recess: School's Out</td>
            <td class="column1 style1 f">20</td>
            <td class="column2 style1 f">RECESS: SCHOOL'S OUT</td>
            <td class="column3 style8 f">recess: school's out</td>
            <td class="column4 style8 f">ss: School</td>
            <td class="column5 style1 f">MIDTERM CUTIE : School's Out</td>
          </tr>
          <tr class="row38">
            <td class="column0 style1 s">Just Visiting</td>
            <td class="column1 style1 f">13</td>
            <td class="column2 style1 f">JUST VISITING</td>
            <td class="column3 style8 f">just visiting</td>
            <td class="column4 style8 f">&nbsp;Visiting</td>
            <td class="column5 style1 f">MIDTERM CUTIE isiting</td>
          </tr>
          <tr class="row39">
            <td class="column0 style3 s">Pearl Harbor</td>
            <td class="column1 style1 f">12</td>
            <td class="column2 style1 f">PEARL HARBOR</td>
            <td class="column3 style8 f">pearl harbor</td>
            <td class="column4 style8 f">l Harbor</td>
            <td class="column5 style1 f">MIDTERM CUTIE Harbor</td>
          </tr>
          <tr class="row40">
            <td class="column0 style1 s">Atlantis: The Lost Empire</td>
            <td class="column1 style1 f">25</td>
            <td class="column2 style1 f">ATLANTIS: THE LOST EMPIRE</td>
            <td class="column3 style8 f">atlantis: the lost empire</td>
            <td class="column4 style8 f">ntis: The </td>
            <td class="column5 style1 f">MIDTERM CUTIE is: The Lost Empire</td>
          </tr>
          <tr class="row41">
            <td class="column0 style3 s">crazy/beautiful</td>
            <td class="column1 style1 f">15</td>
            <td class="column2 style1 f">CRAZY/BEAUTIFUL</td>
            <td class="column3 style8 f">crazy/beautiful</td>
            <td class="column4 style8 f">y/beautifu</td>
            <td class="column5 style1 f">MIDTERM CUTIE beautiful</td>
          </tr>
          <tr class="row42">
            <td class="column0 style1 s">The Princess Diaries</td>
            <td class="column1 style1 f">20</td>
            <td class="column2 style1 f">THE PRINCESS DIARIES</td>
            <td class="column3 style8 f">the princess diaries</td>
            <td class="column4 style8 f">Princess D</td>
            <td class="column5 style1 f">MIDTERM CUTIE incess Diaries</td>
          </tr>
          <tr class="row43">
            <td class="column0 style3 s">Bubble Boy</td>
            <td class="column1 style1 f">10</td>
            <td class="column2 style1 f">BUBBLE BOY</td>
            <td class="column3 style8 f">bubble boy</td>
            <td class="column4 style8 f">le Boy</td>
            <td class="column5 style1 f">MIDTERM CUTIE  Boy</td>
          </tr>
          <tr class="row44">
            <td class="column0 style1 s">Max Keeble's Big Move</td>
            <td class="column1 style1 f">21</td>
            <td class="column2 style1 f">MAX KEEBLE'S BIG MOVE</td>
            <td class="column3 style8 f">max keeble's big move</td>
            <td class="column4 style8 f">Keeble's B</td>
            <td class="column5 style1 f">MIDTERM CUTIE eble's Big Move</td>
          </tr>
          <tr class="row45">
            <td class="column0 style3 s">Corky Romano</td>
            <td class="column1 style1 f">12</td>
            <td class="column2 style1 f">CORKY ROMANO</td>
            <td class="column3 style8 f">corky romano</td>
            <td class="column4 style8 f">y Romano</td>
            <td class="column5 style1 f">MIDTERM CUTIE Romano</td>
          </tr>
          <tr class="row46">
            <td class="column0 style1 s">High Heels and Low Lifes</td>
            <td class="column1 style1 f">24</td>
            <td class="column2 style1 f">HIGH HEELS AND LOW LIFES</td>
            <td class="column3 style8 f">high heels and low lifes</td>
            <td class="column4 style8 f">&nbsp;Heels and</td>
            <td class="column5 style1 f">MIDTERM CUTIE eels and Low Lifes</td>
          </tr>
          <tr class="row47">
            <td class="column0 style3 s">Monsters, Inc.</td>
            <td class="column1 style1 f">14</td>
            <td class="column2 style1 f">MONSTERS, INC.</td>
            <td class="column3 style8 f">monsters, inc.</td>
            <td class="column4 style8 f">ters, Inc.</td>
            <td class="column5 style1 f">MIDTERM CUTIE rs, Inc.</td>
          </tr>
          <tr class="row48">
            <td class="column0 style1 s">Out Cold</td>
            <td class="column1 style1 f">8</td>
            <td class="column2 style1 f">OUT COLD</td>
            <td class="column3 style8 f">out cold</td>
            <td class="column4 style8 f">Cold</td>
            <td class="column5 style1 f">MIDTERM CUTIE ld</td>
          </tr>
          <tr class="row49">
            <td class="column0 style3 s">The Royal Tenenbaums</td>
            <td class="column1 style1 f">20</td>
            <td class="column2 style1 f">THE ROYAL TENENBAUMS</td>
            <td class="column3 style8 f">the royal tenenbaums</td>
            <td class="column4 style8 f">Royal Tene</td>
            <td class="column5 style1 f">MIDTERM CUTIE yal Tenenbaums</td>
          </tr>
          <tr class="row50">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row51">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row52">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row53">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row54">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row55">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row56">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row57">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row58">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row59">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row60">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row61">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row62">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row63">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row64">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row65">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row66">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row67">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row68">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row69">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row70">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row71">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row72">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row73">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row74">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row75">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row76">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row77">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row78">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row79">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row80">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row81">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row82">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row83">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row84">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row85">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row86">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row87">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row88">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row89">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row90">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row91">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row92">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row93">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row94">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row95">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row96">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row97">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row98">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row99">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row100">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row101">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row102">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row103">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row104">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row105">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row106">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row107">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row108">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row109">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row110">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row111">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row112">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row113">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row114">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row115">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row116">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row117">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row118">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row119">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row120">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row121">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row122">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row123">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row124">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row125">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row126">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row127">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row128">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row129">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row130">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row131">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row132">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row133">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row134">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row135">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row136">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row137">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row138">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row139">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row140">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row141">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row142">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row143">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row144">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row145">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row146">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row147">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row148">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row149">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row150">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row151">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row152">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row153">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row154">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row155">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row156">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row157">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row158">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row159">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row160">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row161">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row162">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row163">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row164">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row165">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row166">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row167">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row168">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row169">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row170">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row171">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row172">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row173">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row174">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row175">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row176">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row177">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row178">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row179">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row180">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row181">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row182">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row183">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row184">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row185">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row186">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row187">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row188">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row189">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row190">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row191">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row192">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row193">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row194">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row195">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row196">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row197">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row198">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row199">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row200">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row201">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row202">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row203">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row204">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row205">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row206">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row207">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row208">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row209">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row210">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row211">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row212">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row213">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row214">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row215">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row216">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row217">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row218">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row219">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row220">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row221">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row222">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row223">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row224">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row225">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row226">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row227">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row228">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row229">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row230">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row231">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row232">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row233">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row234">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row235">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row236">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row237">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row238">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row239">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row240">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row241">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row242">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row243">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row244">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row245">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row246">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row247">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row248">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row249">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row250">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row251">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row252">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row253">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row254">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row255">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row256">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row257">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row258">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row259">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row260">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row261">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row262">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row263">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row264">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row265">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row266">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row267">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row268">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row269">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row270">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row271">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row272">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row273">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
          <tr class="row274">
            <td class="column0 style4 null"></td>
            <td class="column1">&nbsp;</td>
            <td class="column2 style5 null"></td>
            <td class="column3">&nbsp;</td>
            <td class="column4 style4 null"></td>
            <td class="column5 style4 null"></td>
          </tr>
        </tbody>
    </table>
  </body>
</html>
ploading Text-Functions-Upload.html…]()



## Math Functions
A math function is a built-in mathematical operation or formula that you can use to perform various calculations on numerical data in your spreadsheets. These functions make it easier to perform complex mathematical operations without having to write custom formulas. 

>>Greatest Common Denominator (GCD): *Returns the largest positive integer that is a divisor of all the given integers.*

>>Average (AVERAGE): *Returns the average of the given numbers.*

>>Absolute Value (ABS): *Returns the non-negative absolute value of the given number.*

>>Square Root(SQRT): *Returns the square root of the given number.*

>>Sign (SIGN): *Returns the sign of the given number. The sign of a number is either 1 (positive), 0 (zero), or -1 (negative).*

## Logical Functions
A logical function is a built-in functions that allows you to perform operations based on logical conditions or criteria. These functions help you make decisions, evaluate data, and perform tasks based on whether certain conditions are met. Logical functions return either TRUE or FALSE as their results, which are commonly used for conditional formatting, data analysis, and complex decision-making within spreadsheets. 

>>IF Function (IF): *Returns one value if a condition is met, and another value if the condition is not met.*

>>OR Function (OR): *Returns true if any of the given conditions are true, and false if all of the conditions are false.*

>>NOT Function (NOT): *Returns the opposite of the given Boolean value.* 

>>XOR Function (XOR): *Returns true if exactly one of the given conditions is true, and false otherwise.*

>>ISBLANK Function (ISBLANK): *Returns true if the given cell is blank, and false otherwise.*

## Information Functions
Information functions provide information about the content, formatting and location of cells in an Excel Worksheet.

>>ISERROR Function (ISERROR): *Returns true if the value of the cell is an error, false otherwise*

>>ISNUMBER Function (ISNUMBER): *Returns true if the value of the cell is a number, false otherwise.*

>>ISTEXT Function (ISTEXT): *Returns true if the value of the cell is text, false otherwise.*

>>ISNA Function (ISNA): *Returns true if the value of the cell is #N/A, false otherwise.*

>>ISREF Function (ISREF): *Returns true if the value of the cell is a reference to another cell or range of cells, false otherwise.*

## Date and Time Functions
Date and Time functions provides a variety of functions for working with dates and times. These functions allow you to perform calculations, manipulate dates and times, and format them as needed. 
 
 >>WEEKNUM Function (WEEKNUM): *Returns the week number of a date, according to the specified locale.*

>>DAY Function (WEEKNUM): *Returns the week number of a date, according to the specified locale.*

>>MONTH Function (MONTH): *Returns the month number from a date.*

>>YEAR Function (YEAR): *Returns the year number from a date.*

>>DATE Function (DATE): *Creates a date from the specified year, month, and day.*

>>EOMONTH Function (EOMONTH): *Returns the last day of the month for a specified date.*

## Lookup Functions
Lookup functions are used to search for a specific value in a range or table of data and return related information from that range. These functions are extremely useful for tasks such as finding corresponding values, performing approximate matches, and retrieving data from large datasets.

>>LOOKUP Function (LOOKUP): *Returns a value from a table based on a given value.*

>>ADDRESS Function (ADDRESS): *Returns the cell address of a cell based on a given row and column number.*

>>MATCH Function (MATCH): *Returns the position of a value in a table.*

>>CHOOSE Function (CHOOSE): *Returns a value from a list of values based on a given index number.*

>>COLUMN Function (COLUMN): *Returns the column number of a cell.*
