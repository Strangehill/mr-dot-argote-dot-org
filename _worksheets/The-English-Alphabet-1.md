---
title: The English Alphabet
subtitle: Letter Sounds
layout: A4-landscape
class: eng1
yaml-letters-and-lexicon:
  - A a,apple=_pple,ant=___,alligator=_lli_a_o_,astronaut=_stronau_,ax=__,Africa=______
  - B b,baby=_a_y,book=_oo_,bee=b__,bird=_ir_,butterfly=__tt_r_ly
  - C c,cat=__t,clock=_l_ck,can=___,cloud=__ou_,cockroach=__ck_oa__,caterpillar=___er__llar
  - C c,centipede=_____pede,circle=___cle,cemetery=__me__ry,city=__ty,cereal=__rea_
  - D d,dog=___,doctor=___to_,desk=____,duck=_uck,dinosaur=____sau_,dolphin=___ph__
  - E e,egg=_gg,elephant=___ph___,earth=_arth,eraser=_ra___,eight=_igh_
  - F f,fish=_ish,four=_ou_,football=_oo_ball,flower=__ow__,fan=___
  - G g,goat=_oa_,gift=____,glue=____,guitar=_ui___
  - G g,giraffe=____ffe,gem=___,gems=____,genie=__n__
  - H h,hippopotamus=__ppo_____us,hand=_an_,hat=___,hammer=__mm__,horse=__rse
  - I i,ice-cream=___-_rea_,igloo=___oo,ink=___,idea=_de_
  - J j,jacket=__cke_,jam=___,jar=___,jug=___,juice=___ce
  - K k,keyboard=____oar_,koala=_____,kiwi-bird=____=kiwi,kiwi-fruit=____=kiwi,kiss=__ss
  - L l,lion=_io_,lemon=__m__,lollipop=__ll_p__,leaf=_ea_
  - M m,monkey=____ey,moon=_oo_,milk=__l_,map=___
  - N n,nine=_i_e,nurse=___se,neck=__ck,newspaper=___spa_er
  - O o,ostrich=_____ch,orange=____ge,olives=____es,octopus=__t____,ocarina=___ri__
  - P p,pencil=___cil,popcorn=_______,penguin=_e_gui_,parrot=__rro_
  - Q q,quill=___ll,queen=__ee_,question=____tio_,quiet=__ie_
  - R r,robot=_____,rabbit=__bbi_,rainbow=_____ow,rectangle=__c___gle,roadrunner=r__d__nn__
  - S s,sock=__ck,square=___are,seahorse=_ea___se,socks=__ck_,six=___
  - T t,turtle=___tle,ten=___,triangle=__i__gle,telescope=_e_e___pe,two=_wo
  - U u,umbrella=__br_ll_,up=__,unicycle=___cycle,unicorn=___c___
  - V v,vegetables=__ge__ble_,volcano=___ca__,violin=_io___,vest=____,vase=_ase
  - W w,water=___e_,web=___,wifi=____,whale=_h___
  - X x,fox=___,box=___,ax=__,sax=___,t-rex=t-r__
  - Y y,yogurt=___u__,yoga=____,yoyo=____,yarn=__r_
  - Z z,zebra=__b__,zero=____,zombie=____ie,zipper=___p__
  - CH ch,cheese=____se,chair=__ai_,chess=___ss,chocolate=____olate
  - PH ph,phone=___n_,pharaoh=_____oh,photographs=_____gra__s,dolphin=dol____
  - SH sh,shell=___ll,ship=____,sheep=_____,shoes=__oe_,shark=_____
  - TH th,three=_____,thumb-down=____bs ____=thumbs down,theater=__ea___,thumb-up=__u_bs __=thumbs up
one_off_styles: |
  .a-letter {
    border: dotted #DDD;
    border-width: 1px 0 0 0;
    display: flex;
    padding: 0.5rem;
    page-break-inside: avoid;
    &_The-Hero {
      color: #FFF;
      font-size: 5rem;
      padding: 0 0.2em;
      text-shadow: 1px 1px 5px blue, -1px -1px 5px red;
      flex-basis: auto;
    }
    &_pics-and-blanks_combo {
      flex-grow: 1;
      justify-content: space-around;
      margin-top: 0.6rem;
      text-align: center;
      img {
        height: 4rem;
        display: inline-block;
        padding: 0.5rem;
        &:hover {
          background-image: radial-gradient(#FED, white 65%, #CCC 66%, #666 70%, hsla(0,0,100%,0) 71%);
          background-clip: padding-box;
          cursor: pointer;
          margin-bottom: 0.5em;
          animation: spinWhenRead 0.6s ease-in-out ;
          @keyframes spinWhenRead{
            0% { transform: scale(1) rotate(0deg);}
            83% { transform: scale(1.8) rotate(360deg);}
            100% { transform: scale(1) rotate(360deg);}
          }
        }
      }
      div {
        font-size: 1.2em;
        letter-spacing: 0.14em;
        transition: all 0.4s ease-in-out;
        word-spacing: 0.2em;
        span {
          position: relative;
          top: 0.2em;
        }
      }
    }
  }
  .answers {
    padding: 0.7rem 4rem;
    border-top: 1px solid #EEE;
    page-break-before: avoid;
    page-break-inside: avoid;
    text-align: center;
    &_label {
      margin-right: 2rem;
    }
  }
  @media screen {
    .hackyHr {
      border: 1px solid #EEE;
      margin-bottom: 10em;
      transition: all 0.4s ease-in-out;
      &.no-margin {
        margin-bottom: 0em;
      }
    }
    .widget select, .no-widget .select {
      position: absolute;
      left: -5000em;
      height: 0;
      overflow: hidden;
    }
    select {
      position: absolute;
      height: 2rem;
      top: 0.8rem;
      left: 50%;
      right: 50%;
      transform: translateX(-50%);
    }
    .select {
      background : linear-gradient(0deg, #E3E3E3, #fcfcfc 50%, #f0f0f0);
      border: .2em solid black;
      border-radius: .4em;
      box-shadow: 0 .1em .2em rgba(0,0,0,.45);
      position: absolute;
      padding: .1em 2.5em .2em .5em;
      width: 16rem;
      top: 1rem;
      left: 50%;
      right: 50%;
      text-align: center;
      transform: translateX(-50%);
      .hidden {
        max-height: 0;
        visibility: hidden;
      }
      &.active, &:focus {
        outline: 3px solid green;
        box-shadow: 0 0 3px 1px #227755;
      }
      .value {
        display: inline-block;
        width: 100%;
        overflow: hidden; vertical-align: top;
        white-space  : nowrap;
        text-overflow: ellipsis;
      }
      &:after {
        content: "▼";
        position: absolute;
        z-index : 1;
        top     : 0;
        right   : 0;
        box-sizing: border-box;
        height: 100%;
        width: 2em;
        padding-top: .1em;
        border-left: .2em solid black;
        border-radius: 0 .1em .1em 0;
        background-color: black;
        color: white;
        text-align: center;
      }
      .voice-options {
        background: #F0F0F0;
        border: .2em solid black;
        border-radius: 0 0 .4em .4em;
        border-top-width: .1em;
        box-shadow: 0 .2em .4em rgba(0,0,0,.4);
        box-sizing: border-box;
        list-style-type: none;
        margin: 0;
        max-height: 10em;
        min-width: 100%;
        overflow-y: auto;
        overflow-x: hidden;
        padding: 0;
        position: absolute;
        top: 100%;
        left: 0;
        z-index: 2;
        .option {
          padding: .2em .3em;
        }
        .highlight {
          background: black;
          color: white;
        }
      }
    }
  }
  @media print {
    form {
      display: none;
    }
  }
  @media (max-width: 700px){
    body.printout {
      background-color: #FFF;
      padding: 0 0.5em;
      width: 100%;
    }
    .a-letter {
      flex-wrap: wrap;
      //&_The-Hero { min-width: calc(100%/3); }
      &_pics-and-blanks_combo { min-width: calc(100%/4); }
    }
    .answers {
      padding-left: 0.7rem;
      padding-right: 0.7rem;
      text-align: center;
      &_label {
        margin-right: 1.5rem;
      }
    }
  }
  @media (max-width: 450px){
    .a-letter {
      //&_The-Hero { min-width: calc(100%/2); }
      &_pics-and-blanks_combo { min-width: calc(100%/3); }
    }
  }
---

<form class="no-widget">
<select name="fallbackDefault" tabindex="-1">
</select>

<div class="select" tabindex="0" role="listbox">
<span class="value">Alex</span>
<ul class="voice-options hidden" role="presentation">
{% comment %}
<!-- What the template looks like: -->
<li data-voiceName="${voice.name}" data-voiceLang="${voice.lang}" class="option" role="option">${voice.name}</li>
{% endcomment %}
</ul>
</div>
<hr class="hackyHr no-margin">
</form>

{% assign rowsOfLetters = 0 %}
{% assign answers = ""  %}

{% for itemString in page.yaml-letters-and-lexicon %}
  {% assign itemArray = itemString | split: ',' %}
  {% assign lastIndex = itemArray.size | minus: 1 %}
  {% for nth in (1..lastIndex) %}
    {% assign wordPicPairArray = itemArray[nth] | split: "=" %}
    {% if wordPicPairArray.size==3 %}
      {% assign answers = answers | append: ' * ' | append: wordPicPairArray[2] %}
    {% else %}
      {% assign answers = answers | append: ' * ' | append: wordPicPairArray[0] %}
    {% endif %}
  {% endfor %}
  <div class="a-letter">
  <div class="a-letter_The-Hero">
    {{ itemArray[0] }}
  </div>
  {% for nth in (1..lastIndex) %}
  {% assign wordPicPairArray = itemArray[nth] | split: "=" %}
  <div id="{% if wordPicPairArray.size==3 %}{{wordPicPairArray[2]}}{% else %}{{wordPicPairArray[0]}}{% endif %}" class="a-letter_pics-and-blanks_combo">
    <img src="/assets/icons-and-clipart/svg/own/lexicon/{{ wordPicPairArray[0] }}.svg" height="60" />
    <div>{{ wordPicPairArray[1] | replace: '_', '<span>_</span>' }}</div>
  </div>
  {% endfor %}
  </div>
  {% assign rowsOfLetters = rowsOfLetters | plus: 1 %}
  {% if
    rowsOfLetters == 4
    or rowsOfLetters == 13
    or rowsOfLetters == 13
    or rowsOfLetters == 21
    or rowsOfLetters == 28
    or rowsOfLetters == 32%}
  <div class="answers">
    <span class="answers_label">ANSWERS:</span> {{ answers }}
  </div>
  {% assign answers = "" %}
  {% endif %}
{% endfor %}


<script>

var i, allAudioElems;

allImgItems = document.querySelectorAll('.a-letter_pics-and-blanks_combo img');
allImgItems.forEach(imgItem => imgItem.addEventListener('click',play));

const msg = new SpeechSynthesisUtterance();

function play(e) {
  msg.text = this.parentNode.getAttribute('id');
  speechSynthesis.speak(msg);
}

let voices = [];
const voicesLiOptions = document.querySelector('.voice-options'); // with radio
const fallbackSelectOptions = document.querySelector('[name="fallbackDefault"]');

function populateVoices() {
  voices = this.getVoices().filter(voice => voice.lang.includes('en'));

  voicesLiOptions.innerHTML = voices // with radio
  .map(voice => `
    <li
      data-voiceName="${voice.name}" data-voiceLang="${voice.lang}"
      class="option" role="option">
        ${voice.name}
    </li>
    `)
  .join('');

  fallbackSelectOptions.innerHTML = voices
  .filter(voice => voice.lang.includes('en'))
  .map(voice => `
    <option value="${voice.name}">${voice.name} (${voice.lang})</option>
  `)
  .join('');

  voicesLiOptions.parentElement.classList.remove("hidden");

  activateDropdown();
}

function setVoice() {
  msg.voice = voices.find(voice => voice.name === this.value); // with select/option
}

speechSynthesis.addEventListener('voiceschanged', populateVoices);
fallbackSelectOptions.addEventListener('change', setVoice); // since this event won't
// fire when updateValue() assigns nativeWidget.selectedIndex, that function has its own msg.voice call.

/* Making the custom form element interactive */

NodeList.prototype.forEach = function (callback) {
  Array.prototype.forEach.call(this, callback);
}

window.addEventListener('load', function () {
  var form = document.querySelector('form');

  form.classList.remove('no-widget');
  form.classList.add('widget');
});

function deactivateSelect (select) {
  if (!select.classList.contains('active')) return;
  var voiceOptions = select.querySelector('.voice-options');
  voiceOptions.classList.add('hidden');
  var hackyHr = document.querySelector('.hackyHr');
  hackyHr.classList.add('no-margin');
  select.classList.remove('active');
}
function activeSelect (select, selectList) {
  if (select.classList.contains('active')) return;
  selectList.forEach(deactivateSelect);
  select.classList.add('active');
}
function toggleVoiceOptions (select) {
  var voiceOptions = select.querySelector('.voice-options');
  voiceOptions.classList.toggle('hidden');
  var hackyHr = document.querySelector('.hackyHr');
  hackyHr.classList.toggle('no-margin');
}
function highlightOption (select, option) {
  var voiceOptions = select.querySelectorAll('.option');
  voiceOptions.forEach(function (other) {
    other.classList.remove('highlight');
  });
  option.classList.add('highlight');
};

function activateDropdown() {
  var selectList = document.querySelectorAll('.select');
  selectList.forEach(function (select) {
    var optionList = select.querySelectorAll('.option');
    optionList.forEach(function (option) {
      option.addEventListener('mouseover', function() {
        highlightOption(select, option);
      });
    });
    select.addEventListener('click', function (event) {
      toggleVoiceOptions(select);
    });
    select.addEventListener('focus', function (event) {
      activeSelect(select, selectList);
    });
    select.addEventListener('blur', function (event) {
      deactivateSelect(select);
    });
  });
  bindCustomAndNative();
};

function updateValue (select, index) {
  var nativeWidget = select.previousElementSibling;
  var value = select.querySelector('.value');
  var optionList = select.querySelectorAll('.option');
  optionList.forEach(function (other){
    other.setAttribute('aria-selected', 'false');
  });
  optionList[index].setAttribute('aria-selected', 'true');
  nativeWidget.selectedIndex = index;
  value.innerHTML = optionList[index].innerHTML;
  msg.voice = voices
    .find(voice => voice.name === optionList[index].getAttribute("data-voiceName"));
  highlightOption(select, optionList[index]);
};

function getIndex (select) {
  var nativeWidget = select.previousElementSibling;
  return nativeWidget.selectedIndex;
};

function bindCustomAndNative () {
  var selectList = document.querySelectorAll('.select');
  selectList.forEach(function (select) {
    var optionList = select.querySelectorAll('.option'),
        selectedIndex = getIndex(select);
    select.tabIndex = 0;
    select.previousElementSibling.tabIndex = -1;
    updateValue(select, selectedIndex);
    optionList.forEach(function (option, index) {
      option.addEventListener('click', function (event) {
        updateValue(select, index);
      });
    });
    select.addEventListener('keyup', function (event) {
      var length = optionList.length,
          index = getIndex(select);
      if (event.keyCode === 40 && index < length - 1) { index++; }
      if (event.keyCode === 38 && index > 0) { index --; }
      updateValue(select, index);
    });
  });
};

 </script>

