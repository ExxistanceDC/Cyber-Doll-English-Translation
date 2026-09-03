 <div align="center"><img width="600" alt="Splash_Cover"  /></div>

# Cyber Doll English Translation

An English translation patch for the Sega Saturn Japanese-exclusive cyberpunk RPG, <a href='https://en.wikipedia.org/wiki/Cyber_Doll'>Cyber Doll</a>.

## Table of Contents
1. [Overview](#Overview)
1. [Screenshots](#Screenshots)
1. [About the Game](#About-the-Game)
1. [Patching Instructions](#Patching-Instructions)
1. [Helpful Game Tips](#Helpful-Game-Tips)
1. [Credits & Special Thanks](#Credits)
1. [Reporting Issues](#Reporting-Issues)
1. [Release Changelog](#Release-Changelog)



## **Overview**

The year is 1999. Humanity has defeated **AIDS**.

You would think that would be cause for celebration... but fate had other plans in mind.

A new catastrophe arose... M.L.D. aka Muscular Loosening Disease. Thankfully, scientists defeated that one, too. (Although it had the side effect of making people immortal... which apparently is a problem?)

But wait, we're not done yet... 

Year: 2039. Now, mankind faces a new, _NEW_ threat... Dark Visitor! Yet another deadly disease! Sheesh, humanity really can't catch a break here... 

## 
...And that's your introduction to _Cyber Doll_, one of the relatively few traditional RPGs that the Saturn was graced with. It has many of those traditional 2D RPG hallmarks, like overworld traversal, NPCs, and shops, but with a slick cyberpunk aesthetic and a unique battle system.


Once again, we have translator extraordinaire **wiredcrackpot** to thank for volunteering to translate the game.

To make the game entirely playable in English, the following changes have been implemented:

- Full game dialogue translation alongside implementation of single byte encoding with new 8 x 16 monospaced font
- Translated UI elements
- Modified name entry screen to default to English entry
- Localized title screen (removal of Japanese text)
- Removal of JP subs in the intro video
- Translated save warning screens



## **Screenshots**

<!-- Row 1 -->
<p> 
 <img width="500" src="https://github.com/user-attachments/assets/afca9145-d597-4981-98e3-333ee6e6f95c" />
 <img width="500" src="https://github.com/user-attachments/assets/1fc83b99-a845-4c86-841e-830b8bc80df2" />
</p>

<!-- Row 3 -->
<p>
 <img width="500" src="https://github.com/user-attachments/assets/7aeba4cb-1959-423b-adfd-3faca7ab42a7" />
 <img width="500" src="https://github.com/user-attachments/assets/c333dc33-652b-49f7-a64b-70c0a62f0db7" />

</p>
<!-- Row 3 -->
<p>
 <img width="500" src="https://github.com/user-attachments/assets/f9b6197e-ebbd-4855-949c-f8649ab96245" /> 
 <img width="500" src="https://github.com/user-attachments/assets/6b608dce-25f8-4f84-964e-a4106fe834aa" />
</p>

<!-- Row 4 -->
<p>
 <img width="500" src="https://github.com/user-attachments/assets/932fe719-b650-47a3-9533-0f631f7601cb" />
 <img width="500" src="https://github.com/user-attachments/assets/92bf8ef4-af53-4b91-91e2-979ee00bc1e3" />   
</p>

## **About the Game**

<div align="center">
<table>
  <tr>
    <td><strong>Original Title</strong></td>
    <td>Cyber Doll</td>
  </tr>
  <tr>
    <td><strong>Localized Title</strong></td>
    <td>Cyber Doll</td>
  </tr>
  <tr>
    <td><strong>Developer</strong></td>
    <td>Betop</td>
  </tr>
  <tr>
    <td><strong>Publisher</strong></td>
    <td>I'MAX</td>
  </tr>
    <tr>
    <td><strong>Original Release Date</strong></td>
    <td>1996-08-09</td>
  </tr>
 </table>
</div>


## **Patching Instructions**

The patch is shipped as an XDelta patch. 

### XDelta Instructions ###

1. Grab an XDelta patching utility like <a href='https://www.romhacking.net/utilities/704/'>Delta Patcher</a>
2. Unzip patch bundle
3. Open **'DeltaPatcher.exe'**
4. For the Original File, locate Track 01 of the original Cyber Doll disc (for example: <kbd>Cyber Doll (Japan) (Track 01).bin</kbd> )
5. Locate the <kbd>Cyber_Doll_English_Translation_v1.0.xdelta</kbd> patch.
6. Click **'Apply Patch'**
7. If successful, Track 01 will be replaced with the patched track.

**--> Important! <--**
- Tested with release <kbd>Cyber Doll (Japan)</kbd>
- Test in Ymir, Kronos, and Mednafen emulators, and on real hardware with Satiator.

## Helpful Game Tips ##

- The game has a robust debug mode where you can play with the battle mode, listen to music tracks, view all story strings, and more. Access it by holding **X + Y + Z** and pressing **Start** during the I'MAX logo.



## **Credits**

**Translation**
- wiredcrackpot

**Texture Art**
- Exxistance

**QA**
- Exxistance

**Special Thanks**
- <a href='https://32bits.substack.com/'>Bo Bayles</a> (whose cracking of the game's custom text encoding really unlocked this translation)
- Malenko (who also posted some helpful insight/clues about this game)
- Majuular (whose great video <a href="https://youtu.be/_900EwYcZ5s?si=vR8M6J4y93m9hyZp">"The Weird World of Saturn RPGs"</a> introduced me to this game)
- Whoever it was on the dev team that came up with the awesome debug mode that allowed me to verify all 1,800+ strings easily. MVP! 

## **Reporting Issues**

If you find an issue, be it a text overrun, a crash, or a freeze, please [submit a new issue here](https://github.com/ExxistanceDC/Cyber-Doll-English-Translation/issues/new). The game has been thoroughly tested, but the universe loves a good joke and all that...

## **Release Changelog**

- **Version 1.0. (xxxxx/2026)**
  - Initial release


