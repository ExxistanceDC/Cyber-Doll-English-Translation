 <div align="center"><img width="600" alt="Astra_Splash_Cover"  /></div>

# Cyber Doll English Translation

An English translation patch for the Sega Saturn Japanese-exclusive cyberpunk RPG, <a href='https://en.wikipedia.org/wiki/Cyber_Doll'>Cyber Doll</a>.

## Table of Contents
1. [Overview](#Overview)
1. [Screenshots](#Screenshots)
1. [About the Game](#About-the-Game)
1. [Patching Instructions](#Patching-Instructions)
1. [Helpful Game Tips](#Helpful-Game-Tips)
1. [Credits & Special Thanks](#Credits)
1. [Release Changelog](#Release-Changelog)



## **Overview**

The year is 2039. Humanity has defeated **AIDS**.

You would think that would be cause for celebration... but fate had other plans in mind.

A new catastrophe arose... M.L.D. aka Muscular-Loosening Disease. Thankfully, scientists defeated that one as well (although it had the side effect of making people immortal... which apparently is a problem?)

But wait, we're not done yet... 

Now, a new, NEW disease theatens mankind... Dark Visitor! Yet another plague! Sheesh, humanity really can't catch a break... 

<hr>
...And that's your introduction to Cyber Doll, one of the relatively few traditional RPGs that the Saturn was graced with. It has many of those traditional RPG hallmarks, like overworld traversal, NPCs, and shops, but with a slick cyberpunk aesthetic and a unique battle system.

Once again, we have translator extraodinaire **wiredcrackpot** to thank for volunteering to translate the game.

To make game playable entirely in English, the following changes have been implemented:

- Full game dialogue translation alongside implementation of single byte encoding with new 8 x 16 monospaced font
- Translated UI elements
- Modified name entry scream to support English alphabet
- Localized title screen (removal of Japanese text)
- Translated save warning screens



## **Screenshots**

<!-- Row 1 -->
<p>
  <img width="500" alt="Choose_Professional" src="https://github.com/user-attachments/assets/a9b90e04-88f5-4aea-8b7d-22233bbed9fe" />
  <img width="500" alt="Options" src="https://github.com/user-attachments/assets/264b8373-07ea-443f-b96e-50940e9ae651" />
</p>

<!-- Row 2 -->
<p>
  <img width="500" alt="Choose_Professional" src="https://github.com/user-attachments/assets/1d7b32d9-c80d-4b94-bc78-8f9f3ece2e65" />
  <img width="500" alt="Gameplay_screenshot" src="https://github.com/user-attachments/assets/2ab17fe0-1d9f-4c31-aedd-f5e80cca1e8d" />    
</p>

<!-- Row 3 -->
<p>
  <img width="500" alt="Options" src="https://github.com/user-attachments/assets/c09c36dd-bc4f-42ea-bd08-df76f5ae6e9c" />
  <img width="500" alt="Options" src="https://github.com/user-attachments/assets/11b8c1f2-5e0a-44cc-b73c-cf0f13a4ca13" />
</p>

<!-- Row 4 -->
<p>
  <img width="500" alt="Choose_Professional" src="https://github.com/user-attachments/assets/2a344806-8b94-4c5d-b522-e24449898ae2" />
  <img width="500" alt="Title Screen" src="https://github.com/user-attachments/assets/1a36b523-fa46-4b9d-8038-28ddc5b107d4" />    
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

- The game fully utilizes the Saturn RAM carts. In terms of order of best experience, you can think of it like 4 MB RAM > 1 MB RAM > no cart. 
- As usual, the <a href='https://segaretro.org/Astra_Superstars'>Sega Retro page</a> for this game is fantastic. I highly recommend you take a look at it to understand the game's mechanics.
- Wikipedia states that "Depending on what is said, the player can encounter the Devil (based on bad judgment of character) or the Angel (based on good judgement of character) to fight before the final boss" but I don't think this is true based on what I extracted from the game's files. MyAngel is **only** encountered when you play with the character Fooly. All other characters face up against MyDevil.



## **Credits**

**Translation**
- wiredcrackpot

**Texture Art**
- Exxistance

**QA**
- Exxistance

**Special Thanks**
- Sega-Extreme (whose 31st Annual Homebrew competition inspired me to return to my previous menu-only patch)

## **Release Changelog**

- **Version 1.0. (xxxxx/2026)**
  - Initial release


