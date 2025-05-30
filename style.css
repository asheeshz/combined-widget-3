/* ==========================================================================
   Vedic Bloom TOC CSS for Blogger (v5.8.3 - Ruby Sidebar, Custom Highlight, Scrollable Button Pattern Fix)
   Author: [Your Name/Website Optional]
   Description: Sidebar main background changed to opaque Ruby.
                New custom gradient highlight effects for headings and paragraphs.
                Ensured highlight functionality. Button TOC pattern visibility enhanced AND MADE SCROLLABLE.
   JS Compatibility: Maintained.
   ========================================================================== */

/* --- Global Variables & Base Styles --- */
:root {
    /* Vedic Color Palette */
    --stoc-ruby-deep: #8A0000; /* गहरा माणिक */
        --stoc-ruby-deep-rgb: 138, 0, 0;
    --stoc-ruby-medium: #A70404;
        --stoc-ruby-medium-rgb: 167, 4, 4;
    --stoc-ruby-highlight: #D32F2F;
        --stoc-ruby-highlight-rgb: 211, 47, 47;

    --stoc-sidebar-main-bg: var(--stoc-ruby-deep);

    --stoc-pink-very-deep: #A0144F;
        --stoc-pink-very-deep-rgb: 160, 20, 79;
    --stoc-pink-medium: #C2185B;
        --stoc-pink-medium-rgb: 194, 24, 91;
    --stoc-pink-light: #F48FB1; /* हल्का गुलाबी */
        --stoc-pink-light-rgb: 244, 143, 177;


    --stoc-saffron-dark: #E69100;
        --stoc-saffron-dark-rgb: 230, 145, 0;
    --stoc-saffron-medium: #FFA000;
        --stoc-saffron-medium-rgb: 255, 160, 0;
    --stoc-saffron-light: #FFCA28;
        --stoc-saffron-light-rgb: 255, 202, 40;
    --stoc-saffron-pale: #FFF3E0; /* बहुत हल्का केसरिया */
        --stoc-saffron-pale-rgb: 255, 243, 224;

    --stoc-gold-text: #FFD700;
        --stoc-gold-text-rgb: 255, 215, 0;
    --stoc-gold-rich-text: #FFD700;
    --stoc-gold-deep-text: #B8860B;
        --stoc-gold-deep-text-rgb: 184, 134, 11;
    --stoc-gold-border: #FFB300;
        --stoc-gold-border-rgb: 255, 179, 0;
    --stoc-gold-highlight: #FFEE58;
        --stoc-gold-highlight-rgb: 255, 238, 88;
    --stoc-gold-pale: #FFF8E1;
        --stoc-gold-pale-rgb: 255, 248, 225;

    --stoc-ivory: #FFFFF0; /* हाथीदांत */
        --stoc-ivory-rgb: 255, 255, 240;

    /* पैटर्न के रंग (v4.9 बटन TOC के लिए) - अब प्रभावी अल्फा मान */
    --stoc-button-toc-pattern-dot-effective: rgba(var(--stoc-gold-text-rgb), 0.2); /* मूल 0.25 * 0.8 ओपेसिटी */
    --stoc-button-toc-pattern-dot-strong-effective: rgba(var(--stoc-gold-text-rgb), 0.32); /* मूल 0.4 * 0.8 ओपेसिटी */


    /* साइडबार पैटर्न अब रूबी बैकग्राउंड पर, रंग समायोजित */
    --stoc-sidebar-pattern-color1: rgba(var(--stoc-gold-text-rgb), 0.18);
    --stoc-sidebar-pattern-color2: rgba(var(--stoc-gold-text-rgb), 0.12);


    --stoc-copper: #A1887F;
        --stoc-copper-rgb: 161, 136, 127;
    --stoc-text-glow: rgba(255, 223, 186, 0.25);

    /* Text & Background */
    --stoc-text-light-on-dark: #FFFDE7;
    --stoc-text-dark-on-light: #4E342E;
    --stoc-border-color-light: #FFCC80;

    /* साइडबार आइटम डिज़ाइन (नया v5.8) */
    --stoc-sidebar-item-bg-base: rgba(0, 0, 0, 0.15);
    --stoc-sidebar-item-bg-hover: rgba(0, 0, 0, 0.25);
    --stoc-sidebar-item-border: rgba(var(--stoc-gold-text-rgb), 0.3);
    --stoc-sidebar-item-border-hover: rgba(var(--stoc-gold-highlight-rgb), 0.6);
    --stoc-sidebar-text-shadow: 0 1px 2px rgba(0, 0, 0, 0.7), 0 0 8px rgba(var(--stoc-gold-text-rgb),0.3);


    /* Typography */
    --stoc-font-main: 'Laila', 'Noto Sans Devanagari', serif;
    --stoc-font-heading: 'Martel', 'Noto Serif Devanagari', serif;

    /* Dimensions & Radius */
    --stoc-border-radius: 10px;
    --stoc-item-border-radius: 8px;
    --stoc-sidebar-inner-item-radius: 7px;
    --stoc-sidebar-width: 295px;
    --stoc-button-box-max-height-expanded: 380px;

    /* Transitions & Animations */
    --stoc-transition-fast: 0.2s ease-in-out;
    --stoc-transition-medium: 0.35s cubic-bezier(0.68, -0.55, 0.265, 1.55);
    --stoc-transition-reveal: 0.5s cubic-bezier(0.165, 0.84, 0.44, 1);

    /* Highlight Effect */
    --stoc-highlight-duration: 2.8s;
    --stoc-popup-highlight-duration: 2.8s; /* JS इस वेरिएबल का उपयोग करता है */

    --stoc-scroll-indicator-color: var(--stoc-gold-text);
    --stoc-sidebar-scroll-indicator-color: var(--stoc-gold-text);
}

/* Google Fonts Import */
@import url('https://fonts.googleapis.com/css2?family=Laila:wght@400;600;700&family=Martel:wght@600;700;800&family=Noto+Sans+Devanagari:wght@400;600&family=Noto+Serif+Devanagari:wght@600;700&display=swap');

/* Base element reset */
#stoc-toc-button-wrapper *,
#stoc-floating-toc-icon *,
#stoc-toc-icon-sidebar * {
    box-sizing: border-box;
    line-height: 1.5;
}
#stoc-toc-button-list,
#stoc-toc-icon-sidebar-list {
    line-height: 1.45;
}

/* --- Collapsible Button TOC (Revised Design - v4.9 style) --- */
#stoc-toc-button-wrapper {
    margin-bottom: 25px;
    position: relative;
    border-radius: var(--stoc-border-radius);
    background: linear-gradient(140deg, var(--stoc-ruby-deep) 0%, var(--stoc-ruby-medium) 50%, var(--stoc-pink-medium) 100%);
    border: 2.5px solid var(--stoc-gold-border);
    box-shadow: 0 6px 20px rgba(80, 0, 0, 0.45),
                inset 0 0 15px rgba(255, 100, 100, 0.25),
                0 0 0 1.5px var(--stoc-ruby-deep);
    transition: box-shadow var(--stoc-transition-medium), transform var(--stoc-transition-medium);
    overflow: hidden;
}
#stoc-toc-button-wrapper:hover {
    box-shadow: 0 8px 28px rgba(80, 0, 0, 0.6),
                inset 0 0 20px rgba(255, 120, 120, 0.35),
                0 0 0 1.5px var(--stoc-ruby-deep);
    transform: translateY(-3px) scale(1.01);
}
#stoc-toc-button-wrapper::before {
    content: '';
    position: absolute;
    top: 4px; left: 4px; right: 4px; bottom: 4px;
    border-radius: calc(var(--stoc-border-radius) - 5px);
    border: 1.5px dotted var(--stoc-gold-text);
    opacity: 0.6;
    pointer-events: none;
    z-index: 1;
}

#stoc-toc-button-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 12px 18px;
    cursor: pointer;
    color: var(--stoc-gold-text);
    user-select: none;
    position: relative;
    z-index: 3;
    background-color: transparent;
    text-shadow: 0 1px 4px rgba(0, 0, 0, 0.6);
    transition: background-color var(--stoc-transition-fast);
}
#stoc-toc-button-header:hover {
    background-color: rgba(0,0,0,0.1);
}

#stoc-toc-button-header h3 {
    margin: 0;
    font-family: var(--stoc-font-heading);
    font-size: 1.35em;
    font-weight: 700;
    display: flex;
    align-items: center;
    gap: 10px;
}

#stoc-toc-button-header h3 .fa-book-open {
    color: var(--stoc-gold-text);
    font-size: 1.2em;
    filter: drop-shadow(0 0 5px var(--stoc-gold-text));
    transition: transform var(--stoc-transition-medium), color var(--stoc-transition-fast);
}
#stoc-toc-button-header:hover h3 .fa-book-open {
    transform: rotate(10deg) scale(1.1);
    color: var(--stoc-gold-highlight);
}

.stoc-toc-button-title-text {
    font-weight: 700;
    letter-spacing: 0.5px;
    font-size: 0.85em;
    color: var(--stoc-gold-text);
    padding: 2px 0;
    text-transform: uppercase;
}

.stoc-toc-open-prompt-icon {
    font-size: 1.1em;
    color: var(--stoc-gold-text);
    opacity: 0.7;
    margin-left: 10px;
    transition: opacity var(--stoc-transition-fast) 0.2s, transform var(--stoc-transition-fast);
    transform: translateX(-5px);
}
#stoc-toc-button-wrapper.collapsed .stoc-toc-open-prompt-icon {
    opacity: 1;
    transform: translateX(0);
    animation: stoc-prompt-pulse 2s infinite ease-in-out 0.5s;
}
@keyframes stoc-prompt-pulse {
    0%, 100% { transform: scale(1) translateX(0); opacity: 0.7; }
    50% { transform: scale(1.15) translateX(0); opacity: 1; }
}

#stoc-toc-button-toggle-icon {
    font-size: 1.6em;
    color: var(--stoc-gold-text);
    transition: transform var(--stoc-transition-medium) 0.1s, color var(--stoc-transition-fast);
    padding: 4px;
    border-radius: 50%;
}
#stoc-toc-button-header:hover #stoc-toc-button-toggle-icon {
    color: var(--stoc-gold-highlight);
    background-color: rgba(255, 215, 0, 0.1);
}
#stoc-toc-button-wrapper.collapsed #stoc-toc-button-toggle-icon { transform: rotate(0deg); }
#stoc-toc-button-wrapper.expanded #stoc-toc-button-toggle-icon { transform: rotate(-180deg); }

#stoc-toc-button-scrollbox {
    max-height: 0;
    overflow: hidden; /* Important for collapse/expand animation */
    padding: 0 10px;
    position: relative;
    z-index: 2;
    opacity: 0;
    
    /* MODIFIED: Pattern applied as multi-layer background for scrollability */
    background:
        /* Layer 1: Pattern dot 1 (topmost pattern layer) */
        radial-gradient(var(--stoc-button-toc-pattern-dot-effective) 1px, transparent 1.2px) 0 0 / 12px 12px repeat local,
        /* Layer 2: Pattern dot 2 */
        radial-gradient(var(--stoc-button-toc-pattern-dot-strong-effective) 0.8px, transparent 1px) 4px 4px / 8px 8px repeat local,
        /* Layer 3: Base background color (bottommost layer) */
        var(--stoc-saffron-dark);

    box-shadow: inset 0 6px 15px rgba(0,0,0,0.3), inset 0 -4px 10px rgba(0,0,0,0.2);
    transform: perspective(600px) rotateX(-90deg) translateY(-50%);
    transform-origin: top center;
    transition: max-height var(--stoc-transition-reveal) 0.05s,
                padding var(--stoc-transition-reveal) 0.05s,
                opacity calc(var(--stoc-transition-reveal) * 0.6) ease-in 0.15s,
                transform var(--stoc-transition-reveal) cubic-bezier(0.23, 1, 0.32, 1),
                visibility 0s linear calc(var(--stoc-transition-reveal) * 0.8);
    border-top: 1px solid rgba(255,255,255,0.15);
    visibility: hidden;
}

/* REMOVED: #stoc-toc-button-scrollbox::before rule as pattern is now direct background */

#stoc-toc-button-wrapper.expanded #stoc-toc-button-scrollbox {
    max-height: var(--stoc-button-box-max-height-expanded);
    padding: 15px 10px;
    opacity: 1;
    transform: perspective(600px) rotateX(0deg) translateY(0%);
    overflow-y: auto; /* This enables scrolling */
    visibility: visible;
    transition-delay: 0s, 0s, 0s, 0s, 0s;
}

#stoc-toc-button-list {
    list-style: none;
    padding: 0 5px;
    margin: 0;
    position: relative; /* Kept for potential future use or if child elements need it */
    z-index: 1; /* Ensures list items are above the scrollbox's direct background if needed, though usually not necessary for direct bg */
}

/* --- बटन TOC लिस्ट आइटम (v4.9 style) --- */
#stoc-toc-button-scrollbox .stoc-toc-list-item {
    margin-bottom: 6px;
    border-radius: 6px;
    background: transparent;
    padding: 0;
    box-shadow: none;
    animation: none;
    border: 1px solid rgba(var(--stoc-pink-very-deep-rgb), 0.2);
}
#stoc-toc-button-scrollbox .stoc-toc-list-item:hover {
    border-color: rgba(var(--stoc-pink-very-deep-rgb), 0.4);
}

#stoc-toc-button-scrollbox .stoc-toc-list-item a {
    display: flex;
    align-items: flex-start;
    gap: 10px;
    padding: 8px 10px;
    text-decoration: none;
    border-radius: 5px;
    background-color: rgba(255, 255, 255, 0.07);
    transition: background-color var(--stoc-transition-fast), transform 0.15s ease-out;
}
#stoc-toc-button-scrollbox .stoc-toc-list-item a:hover {
    background-color: rgba(255, 255, 255, 0.15);
    transform: translateX(2px);
}
#stoc-toc-button-scrollbox .stoc-toc-list-item a.stoc-toc-link-clicked {
    background-color: rgba(var(--stoc-pink-very-deep-rgb),0.1);
    transform: translateX(2px) scale(1.01);
}

#stoc-toc-button-scrollbox .stoc-toc-list-item .stoc-toc-item-icon {
    margin-top: 2px;
    font-size: 0.9em;
    width: 1.2em;
    text-align: center;
    color: var(--stoc-pink-medium);
    flex-shrink: 0;
    transition: color var(--stoc-transition-fast);
}
#stoc-toc-button-scrollbox .stoc-toc-list-item a:hover .stoc-toc-item-icon,
#stoc-toc-button-scrollbox .stoc-toc-list-item a.stoc-toc-link-clicked .stoc-toc-item-icon {
    color: var(--stoc-pink-very-deep);
}

#stoc-toc-button-scrollbox .stoc-toc-list-item .stoc-toc-item-text {
    flex-grow: 1;
    font-size: 0.92em;
    line-height: 1.45;
    font-weight: 600;
    font-family: var(--stoc-font-main);
    color: var(--stoc-pink-very-deep);
    background-image: none;
    -webkit-background-clip: initial; -webkit-text-fill-color: initial;
    background-clip: initial; text-fill-color: initial;
}

#stoc-toc-button-scrollbox .stoc-toc-list-item.level-2 a { font-weight: 700; font-size: 0.95em; }
#stoc-toc-button-scrollbox .stoc-toc-list-item.level-3 { padding-left: 12px; }
#stoc-toc-button-scrollbox .stoc-toc-list-item.level-3 a { font-size: 0.9em; }
#stoc-toc-button-scrollbox .stoc-toc-list-item.level-4 { padding-left: 24px; }
#stoc-toc-button-scrollbox .stoc-toc-list-item.level-4 a { font-size: 0.88em; }


/* --- Floating TOC Icon & Sidebar (v5.8 style) --- */
#stoc-floating-toc-icon {
    position: fixed; top: 50%; right: -75px; transform: translateY(-50%);
    width: 55px; height: 55px;
    background: linear-gradient(145deg, var(--stoc-ruby-medium), var(--stoc-saffron-dark));
    color: var(--stoc-gold-highlight);
    border: 2.5px solid var(--stoc-gold-border);
    border-radius: 50%; font-size: 1.4em; cursor: pointer; z-index: 1001;
    box-shadow: 0 0 12px var(--stoc-saffron-medium), 0 0 20px var(--stoc-ruby-deep), inset 0 0 7px rgba(255,223,186,0.3);
    display: flex; align-items: center; justify-content: center;
    transition: right var(--stoc-transition-medium), transform var(--stoc-transition-medium),
                opacity var(--stoc-transition-medium) 0s, visibility 0s linear var(--stoc-transition-medium),
                background var(--stoc-transition-fast), box-shadow var(--stoc-transition-fast);
    opacity: 0; visibility: hidden;
    animation: stoc-float-gently 3.8s infinite ease-in-out;
}
#stoc-floating-toc-icon.visible {
    right: 22px; opacity: 1; visibility: visible;
    transition-delay: 0s, 0s, 0s, 0s, 0s, 0s;
}
#stoc-floating-toc-icon:hover {
    transform: translateY(-50%) scale(1.18) rotate(18deg);
    box-shadow: 0 0 18px var(--stoc-saffron-dark), 0 0 28px var(--stoc-ruby-deep), inset 0 0 10px rgba(255,223,186,0.4);
    border-color: var(--stoc-gold-highlight);
}
body.stoc-toc-sidebar-open #stoc-floating-toc-icon {
    right: calc(var(--stoc-sidebar-width) + 28px);
    transform: translateY(-50%) rotate(380deg);
    background: linear-gradient(145deg, var(--stoc-saffron-light), var(--stoc-gold-text));
    border-color: var(--stoc-ruby-deep);
}
@keyframes stoc-float-gently {
    0%, 100% { transform: translateY(-50%) rotate(-3deg); }
    50% { transform: translateY(-52%) rotate(5deg); }
}

#stoc-toc-icon-sidebar {
    position: fixed; top: 0; right: 0; width: var(--stoc-sidebar-width); height: 100vh;
    background-color: var(--stoc-sidebar-main-bg);
    box-shadow: -10px 0 30px rgba(var(--stoc-ruby-deep-rgb), 0.45);
    transform: translateX(100%);
    transition: transform var(--stoc-transition-reveal);
    z-index: 1010; display: flex; flex-direction: column; overflow: hidden;
    border-left: 5px solid;
    border-image: linear-gradient(to bottom,
                    var(--stoc-gold-highlight),
                    var(--stoc-saffron-medium) 30%,
                    var(--stoc-ruby-highlight) 60%,
                    var(--stoc-ruby-deep) 100%) 1;
    visibility: hidden;
}
#stoc-toc-icon-sidebar::before {
    content: ""; position: absolute; top: 0; left: 0; right: 0; bottom: 0;
    background-image:
        radial-gradient(ellipse 50% 80% at 20% 25%, transparent 40%, var(--stoc-sidebar-pattern-color1) 41%, var(--stoc-sidebar-pattern-color1) 45%, transparent 46%),
        radial-gradient(ellipse 50% 80% at 80% 75%, transparent 40%, var(--stoc-sidebar-pattern-color1) 41%, var(--stoc-sidebar-pattern-color1) 45%, transparent 46%),
        repeating-linear-gradient(
            30deg,
            var(--stoc-sidebar-pattern-color2),
            var(--stoc-sidebar-pattern-color2) 1px,
            transparent 1px,
            transparent 12px
        ),
        repeating-linear-gradient(
            -30deg,
            var(--stoc-sidebar-pattern-color2),
            var(--stoc-sidebar-pattern-color2) 1px,
            transparent 1px,
            transparent 12px
        );
    background-size: 100px 100px, 100px 100px, 24px 24px, 24px 24px;
    background-position: 0 0, 50px 50px, 0 0, 0 0;
    background-repeat: repeat;
    opacity: 0.6;
    pointer-events: none;
    mix-blend-mode: screen;
    z-index: 0;
}
#stoc-toc-icon-sidebar > * { position: relative; z-index: 1; }

#stoc-toc-icon-sidebar.visible {
    transform: translateX(0); visibility: visible;
}

#stoc-toc-icon-sidebar-header {
    padding: 18px 55px 18px 22px;
    border-bottom: 1.5px solid rgba(var(--stoc-gold-border-rgb), 0.4);
    flex-shrink: 0; position: relative;
    background: linear-gradient(135deg, rgba(0,0,0,0.05), rgba(0,0,0,0.15));
}
#stoc-toc-icon-sidebar-header h3 {
    margin: 0; font-family: var(--stoc-font-heading); font-size: 1.3em;
    font-weight: 700; text-align: center; color: var(--stoc-gold-text);
    text-shadow: 0 1px 3px rgba(0,0,0,0.6);
}
#stoc-toc-sidebar-internal-close {
    position: absolute; top: 50%; right: 15px; transform: translateY(-50%);
    background: none; border: none; width: 36px; height: 36px; font-size: 1.4em;
    color: var(--stoc-gold-text); cursor: pointer; display: flex; justify-content: center;
    align-items: center; border-radius: 50%;
    transition: background-color var(--stoc-transition-fast), color var(--stoc-transition-fast), transform var(--stoc-transition-medium);
    opacity: 0.85;
}
#stoc-toc-sidebar-internal-close:hover {
    background-color: rgba(var(--stoc-gold-highlight-rgb), 0.2);
    color: var(--stoc-gold-highlight);
    transform: translateY(-50%) rotate(180deg) scale(1.1);
    opacity: 1;
}
#stoc-toc-icon-sidebar-scrollbox {
    flex-grow: 1; overflow-y: auto;
    padding: 15px 8px 15px 15px;
    position: relative;
}
#stoc-toc-icon-sidebar-list {
    list-style: none; padding: 0 0 12vh 0; margin: 0;
}

#stoc-toc-icon-sidebar .stoc-toc-list-item {
    margin-bottom: 7px;
    border-radius: var(--stoc-sidebar-inner-item-radius);
    padding: 0;
    background: none;
    animation: none;
    box-shadow: none;
    overflow: hidden;
}

#stoc-toc-icon-sidebar .stoc-toc-list-item a {
    display: flex;
    align-items: center;
    gap: 12px;
    padding: 11px 15px;
    text-decoration: none;
    border-radius: var(--stoc-sidebar-inner-item-radius);
    background-color: var(--stoc-sidebar-item-bg-base);
    border: 1px solid var(--stoc-sidebar-item-border);
    box-shadow: inset 0 0 8px rgba(0,0,0,0.2), 0 1px 2px rgba(0,0,0,0.1);
    transition: all var(--stoc-transition-fast);
    position: relative;
    z-index: 1;
}

#stoc-toc-icon-sidebar .stoc-toc-list-item a:hover {
    background-color: var(--stoc-sidebar-item-bg-hover);
    border-color: var(--stoc-sidebar-item-border-hover);
    transform: translateY(-1px) scale(1.01);
    box-shadow: inset 0 0 10px rgba(0,0,0,0.3), 0 2px 4px rgba(var(--stoc-gold-text-rgb),0.15);
}

#stoc-toc-icon-sidebar .stoc-toc-list-item a.stoc-toc-link-clicked {
    background-color: rgba(0,0,0,0.3);
    border-color: var(--stoc-gold-highlight);
    transform: scale(1);
    box-shadow: inset 0 0 12px rgba(0,0,0,0.4);
}


#stoc-toc-icon-sidebar .stoc-toc-list-item .stoc-toc-item-icon {
    font-size: 0.95em;
    width: 1.25em;
    line-height: 1;
    text-align: center;
    opacity: 1;
    flex-shrink: 0;
    color: var(--stoc-gold-text);
    transition: color var(--stoc-transition-fast), transform var(--stoc-transition-fast);
    text-shadow: 0 0 5px rgba(var(--stoc-gold-text-rgb), 0.5);
}
#stoc-toc-icon-sidebar .stoc-toc-list-item a:hover .stoc-toc-item-icon {
    color: var(--stoc-gold-highlight);
    transform: scale(1.15) rotate(5deg);
}

#stoc-toc-icon-sidebar .stoc-toc-list-item .stoc-toc-item-text {
    flex-grow: 1;
    font-size: 0.96em;
    line-height: 1.55;
    font-weight: 600;
    font-family: var(--stoc-font-main);
    white-space: normal;
    word-break: break-word;
    color: var(--stoc-gold-rich-text);
    text-shadow: var(--stoc-sidebar-text-shadow);
    letter-spacing: 0.15px;
    background-image: none; -webkit-background-clip: initial; -webkit-text-fill-color: initial; background-clip: initial; text-fill-color: initial;
}

#stoc-toc-icon-sidebar .stoc-toc-list-item.level-2 a {
    background-color: rgba(0,0,0,0.2);
    border-left: 4px solid var(--stoc-gold-border);
    padding-left: 12px;
}
#stoc-toc-icon-sidebar .stoc-toc-list-item.level-2 .stoc-toc-item-text {
    font-size: 0.94em;
    font-weight: 700;
    color: var(--stoc-gold-highlight);
}
#stoc-toc-icon-sidebar .stoc-toc-list-item.level-2 .stoc-toc-item-icon {
    color: var(--stoc-gold-border);
    font-size: 1em;
}

#stoc-toc-icon-sidebar .stoc-toc-list-item.level-3 { padding-left: 12px; }
#stoc-toc-icon-sidebar .stoc-toc-list-item.level-3 a {
    background-color: rgba(0,0,0,0.12);
    border-left: 3px solid var(--stoc-saffron-medium);
    padding-left: 10px;
}
#stoc-toc-icon-sidebar .stoc-toc-list-item.level-3 .stoc-toc-item-text {
    font-size: 0.92em;
    font-weight: 500;
}
#stoc-toc-icon-sidebar .stoc-toc-list-item.level-3 .stoc-toc-item-icon {
    color: var(--stoc-saffron-medium);
    font-size: 0.9em;
}

#stoc-toc-icon-sidebar .stoc-toc-list-item.level-4 { padding-left: 24px; }
#stoc-toc-icon-sidebar .stoc-toc-list-item.level-4 a {
    background-color: rgba(0,0,0,0.1);
    border-left: 2px solid var(--stoc-saffron-light);
    padding-left: 8px;
}
#stoc-toc-icon-sidebar .stoc-toc-list-item.level-4 .stoc-toc-item-text {
    font-size: 0.9em;
    font-weight: 400;
}
#stoc-toc-icon-sidebar .stoc-toc-list-item.level-4 .stoc-toc-item-icon {
    color: var(--stoc-saffron-light);
    font-size: 0.88em;
}

#stoc-toc-sidebar-external-close {
    position: fixed; top: 50%; left: -65px;
    transform: translateY(-50%) scale(0.85);
    width: 42px; height: 42px;
    background: linear-gradient(135deg, var(--stoc-ruby-highlight), var(--stoc-saffron-dark));
    border: none; border-radius: 50%; color: var(--stoc-gold-highlight);
    font-size: 1.35em; cursor: pointer;
    box-shadow: 0 6px 18px rgba(var(--stoc-ruby-deep-rgb), 0.45);
    z-index: 1011; display: flex; justify-content: center; align-items: center;
    opacity: 0; visibility: hidden;
    transition: all var(--stoc-transition-medium);
}
#stoc-toc-sidebar-external-close.visible {
    opacity: 1; visibility: visible; left: 20px;
    transform: translateY(-50%) scale(1);
}
#stoc-toc-sidebar-external-close:hover {
    transform: translateY(-50%) scale(1.15) rotate(-18deg);
    box-shadow: 0 9px 25px rgba(var(--stoc-ruby-deep-rgb), 0.6);
}


/* --- साझा स्क्रॉल इंडिकेटर --- */
.stoc-toc-scroll-indicator {
    position: absolute; bottom: 10px; left: 50%; transform: translateX(-50%);
    font-size: 1.6em; opacity: 0; pointer-events: none;
    text-shadow: 0 0 8px rgba(255,255,255,0.3);
    animation: stoc-bounce-pulse-vedic 2s infinite ease-in-out;
    transition: opacity 0.4s ease; z-index: 5;
    visibility: hidden;
}
#stoc-toc-button-scrollbox .stoc-toc-scroll-indicator { color: var(--stoc-scroll-indicator-color); }
#stoc-toc-icon-sidebar-scrollbox .stoc-toc-scroll-indicator { color: var(--stoc-sidebar-scroll-indicator-color); }

.stoc-toc-scroll-indicator.visible { opacity: 0.85 !important; visibility: visible !important; }

@keyframes stoc-bounce-pulse-vedic {
    0%, 100% { transform: translate(-50%, 0px) scale(1); opacity: 0.7; }
    50% { transform: translate(-50%, -6px) scale(1.05); opacity: 1; }
}

/* --- Custom Scrollbars --- */
#stoc-toc-button-scrollbox::-webkit-scrollbar,
#stoc-toc-icon-sidebar-scrollbox::-webkit-scrollbar { width: 6px; }

#stoc-toc-button-scrollbox::-webkit-scrollbar-track,
#stoc-toc-icon-sidebar-scrollbox::-webkit-scrollbar-track { background: rgba(0,0,0,0.1); border-radius: 3px; }

#stoc-toc-button-scrollbox::-webkit-scrollbar-thumb { background: var(--stoc-gold-border); border-radius: 3px; }
#stoc-toc-icon-sidebar-scrollbox::-webkit-scrollbar-thumb { background: var(--stoc-saffron-medium); border-radius: 3px; }

#stoc-toc-button-scrollbox,
#stoc-toc-icon-sidebar-scrollbox {
    scrollbar-width: thin;
}
#stoc-toc-button-scrollbox { scrollbar-color: var(--stoc-gold-border) rgba(0,0,0,0.1); }
#stoc-toc-icon-sidebar-scrollbox { scrollbar-color: var(--stoc-saffron-medium) rgba(0,0,0,0.1); }


/* --- कंटेंट हाइलाइटिंग (नया कस्टम डिज़ाइन) --- */
@keyframes stoc-highlight-heading-custom {
  0% {
    color: var(--stoc-ruby-deep) !important;
    text-shadow: 0 0 3px var(--stoc-gold-pale),
                 0 0 6px var(--stoc-gold-text),
                 0 0 12px var(--stoc-saffron-light);
    transform: scale(1.02) translateY(-1px);
    opacity: 0.8;
  }
  50% {
    color: var(--stoc-pink-medium) !important;
    text-shadow: 0 0 5px var(--stoc-gold-highlight),
                 0 0 10px var(--stoc-gold-text),
                 0 0 20px var(--stoc-saffron-medium),
                 0 0 30px var(--stoc-ruby-highlight);
    transform: scale(1.06) translateY(-2px);
    opacity: 1;
  }
  100% {
    color: var(--stoc-ruby-deep) !important;
    text-shadow: 0 0 3px var(--stoc-gold-pale),
                 0 0 6px var(--stoc-gold-text),
                 0 0 12px var(--stoc-saffron-light);
    transform: scale(1.02) translateY(-1px);
    opacity: 0.8;
  }
}

@keyframes stoc-highlight-paragraph-custom {
  0% {
    background: linear-gradient(135deg, rgba(var(--stoc-saffron-pale-rgb), 0.4), rgba(var(--stoc-gold-pale-rgb), 0.3)) !important;
    box-shadow: 0 0 10px rgba(var(--stoc-saffron-medium-rgb), 0.25),
                inset 0 0 8px rgba(var(--stoc-gold-text-rgb), 0.2),
                0 0 0 1px rgba(var(--stoc-gold-border-rgb), 0.4) !important;
    transform: scale(1.005);
  }
  50% {
    background: linear-gradient(135deg, rgba(var(--stoc-saffron-light-rgb), 0.6), rgba(var(--stoc-gold-highlight-rgb), 0.45)) !important;
    box-shadow: 0 0 20px rgba(var(--stoc-saffron-dark-rgb), 0.4),
                inset 0 0 15px rgba(var(--stoc-gold-highlight-rgb), 0.3),
                0 0 0 2px var(--stoc-gold-border) !important;
    transform: scale(1.015);
  }
  100% {
    background: linear-gradient(135deg, rgba(var(--stoc-saffron-pale-rgb), 0.4), rgba(var(--stoc-gold-pale-rgb), 0.3)) !important;
    box-shadow: 0 0 10px rgba(var(--stoc-saffron-medium-rgb), 0.25),
                inset 0 0 8px rgba(var(--stoc-gold-text-rgb), 0.2),
                0 0 0 1px rgba(var(--stoc-gold-border-rgb), 0.4) !important;
    transform: scale(1.005);
  }
}

.post-body :is(h1,h2,h3,h4,h5,h6).stoc-toc-target-heading.stoc-highlight-active {
    position: relative !important;
    padding: 3px 6px !important;
    margin: -3px -6px !important;
    border-radius: 5px !important;
    animation: stoc-highlight-heading-custom var(--stoc-highlight-duration) ease-in-out forwards !important;
    will-change: color, text-shadow, transform, opacity;
    background: transparent !important;
}

.post-body .stoc-toc-target-paragraph.stoc-highlight-active {
    position: relative !important;
    border-radius: var(--stoc-border-radius) !important;
    padding: 12px !important;
    margin: 8px -12px !important;
    animation: stoc-highlight-paragraph-custom var(--stoc-highlight-duration) ease-in-out forwards !important;
    will-change: background, box-shadow, transform;
    border: none !important;
}

.stoc-toc-target-heading.fading-out,
.stoc-toc-target-paragraph.fading-out {
    animation: none !important;
    transition: color 0.4s ease-out, text-shadow 0.4s ease-out, transform 0.4s ease-out,
                opacity 0.4s ease-out, background 0.4s ease-out, box-shadow 0.4s ease-out,
                padding 0.4s ease-out, margin 0.4s ease-out, border-radius 0.4s ease-out,
                border 0.4s ease-out !important;
    color: inherit !important;
    text-shadow: none !important;
    transform: scale(1) translateY(0) !important;
    opacity: 1 !important;
    background: transparent !important;
    box-shadow: none !important;
    border: none !important;
    border-radius: 0 !important;
}
.stoc-toc-target-paragraph.fading-out {
    padding: 0 !important;
    margin: 0 0 1em 0 !important;
}
.stoc-toc-target-heading.fading-out {
    padding: 0 !important;
    margin: 0 !important;
}


/* --- Responsive --- */
@media (max-width: 768px) {
    :root {
        --stoc-sidebar-width: clamp(250px, 85vw, 290px);
    }

    #stoc-floating-toc-icon {
        width: 50px; height: 50px; font-size: 1.25em;
        right: 18px;
    }
    body.stoc-toc-sidebar-open #stoc-floating-toc-icon {
        right: calc(var(--stoc-sidebar-width) + 20px);
    }
    #stoc-toc-sidebar-external-close {
        width: 38px; height: 38px; font-size: 1.25em; left: 15px;
    }
    #stoc-toc-sidebar-external-close.visible { left: 15px; }


    #stoc-toc-button-header h3 { font-size: 1.2em; }
    .stoc-toc-button-title-text { font-size: 0.8em; }
    #stoc-toc-button-toggle-icon { font-size: 1.4em; }

    #stoc-toc-icon-sidebar-header h3 { font-size: 1.15em; }

    #stoc-toc-button-scrollbox .stoc-toc-list-item a { padding: 7px 8px; }
    #stoc-toc-button-scrollbox .stoc-toc-list-item .stoc-toc-item-text { font-size: 0.9em; }
    #stoc-toc-button-scrollbox .stoc-toc-list-item.level-3 { padding-left: 10px; }
    #stoc-toc-button-scrollbox .stoc-toc-list-item.level-4 { padding-left: 20px; }

    #stoc-toc-icon-sidebar .stoc-toc-list-item a { padding: 9px 12px; }
    #stoc-toc-icon-sidebar .stoc-toc-list-item .stoc-toc-item-text { font-size: 0.92em; }
    #stoc-toc-icon-sidebar .stoc-toc-list-item.level-2 .stoc-toc-item-text { font-size: 0.91em; }
    #stoc-toc-icon-sidebar .stoc-toc-list-item.level-3 { padding-left: 10px; }
    #stoc-toc-icon-sidebar .stoc-toc-list-item.level-3 .stoc-toc-item-text { font-size: 0.89em; }
    #stoc-toc-icon-sidebar .stoc-toc-list-item.level-4 { padding-left: 20px; }
    #stoc-toc-icon-sidebar .stoc-toc-list-item.level-4 .stoc-toc-item-text { font-size: 0.87em; }

    .post-body .stoc-toc-target-paragraph.stoc-highlight-active {
        padding: 10px !important; margin-left: -10px !important; margin-right: -10px !important;
    }
    .post-body :is(h1,h2,h3,h4,h5,h6).stoc-toc-target-heading.stoc-highlight-active {
        padding: 2px 5px !important; margin: -2px -5px !important;
    }
}

/* एक्सेसिबिलिटी: कम मोशन प्राथमिकता */
@media (prefers-reduced-motion: reduce) {
    *, *::before, *::after {
        animation-duration: 0.01ms !important;
        animation-iteration-count: 1 !important;
        transition-duration: 0.01ms !important;
        scroll-behavior: auto !important;
        transition-delay: 0ms !important;
    }

    .stoc-toc-open-prompt-icon,
    #stoc-floating-toc-icon,
    .stoc-toc-target-heading.stoc-highlight-active,
    .stoc-toc-target-paragraph.stoc-highlight-active,
    .stoc-toc-scroll-indicator,
    #stoc-toc-sidebar-internal-close,
    #stoc-toc-sidebar-external-close {
        animation: none !important;
    }

    #stoc-toc-button-toggle-icon { transition: transform 0.01ms !important; }
    #stoc-toc-button-wrapper.collapsed #stoc-toc-button-toggle-icon { transform: rotate(0deg); }
    #stoc-toc-button-wrapper.expanded #stoc-toc-button-toggle-icon { transform: rotate(-180deg); }

    #stoc-toc-button-scrollbox { transition: max-height 0.01ms, padding 0.01ms, opacity 0.01ms, transform 0.01ms !important; }
    #stoc-toc-icon-sidebar { transition: transform 0.01ms !important; }
    #stoc-toc-sidebar-external-close { transition: opacity 0.01ms, visibility 0.01ms, transform 0.01ms, left 0.01ms !important; }

    #stoc-floating-toc-icon:hover,
    #stoc-toc-button-header:hover,
    #stoc-toc-button-wrapper:hover,
    #stoc-toc-sidebar-external-close:hover,
    #stoc-toc-icon-sidebar .stoc-toc-list-item a:hover,
    #stoc-toc-button-scrollbox .stoc-toc-list-item a:hover {
        transform: none !important;
    }
    #stoc-toc-button-header:hover { background-color: rgba(0,0,0,0.05) !important; }
    #stoc-toc-button-scrollbox .stoc-toc-list-item a:hover { background-color: rgba(255, 255, 255, 0.12) !important; }
    #stoc-toc-icon-sidebar .stoc-toc-list-item a:hover { background-color: rgba(0,0,0,0.22) !important; }
    #stoc-toc-sidebar-internal-close:hover { background-color: rgba(var(--stoc-gold-highlight-rgb),0.15) !important; color: var(--stoc-gold-highlight) !important; }
}


/* --- पोस्ट कंटेंट हेडिंग्स के लिए बेसिक स्टाइल --- */
.post-body :is(h1, h2, h3, h4, h5, h6) {
    font-family: var(--stoc-font-heading);
    scroll-margin-top: 80px; /* हेडर की ऊँचाई के आधार पर समायोजित करें */
    padding-top: 5px; padding-bottom: 5px;
}

/* --- End of Vedic Bloom TOC CSS (v5.8.3 - Scrollable Button Pattern Fix) --- */
/* ======================================== */
/* === Widget खोजें और सीखें=== */
/* ======================================== */
h2.vsw-page-title{text-align:center;padding:15px;background:linear-gradient(to right,#3498db,#9b59b6);color:#fff;margin:0 0 20px 0;width:100%;box-sizing:border-box;font-size:1.8em}#vsw-main-widget{background-color:#0a192f;padding:25px;margin:0 auto 20px auto;max-width:1800px;width:95%;box-sizing:border-box;border:10px solid transparent;border-radius:25px;background-clip:padding-box;position:relative;animation:vsw_shinyBorder 6s infinite linear;box-shadow:0 10px 30px rgba(0,0,0,.4);-webkit-mask-image:radial-gradient(white,black);overflow:hidden}@-webkit-keyframes vsw_shinyBorder{0%{border-image-source:linear-gradient(45deg,#ff00ff,#00ffff,#ffff00);border-image-slice:1}25%{border-image-source:linear-gradient(135deg,#ff00ff,#00ffff,#ffff00);border-image-slice:1}50%{border-image-source:linear-gradient(225deg,#ff00ff,#00ffff,#ffff00);border-image-slice:1}75%{border-image-source:linear-gradient(315deg,#ff00ff,#00ffff,#ffff00);border-image-slice:1}100%{border-image-source:linear-gradient(405deg,#ff00ff,#00ffff,#ffff00);border-image-slice:1}}@keyframes vsw_shinyBorder{0%{border-image-source:linear-gradient(45deg,#ff00ff,#00ffff,#ffff00);border-image-slice:1}25%{border-image-source:linear-gradient(135deg,#ff00ff,#00ffff,#ffff00);border-image-slice:1}50%{border-image-source:linear-gradient(225deg,#ff00ff,#00ffff,#ffff00);border-image-slice:1}75%{border-image-source:linear-gradient(315deg,#ff00ff,#00ffff,#ffff00);border-image-slice:1}100%{border-image-source:linear-gradient(405deg,#ff00ff,#00ffff,#ffff00);border-image-slice:1}}.vsw-stylish-header-container{text-align:center;padding:15px;margin:0 auto 25px auto;max-width:95%;border-radius:10px;box-sizing:border-box}.vsw-stylish-header{font-size:1.6em;font-weight:bold;color:#e74c3c;text-shadow:2px 2px 5px rgba(255,255,255,.15),3px 3px 8px rgba(0,0,0,.6);animation:vsw_colorChange 5s infinite alternate,vsw_wobble 2.5s infinite ease-in-out}.vsw-stylish-description{font-size:1.15em;color:#5dade2;animation:vsw_fadeIn 2s ease-out,vsw_pulse 2.2s infinite alternate;line-height:1.5}@-webkit-keyframes vsw_wobble{0%,100%{transform:translateX(0) rotate(0)}15%{transform:translateX(-6px) rotate(-4deg)}30%{transform:translateX(4px) rotate(3deg)}45%{transform:translateX(-4px) rotate(-2deg)}60%{transform:translateX(3px) rotate(1.5deg)}75%{transform:translateX(-2px) rotate(-1deg)}}@keyframes vsw_wobble{0%,100%{transform:translateX(0) rotate(0)}15%{transform:translateX(-6px) rotate(-4deg)}30%{transform:translateX(4px) rotate(3deg)}45%{transform:translateX(-4px) rotate(-2deg)}60%{transform:translateX(3px) rotate(1.5deg)}75%{transform:translateX(-2px) rotate(-1deg)}}@-webkit-keyframes vsw_fadeIn{from{opacity:0}to{opacity:1}}@keyframes vsw_fadeIn{from{opacity:0}to{opacity:1}}@-webkit-keyframes vsw_colorChange{0%{color:#e74c3c}25%{color:#3498db}50%{color:#2ecc71}75%{color:#f1c40f}100%{color:#9b59b6}}@keyframes vsw_colorChange{0%{color:#e74c3c}25%{color:#3498db}50%{color:#2ecc71}75%{color:#f1c40f}100%{color:#9b59b6}}@-webkit-keyframes vsw_pulse{0%{transform:scale(1)}100%{transform:scale(1.03)}}@keyframes vsw_pulse{0%{transform:scale(1)}100%{transform:scale(1.03)}}.vsw-category-buttons{text-align:center;padding:20px 10px;background-color:rgba(255,255,255,.05);display:flex;flex-wrap:wrap;justify-content:center;gap:15px;border-radius:8px;transition:opacity .4s ease-in-out;opacity:1}.vsw-category-buttons.vsw-hidden{opacity:0}.vsw-category-buttons button{flex-grow:1;flex-basis:150px;max-width:200px;padding:12px 15px;height:48px;display:inline-flex;align-items:center;justify-content:center;font-size:1em;font-weight:bold;color:#fff;border:none;border-radius:8px;cursor:pointer;transition:background-color .3s ease,transform .15s ease,box-shadow .15s ease,border-bottom .15s ease;text-align:center;box-shadow:0 5px 8px rgba(0,0,0,.25),inset 0 -4px 2px rgba(0,0,0,.3);border-bottom:3px solid rgba(0,0,0,.4);position:relative;top:0}.vsw-category-buttons button:nth-child(1){background-color:#e74c3c;border-color:#a1332a}.vsw-category-buttons button:nth-child(2){background-color:#3498db;border-color:#2570a8}.vsw-category-buttons button:nth-child(3){background-color:#2ecc71;border-color:#1f9451}.vsw-category-buttons button:nth-child(4){background-color:#f39c12;border-color:#b5740e}.vsw-category-buttons button:nth-child(5){background-color:#9b59b6;border-color:#703c87}.vsw-category-buttons button:hover{transform:translateY(-3px) scale(1.02);box-shadow:0 8px 12px rgba(0,0,0,.3),inset 0 -2px 1px rgba(0,0,0,.2);top:-3px}.vsw-category-buttons button:active{transform:translateY(2px) scale(.98);box-shadow:0 1px 3px rgba(0,0,0,.2),inset 0 1px 2px rgba(0,0,0,.3);border-bottom:none;top:2px}#vsw-category-banner{background:linear-gradient(90deg,rgba(2,0,36,1) 0%,rgba(9,9,121,1) 35%,rgba(0,212,255,1) 100%);color:#fff;text-align:center;padding:12px 10px;margin:20px auto 25px auto;border-radius:8px;font-size:1.1em;font-weight:bold;letter-spacing:.5px;width:90%;max-width:600px;box-shadow:0 3px 8px rgba(0,0,0,.3);animation:vsw_bannerPulse 2s infinite alternate ease-in-out,vsw_fadeInBanner 1s ease-out;display:block;transition:opacity .4s ease-in-out;opacity:1}#vsw-category-banner.vsw-hidden{opacity:0}@-webkit-keyframes vsw_bannerPulse{0%{transform:scale(1);box-shadow:0 3px 8px rgba(0,0,0,.3)}100%{transform:scale(1.02);box-shadow:0 5px 15px rgba(0,212,255,.5)}}@keyframes vsw_bannerPulse{0%{transform:scale(1);box-shadow:0 3px 8px rgba(0,0,0,.3)}100%{transform:scale(1.02);box-shadow:0 5px 15px rgba(0,212,255,.5)}}@-webkit-keyframes vsw_fadeInBanner{from{opacity:0;transform:translateY(-10px)}to{opacity:1;transform:translateY(0)}}@keyframes vsw_fadeInBanner{from{opacity:0;transform:translateY(-10px)}to{opacity:1;transform:translateY(0)}}.vsw-search-category-container{padding:10px 0;width:100%;box-sizing:border-box;opacity:0;display:none;transition:opacity .4s ease-in-out}.vsw-search-category-container.vsw-active-search-box{opacity:1;max-height:2000px;overflow:visible}.vsw-search-box{max-width:95%;margin:10px auto 20px auto;padding:25px;border-radius:10px;box-shadow:0 4px 12px rgba(0,0,0,.4);text-align:center;color:#fff;transition:transform .4s ease,box-shadow .4s ease;min-height:280px;position:relative;box-sizing:border-box;display:flex;flex-direction:column;align-items:center;justify-content:center}#vsw-search-box-1{background:linear-gradient(45deg,#4285f4,#34a853,#fbbc05,#ea4335,#673ab7)}#vsw-search-box-2{background:linear-gradient(45deg,#e91e63,#9c27b0,#673ab7,#3f51b5,#2196f3)}#vsw-college-search-box{background:linear-gradient(45deg,#009688,#4caf50,#8bc34a,#cddc39,#ffeb3b)}#vsw-search-box-3{background:linear-gradient(45deg,#ff9800,#ff5722,#f44336,#e91e63,#9c27b0)}#vsw-news-search-box{background:linear-gradient(45deg,#607d8b,#795548,#9e9e9e,#455a64,#37474f)}.vsw-search-box:hover{transform:scale(1.02);box-shadow:0 6px 16px rgba(0,0,0,.5)}.vsw-search-box h3{font-size:1.5em;margin-bottom:20px;text-shadow:1px 1px 3px rgba(0,0,0,.5);font-weight:bold;color:#fff}.vsw-search-box select,.vsw-search-box input[type=text],.vsw-search-box button{width:90%;max-width:450px;padding:12px;margin-bottom:15px;border-radius:6px;border:1px solid #ccc;background-color:rgba(255,255,255,.95);color:#333;font-size:1.1em;font-weight:normal;box-sizing:border-box;display:block;margin-left:auto;margin-right:auto}.vsw-search-box button.vsw-back-button{background-color:#5a6268;color:#fff;margin-top:15px;font-size:.9em;text-transform:none;letter-spacing:normal;width:auto;max-width:200px;padding:8px 15px;display:inline-block;margin-bottom:0}.vsw-search-box button.vsw-back-button:hover{background-color:#4e555b}.vsw-search-box button.vsw-back-button:active{transform:scale(.98)}.vsw-search-box select{cursor:pointer}.vsw-search-box input[type=text]{cursor:text}.vsw-search-box button.vsw-search-button{background-color:#e74c3c;color:#fff;font-weight:bold;text-transform:uppercase;letter-spacing:.8px;border:none;cursor:pointer;transition:background-color .3s ease,transform .1s ease,opacity .3s ease;pointer-events:auto}.vsw-search-box button.vsw-search-button:disabled{opacity:.5;cursor:not-allowed;pointer-events:none!important}.vsw-search-box button.vsw-search-button:not(:disabled):hover{background-color:#c0392b}.vsw-search-box button.vsw-search-button:not(:disabled):active{transform:scale(.98)}.vsw-custom-search-input::-webkit-input-placeholder{color:#777;font-style:italic}.vsw-custom-search-input::-moz-placeholder{color:#777;font-style:italic}.vsw-custom-search-input:-ms-input-placeholder{color:#777;font-style:italic}.vsw-custom-search-input::placeholder{color:#777;font-style:italic}.vsw-video-container{padding:15px 5px;text-align:center;display:none;width:100%;box-sizing:border-box}.vsw-video-slider-container{position:relative;width:100%;max-width:100%;margin:15px auto;overflow:hidden;min-height:160px;display:none;background-color:rgba(255,255,255,.1);border-radius:8px;padding:10px;box-shadow:0 1px 4px rgba(0,0,0,.2)}.vsw-video-slider{display:flex;transition:transform .5s ease-in-out}.vsw-video-item{flex:0 0 auto;width:150px;margin:0 6px;cursor:pointer;position:relative;text-align:center;border:1px solid #555;border-radius:4px;padding:5px;background-color:#1a2b47;transition:transform .2s ease,border-color .3s ease;box-sizing:border-box}.vsw-video-item:first-child{margin-left:0}.vsw-video-item:last-child{margin-right:0}.vsw-video-item:hover{transform:scale(1.04);border-color:#00ffff}.vsw-video-item img{width:100%;height:84px;object-fit:cover;border-radius:4px;display:block}.vsw-video-item p{margin-top:6px;font-size:.8em;line-height:1.25;height:3em;overflow:hidden;text-overflow:ellipsis;color:#ccc;display:-webkit-box;-webkit-line-clamp:2;-webkit-box-orient:vertical;word-break:break-word}.vsw-video-slider-nav{position:absolute;top:50%;transform:translateY(-50%);left:0;right:0;width:100%;box-sizing:border-box;display:flex;justify-content:space-between;padding:0 5px;display:none;z-index:10;pointer-events:none}.vsw-video-slider-nav button{background:rgba(0,0,0,.7);color:#fff;border:none;padding:8px 12px;border-radius:50%;cursor:pointer;font-size:1.1em;line-height:1;width:40px;height:40px;display:flex;align-items:center;justify-content:center;transition:background-color .3s ease;pointer-events:auto;z-index:11}.vsw-video-slider-nav button:hover{background:rgba(0,0,0,1)}.vsw-video-player{width:98%;max-width:900px;margin:20px auto;border-radius:8px;overflow:hidden;box-shadow:0 4px 15px rgba(0,0,0,.5);background-color:#000}.vsw-video-player iframe{display:block;width:100%;aspect-ratio:16/9;border:none}.vsw-message-box{position:fixed;top:80px;left:50%;transform:translateX(-50%);background-color:#ffc107;color:#333;border:1px solid #e0a800;padding:15px 25px;border-radius:5px;box-shadow:0 2px 10px rgba(0,0,0,.3);z-index:1100;text-align:center;display:none;font-size:1.1em;font-weight:bold;max-width:80%;box-sizing:border-box}@media (max-width:768px){#vsw-main-widget{padding:15px;border-width:8px;border-radius:20px}.vsw-stylish-header{font-size:1.4em}.vsw-stylish-description{font-size:1.05em}.vsw-category-buttons button{flex-basis:140px;height:45px}.vsw-category-buttons{gap:12px}#vsw-category-banner{font-size:1em;padding:10px;margin-bottom:20px}.vsw-search-box{max-width:100%;padding:20px;min-height:auto}.vsw-search-box h3{font-size:1.3em;margin-bottom:15px}.vsw-search-box select,.vsw-search-box input[type=text],.vsw-search-box button{width:95%;font-size:1em;padding:10px;margin-bottom:12px}.vsw-search-box button.vsw-back-button{width:auto;max-width:180px;font-size:.85em;padding:6px 12px;margin-bottom:0}.vsw-video-item{width:130px}.vsw-video-item img{height:73px}.vsw-video-item p{font-size:.78em}.vsw-video-player iframe{height:350px}.vsw-video-slider-nav button{width:38px;height:38px;font-size:1em}}@media (max-width:480px){h2.vsw-page-title{font-size:1.4em;padding:12px}#vsw-main-widget{padding:10px;border-width:6px;border-radius:15px}.vsw-stylish-header{font-size:1.2em}.vsw-stylish-description{font-size:.95em}.vsw-category-buttons{padding:15px 5px;gap:10px}.vsw-category-buttons button{font-size:.85em;padding:8px 10px;flex-basis:calc(50% - 15px);max-width:none;height:48px}#vsw-category-banner{font-size:.9em;padding:8px;margin-bottom:15px}.vsw-search-box h3{font-size:1.15em}.vsw-search-box select,.vsw-search-box input[type=text],.vsw-search-box button{font-size:.9em;padding:8px}.vsw-search-box button.vsw-back-button{max-width:150px;font-size:.8em;padding:5px 10px;margin-bottom:0}.vsw-video-item{width:110px}.vsw-video-item img{height:62px}.vsw-video-item p{font-size:.7em;height:2.8em;-webkit-line-clamp:2;-webkit-box-orient:vertical}.vsw-video-player iframe{height:200px}.vsw-video-slider-nav button{width:32px;height:32px;font-size:.9em}}#vsw-message-texts{display:none}
/* ======================================== */
/* === Widget खोजों और सीखो=== */
/* ======================================== */
/* सर्कुलर मेन्यू कंटेनर */
.cm__circle-menu-container {
    position: fixed;
    top: 10px;
    left: 85%; /* आप इसे अपनी आवश्यकतानुसार समायोजित कर सकते हैं */
    transform: translateX(-50%);
    z-index: 1000;
}

/* मेन्यू आइकॉन */
.cm__menu-toggle {
    width: 60px;
    height: 60px;
    background-image: url('https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhCbarYqIlzfRqB0VbKZvHmwyyPtvU0Y2Nkv1izHDcL_tlX1A6d3u8KtV85jfUhqqZcsUDKds1yQDDn6p_MJbM_wec1tyUHOw50hsTHKlpVzeEfhZR_gkFsL_O4OG0zytlGbKUlJaRQPSDfx7SAqI4D6B_SnWzxSQ-lWz3ld38THUIYWdDwsXE7bBuJx7EN/s374/IMG_20250404_055208.png');
    background-size: cover;
    border-radius: 50%;
    cursor: pointer;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    transition: transform 0.3s, box-shadow 0.3s;
}

.cm__menu-toggle:hover {
    transform: scale(1.1);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
}

/* सब-कैटेगरी मेन्यू */
.cm__menu-categories {
    position: absolute;
    top: 80px;
    left: -180%;
    transform: translateX(-50%) scale(0); /* प्रारंभिक स्थिति */
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 6px;
    width: 310px;
    background-color: transparent; /* ट्रांसपेरेंट रखा गया */
    box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
    border-radius: 15px;
    padding: 8px;
    transition: transform 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275), opacity 0.4s ease, visibility 0.4s ease;
    opacity: 0;
    visibility: hidden;
    z-index: 1001;
}

.cm__menu-categories.cm__active {
    transform: translateX(-50%) scale(1); /* सही ट्रांसफॉर्म */
    opacity: 1;
    visibility: visible;
}

/* "अपनी पसंद पर क्लिक करें" टाइटल */
.cm__menu-categories .cm__category-title {
    font-size: 1.2em;
    font-weight: bold;
    text-align: center;
    padding: 10px;
    color: #fff; /* सफेद टेक्स्ट */
    border-bottom: 1px solid #555; /* थोड़ी डार्क बॉर्डर */
    display: none; /* डिफ़ॉल्ट रूप से छिपा हुआ */
    grid-column: 1 / -1; /* पूरी चौड़ाई ले */
    animation: cm__zoomIn 0.8s ease-out; /* थोड़ी तेज एनिमेशन */
    background-size: 200% auto;
    transition: background-position 0.5s ease;
    cursor: pointer;
    border-radius: 30px; /* गोल किनारे */
}

.cm__menu-categories .cm__category-title.cm__gradient-1 { background-image: linear-gradient(135deg, #e74c3c 0%, #e74c3c 10%, #e67e22 10%, #e67e22 20%, #f1c40f 20%, #f1c40f 30%, #2ecc71 30%, #2ecc71 40%, #1abc9c 40%, #1abc9c 50%, #3498db 50%, #3498db 60%, #2980b9 60%, #2980b9 70%, #9b59b6 70%, #9b59b6 80%, #e91e63 80%, #e91e63 90%, #34495e 90%, #34495e 100%); }
.cm__menu-categories .cm__category-title.cm__gradient-2 { background-image: linear-gradient(90deg, #3366ff, #cc3399, #ff3366, #ff6600, #ffff33); }
.cm__menu-categories .cm__category-title.cm__gradient-3 { background-image: linear-gradient(90deg, #00ffcc, #33ccff, #cc33ff, #ff33cc, #ff0066); }
.cm__menu-categories .cm__category-title.cm__gradient-4 { background-image: linear-gradient(90deg, #66ff33, #33ffcc, #3366ff, #6633ff, #cc33ff); }
.cm__menu-categories .cm__category-title.cm__gradient-5 { background-image: linear-gradient(90deg, #ff3300, #ff9933, #ffcc66, #ffff99, #ccffcc); }
.cm__menu-categories .cm__category-title.cm__gradient-6 { background-image: linear-gradient(90deg, #33ff57, #00ccff, #cc33ff, #ff5733, #ffcc00); }
.cm__menu-categories .cm__category-title.cm__gradient-7 { background-image: linear-gradient(90deg, #cc3399, #ff3366, #ff6600, #ffff33, #3366ff); }
.cm__menu-categories .cm__category-title.cm__gradient-8 { background-image: linear-gradient(90deg, #33ccff, #cc33ff, #ff33cc, #ff0066, #00ffcc); }
.cm__menu-categories .cm__category-title.cm__gradient-9 { background-image: linear-gradient(90deg, #6633ff, #cc33ff, #66ff33, #33ffcc, #3366ff); }
.cm__menu-categories .cm__category-title.cm__gradient-10 { background-image: linear-gradient(90deg, #ffcc66, #ffff99, #ccffcc, #ff3300, #ff9933); }
.cm__menu-categories .cm__category-title.cm__gradient-11 { background-image: linear-gradient(90deg, #33ff57, #00ccff, #cc33ff, #ff5733, #ffcc00); }
.cm__menu-categories .cm__category-title.cm__gradient-12 { background-image: linear-gradient(90deg, #cc3399, #ff3366, #ff6600, #ffff33, #3366ff); }

.cm__menu-categories .cm__category-title:hover {
    background-position: right center;
}

@keyframes cm__zoomIn {
    0% { transform: scale(0.7); opacity: 0; }
    100% { transform: scale(1); opacity: 1; }
}

.cm__menu-categories .cm__category {
    width: 68px;
    height: 68px;
    background-color: #fff;
    border: 1px solid #ddd;
    color: #333;
    font-size: 16px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.cm__menu-categories .cm__category img {
    width: 60px;
    height: 60px;
    object-fit: contain;
    border-radius: 50%;
}

.cm__menu-categories .cm__category:hover {
    transform: scale(1.15);
    box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
    border-color: #4caf50;
}

.cm__menu-links {
    position: absolute;
    top: 80px;
    left: -180%;
    transform: translateX(-50%) scale(0);
    width: 340px;
    background-color: #200000;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
    border-radius: 15px;
    padding: 20px;
    opacity: 0;
    visibility: hidden;
    max-height: 400px;
    overflow-y: auto;
    transition: transform 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275), opacity 0.4s ease, visibility 0.4s ease;
    display: none;
    z-index: 1000;
}

.cm__menu-links.cm__show {
    display: block;
    opacity: 1;
    visibility: visible;
    transform: translateX(-50%) scale(1);
    z-index: 1002;
}

.cm__menu-links .cm__links-title {
    font-size: 20px;
    font-weight: bold;
    margin-bottom: 15px;
    text-align: center;
    animation: cm__fadeInUp 1s ease-in-out;
    color: #fff;
    padding: 10px;
    border-radius: 8px;
    position: relative;
    z-index: 1;
    background-color: transparent;
    overflow: hidden;
}

.cm__menu-links .cm__links-title::before {
    content: '';
    position: absolute;
    top: -2px; left: -2px; right: -2px; bottom: -2px;
    background-size: 400% 400%;
    z-index: -1;
    border-radius: 10px;
    animation: cm__Gradient 5s ease infinite;
}

.cm__menu-links .cm__links-title.cm__gradient-1::before { background-image: linear-gradient(90deg, #ff5733, #ffcc00, #33ff57, #00ccff, #cc33ff, #ff5733, #ffcc00); }
.cm__menu-links .cm__links-title.cm__gradient-2::before { background-image: linear-gradient(90deg, #3366ff, #cc3399, #ff3366, #ff6600, #ffff33, #3366ff, #cc3399); }
.cm__menu-links .cm__links-title.cm__gradient-3::before { background-image: linear-gradient(90deg, #00ffcc, #33ccff, #cc33ff, #ff33cc, #ff0066, #00ffcc, #33ccff); }
.cm__menu-links .cm__links-title.cm__gradient-4::before { background-image: linear-gradient(90deg, #66ff33, #33ffcc, #3366ff, #6633ff, #cc33ff, #66ff33, #33ffcc); }
.cm__menu-links .cm__links-title.cm__gradient-5::before { background-image: linear-gradient(90deg, #ff3300, #ff9933, #ffcc66, #ffff99, #ccffcc, #ff3300, #ff9933); }
.cm__menu-links .cm__links-title.cm__gradient-6::before { background-image: linear-gradient(90deg, #33ff57, #00ccff, #cc33ff, #ff5733, #ffcc00, #33ff57, #00ccff); }
.cm__menu-links .cm__links-title.cm__gradient-7::before { background-image: linear-gradient(90deg, #cc3399, #ff3366, #ff6600, #ffff33, #3366ff, #cc3399, #ff3366); }
.cm__menu-links .cm__links-title.cm__gradient-8::before { background-image: linear-gradient(90deg, #33ccff, #cc33ff, #ff33cc, #ff0066, #00ffcc, #33ccff, #cc33ff); }
.cm__menu-links .cm__links-title.cm__gradient-9::before { background-image: linear-gradient(90deg, #6633ff, #cc33ff, #66ff33, #33ffcc, #3366ff, #6633ff, #cc33ff); }
.cm__menu-links .cm__links-title.cm__gradient-10::before { background-image: linear-gradient(90deg, #ffcc66, #ffff99, #ccffcc, #ff3300, #ff9933, #ffcc66, #ffff99); }
.cm__menu-links .cm__links-title.cm__gradient-11::before { background-image: linear-gradient(90deg, #33ff57, #00ccff, #cc33ff, #ff5733, #ffcc00, #33ff57, #00ccff); }
.cm__menu-links .cm__links-title.cm__gradient-12::before { background-image: linear-gradient(90deg, #cc3399, #ff3366, #ff6600, #ffff33, #3366ff, #cc3399, #ff3366); }

@keyframes cm__Gradient {
    0% { background-position: 0% 50% }
    50% { background-position: 100% 50% }
    100% { background-position: 0% 50% }
}

@keyframes cm__fadeInUp {
    0% { transform: translateY(20px); opacity: 0; }
    100% { transform: translateY(0); opacity: 1; }
}

.cm__links-content a.cm__outer-cont {
    display: flex;
    align-items: center;
    font-size: 0.95rem;
    cursor: pointer;
    position: relative;
    color: #fff;
    transition: all 0.3s ease;
    text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.8);
    margin-bottom: 10px;
    padding: 10px 15px;
    border-radius: 10px;
    text-decoration: none;
    overflow: hidden;
    border: none;
    box-shadow:
        inset 0px 0px 4px rgba(255, 255, 255, 0.6),
        inset 0px 20px 25px rgba(0, 0, 0, 0.7),
        0px 4px 8px rgba(0, 0, 0, 0.5);
}

.cm__links-content a.cm__outer-cont::before {
    content: "";
    position: absolute;
    inset: 0;
    border-radius: 12px;
    filter: blur(0);
    z-index: -1;
    box-shadow: none;
    background: conic-gradient(
        #ffffff33 80deg,
        #ffffff66,
        #ffffff88,
        #ffffff33 280deg
    );
    transition: all 0.3s ease;
    opacity: 0;
    pointer-events: none;
}

.cm__links-content a.cm__outer-cont:hover {
     transform: translateY(-2px);
     box-shadow:
        inset 0px 0px 5px rgba(255, 255, 255, 0.7),
        inset 0px 25px 30px rgba(0, 0, 0, 0.8),
        0px 6px 12px rgba(0, 0, 0, 0.6);
}

.cm__links-content a.cm__outer-cont:hover::before {
    filter: blur(10px);
    opacity: 0.6;
}

.cm__links-content a.cm__outer-cont:active {
    transform: translateY(1px);
    box-shadow:
        inset 0px 0px 6px rgba(255, 255, 255, 0.8),
        inset 0px 30px 35px rgba(0, 0, 0, 0.9);
}
.cm__links-content a.cm__outer-cont:active::before {
    filter: blur(5px);
    opacity: 0.8;
}

.cm__links-content a.cm__outer-cont img {
    width: 28px;
    height: 28px;
    margin-right: 12px;
    vertical-align: middle;
    border-radius: 4px;
    flex-shrink: 0;
    position: relative;
    z-index: 1;
}

.cm__links-content a.cm__outer-cont span {
     position: relative;
     z-index: 1;
     flex-grow: 1;
 }

.cm__links-content .cm__links {
    display: none;
}

/* इन क्लास के नामों में cm__ प्रीफिक्स जावास्क्रिप्ट में data-category से सीधे लिया जाता है */
.cm__links-content .cm__class-1-5 > a:nth-child(1) { background: linear-gradient(90deg, #ffc107, #ff9800, #ff5722); }
.cm__links-content .cm__class-1-5 > a:nth-child(2) { background: linear-gradient(90deg, #4caf50, #8bc34a, #cddc39); }

.cm__links-content .cm__class-6-8 > a:nth-child(1) { background: linear-gradient(90deg, #e91e63, #9c27b0, #673ab7); }
.cm__links-content .cm__class-6-8 > a:nth-child(2) { background: linear-gradient(90deg, #f44336, #e53935, #d32f2f); }
.cm__links-content .cm__class-6-8 > a:nth-child(3) { background: linear-gradient(90deg, #03a9f4, #00bcd4, #009688); }
.cm__links-content .cm__class-6-8 > a:nth-child(4) { background: linear-gradient(90deg, #9c27b0, #ba68c8, #e1bee7); }
.cm__links-content .cm__class-6-8 > a:nth-child(5) { background: linear-gradient(90deg, #4caf50, #8bc34a, #cddc39); }
.cm__links-content .cm__class-6-8 > a:nth-child(6) { background: linear-gradient(90deg, #ff9800, #ffc107, #ffeb3b); }
.cm__links-content .cm__class-6-8 > a:nth-child(7) { background: linear-gradient(90deg, #8bc34a, #cddc39, #f0f4c3); }
.cm__links-content .cm__class-6-8 > a:nth-child(8) { background: linear-gradient(90deg, #e91e63, #9c27b0, #673ab7); }

.cm__links-content .cm__class-9-10 > a:nth-child(1) { background: linear-gradient(90deg, #ccffcc, #8bc34a, #4caf50); }
.cm__links-content .cm__class-9-10 > a:nth-child(2) { background: linear-gradient(90deg, #ffffcc, #ffeb3b, #ffc107); }
.cm__links-content .cm__class-9-10 > a:nth-child(3) { background: linear-gradient(90deg, #ffcccc, #e53935, #f44336); }
.cm__links-content .cm__class-9-10 > a:nth-child(4) { background: linear-gradient(90deg, #ccffff, #009688, #00bcd4); }
.cm__links-content .cm__class-9-10 > a:nth-child(5) { background: linear-gradient(90deg, #ffccff, #ba68c8, #9c27b0); }
.cm__links-content .cm__class-9-10 > a:nth-child(6) { background: linear-gradient(90deg, #cc9999, #a1887f, #795548); }
.cm__links-content .cm__class-9-10 > a:nth-child(7) { background: linear-gradient(90deg, #ffc107, #ff9800, #ff5722); }
.cm__links-content .cm__class-9-10 > a:nth-child(8) { background: linear-gradient(90deg, #b0c4de, #90a4ae, #607d8b); }

.cm__links-content .cm__class-11-12 > a:nth-child(1) { background: linear-gradient(90deg, #e91e63, #9c27b0, #673ab7); }
.cm__links-content .cm__class-11-12 > a:nth-child(2) { background: linear-gradient(90deg, #00bcd4, #03a9f4, #009688); }

.cm__links-content .cm__competitive-exam > a:nth-child(1) { background: linear-gradient(90deg, #4caf50, #8bc34a, #cddc39); }
.cm__links-content .cm__competitive-exam > a:nth-child(2) { background: linear-gradient(90deg, #708090, #536d7a, #37474f); }
.cm__links-content .cm__competitive-exam > a:nth-child(3) { background: linear-gradient(90deg, #f1c40f, #f39c12, #e67e22); }

.cm__links-content .cm__news-channel > a:nth-child(1) { background: linear-gradient(90deg, #ff9800, #ffc107, #ffeb3b); }
.cm__links-content .cm__news-channel > a:nth-child(2) { background: linear-gradient(90deg, #3498db, #2980b9, #1f618d); }

.cm__links-content .cm__yoga-ayurveda > a:nth-child(1) { background: linear-gradient(90deg, #00bcd4, #03a9f4, #009688); }
.cm__links-content .cm__yoga-ayurveda > a:nth-child(2) { background: linear-gradient(90deg, #8bc34a, #cddc39, #f0f4c3); }
.cm__links-content .cm__yoga-ayurveda > a:nth-child(3) { background: linear-gradient(90deg, #708090, #536d7a, #37474f); }

.cm__links-content .cm__marriage-links > a:nth-child(1) { background: linear-gradient(90deg, #f44336, #e53935, #d32f2f); }
.cm__links-content .cm__marriage-links > a:nth-child(2) { background: linear-gradient(90deg, #795548, #a1887f, #d7ccc8); }

.cm__links-content .cm__editorial-links > a:nth-child(1) { background: linear-gradient(90deg, #9c27b0, #ba68c8, #e1bee7); }
.cm__links-content .cm__editorial-links > a:nth-child(2) { background: linear-gradient(90deg, #607d8b, #90a4ae, #cfd8dc); }
.cm__links-content .cm__editorial-links > a:nth-child(3) { background: linear-gradient(90deg, #2c3e50, #34495e, #2c3e50); }

.cm__links-content .cm__government-links > a:nth-child(1) { background: linear-gradient(90deg, #b3e5fc, #81d4fa, #4fc3f7); }

.cm__links-content .cm__astrology-links > a:nth-child(1) { background: linear-gradient(90deg, #4caf50, #8bc34a, #cddc39); }
.cm__links-content .cm__astrology-links > a:nth-child(2) { background: linear-gradient(90deg, #f44336, #e53935, #d32f2f); }
.cm__links-content .cm__astrology-links > a:nth-child(3) { background: linear-gradient(90deg, #00bcd4, #03a9f4, #009688); }

.cm__links-content .cm__vaidik-links > a:nth-child(1) { background: linear-gradient(90deg, #ffeb3b, #ffc107, #ff9800); }
.cm__links-content .cm__vaidik-links > a:nth-child(2) { background: linear-gradient(90deg, #fff9c4, #fff59d, #fff176); }

.cm__menu-links::-webkit-scrollbar { width: 8px; }
.cm__menu-links::-webkit-scrollbar-track { background: rgba(255, 255, 255, 0.1); border-radius: 10px; }
.cm__menu-links::-webkit-scrollbar-thumb { background-color: rgba(255, 255, 255, 0.4); border-radius: 10px; border: 2px solid transparent; background-clip: content-box; }
.cm__menu-links::-webkit-scrollbar-thumb:hover { background-color: rgba(255, 255, 255, 0.6); }
/* सर्कुलर मेन्यू कंटेनर समाप्त */
