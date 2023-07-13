# Monkeytype Word Doc Guide:
_______________________________________________________

## Font:
Calibri Download: https://www.downloadfonts.io/downloads/calibri-font/
(Download Calibri in order to have the font in Monkeytype.)
———————————————————————————————————————————————————————

## MonkeyType Settings. 
(Go to https://monkeytype.com/settings, scroll down to "Danger Zone", and click "import". Then copy paste the settings below.)
<details>
 <summary>Settings to Import</summary>
{"theme":"vscode","themeLight":"serika","themeDark":"serika_dark","autoSwitchTheme":false,"customTheme":true,"customThemeColors":["#ffffff","#000000","#e2b714","#1c1c1c","#2c2e31","#000000","#ca4754","#7e2a33","#ca4754","#7e2a33"],"favThemes":[],"showKeyTips":false,"showLiveWpm":false,"showTimerProgress":true,"smoothCaret":true,"quickRestart":"tab","punctuation":false,"numbers":false,"words":10,"time":15,"mode":"time","quoteLength":[3],"language":"english","fontSize":2,"freedomMode":false,"difficulty":"normal","blindMode":false,"quickEnd":false,"caretStyle":"default","paceCaretStyle":"underline","flipTestColors":false,"layout":"default","funbox":"none","confidenceMode":"off","indicateTypos":"below","timerStyle":"mini","colorfulMode":true,"randomTheme":"off","timerColor":"main","timerOpacity":"0.25","stopOnError":"off","showAllLines":false,"keymapMode":"off","keymapStyle":"staggered","keymapLegendStyle":"lowercase","keymapLayout":"colemak","keymapShowTopRow":"layout","fontFamily":"Calibri","smoothLineScroll":true,"alwaysShowDecimalPlaces":false,"alwaysShowWordsHistory":false,"singleListCommandLine":"manual","capsLockWarning":false,"playSoundOnError":false,"playSoundOnClick":"off","soundVolume":"1.0","startGraphsAtZero":true,"showOutOfFocusWarning":false,"paceCaret":"pb","paceCaretCustomSpeed":170,"repeatedPace":true,"pageWidth":"125","chartAccuracy":true,"chartStyle":"line","minWpm":"off","minWpmCustomSpeed":100,"highlightMode":"letter","alwaysShowCPM":false,"ads":"off","hideExtraLetters":false,"strictSpace":false,"minAcc":"off","minAccCustom":90,"showLiveAcc":false,"showLiveBurst":false,"monkey":false,"repeatQuotes":"off","oppositeShiftMode":"off","customBackground":"https://i.imgur.com/Nlr5onP.png","customBackgroundSize":"cover","customBackgroundFilter":[0,1,1,1],"customLayoutfluid":"qwerty#dvorak#colemak","monkeyPowerLevel":"off","minBurst":"off","minBurstCustomSpeed":100,"burstHeatmap":false,"britishEnglish":false,"lazyMode":false,"showAverage":"off","tapeMode":"off"}
</details>
————————————————————————————————————————————————————————

## Removing Other Elements
Stylus is required for the CSS code to modify the page. 
(Install Stylus at 
https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne or https://addons.mozilla.org/en-US/firefox/addon/styl-us/) 

Visit Monkeytype and open Stylus, then click write style. Then paste the code, press save and enable it.
<details>
 <summary>CSS Code</summary>

#top .logo .text {
        visibility: hidden;
    }

#top .logo .text .top {
        visibility: hidden;
}
    
    #top .logo {
        visibility: hidden;
    }
    #top .logo .bottom {
        visibility: hidden;
    }

    #bottom {
    visibility: hidden;
}

    #top .icon {
    visibility: hidden;
}
    #top .account {
    visibility: hidden;
}
    #top .notifications {
    visibility: hidden;
}
    #menu {
    visibility: hidden;
    display: none;
}   
    #testConfig {
    visibility: hidden;
}
#typingTest {

        transform: translateY(-100px);
        margin-left: 10%;
        margin-right: 10%;
}

 #commandLine {
        background: none !important;
    }
    #commandLineWrapper {
        background: none;
        backdrop-filter: blur(5px) brightness(0.5);
        transition: 0.5s ease;
    }
    #commandLine input {
        background: none !important;
    }
    #commandLine > div:first-child {
        border-radius: 0;
        border-bottom: 1px solid var(--sub-color) !important;
    }

    /* command line scrollbar */
    #commandLine .suggestions {
        scrollbar-width: none !important;
        scrollbar-color: rgba(255, 255, 255, .1) transparent !important;
    }
    #commandLine .suggestions:hover {
        scrollbar-width: thin !important;
    }
    #commandLine .suggestions::-webkit-scrollbar {
        width: 0px;
    }
    #commandLine .suggestions:hover::-webkit-scrollbar {
        width: 7px;
    }
</details>
