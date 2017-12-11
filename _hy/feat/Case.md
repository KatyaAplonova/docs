---
layout: feature
title: 'Case'
shortdef: 'case'
udver: '2'
---

<table class="typeindex" border="1">
<tr>
  <td style="background-color:cornflowerblue;color:white"><strong>Values:</strong> </td>
  <td><a href="#Abl">Abl</a></td>
  <td><a href="#Dat">Dat</a></td>
  <td><a href="#Gen">Gen</a></td>
  <td><a href="#Ins">Ins</a></td>
  <td><a href="#Loc">Loc</a></td>
  <td><a href="#Nom">Nom</a></td>
</tr>
</table>

Case is an inflectional feature of [nouns](NOUN) and
[pronouns](PRON). In Armenian there is no case agreement with nouns.
It is also valency feature of [adpositions](ADP) (saying that
the adposition requires its argument to be in that case).

Case helps specify the role of the noun phrase in the sentence.

The descriptions of the individual case values below include semantic
hints about the prototypical meaning of the case. Bear in mind that
quite often a case will be used for a meaning that is totally
unrelated to the meaning mentioned here. Valency of verbs,
adpositions and other words will determine that the noun phrase must
be in a particular grammatical case to fill a particular valency slot
(semantic role).

Armenian linguistics distinguishes from five (morphological) to seven (syntactic) cases:
`Nom`, `Gen`, `Dat`, `Acc`, `Abl`, `Ins` and `Loc` (this ordering is fixed in the grammar and the cases are also referred to by numbers 1–7).

Note, that the first (direct) object of the verb can be formed in nominative or dative (syntactic accusative), this is related to [Animacy](). They will be tagged `Case=Nom` and `Case=Dat` and not `Case=Nom,Acc` or `Case=Gen,Dat` as in some Armenian grammars.

The difference between `Gen` and `Dat` is related to [definiteness](Definite). The `Gen` can not have `Definite=Def`.

Note also, that vocatives, and noun modifiers as an attribute in nominative or as a genitive complement in genitive can not have `Definite=Def`. In these cases we declare `Definite=Ind`. Only this value will have also `Ins`, `Abl` and `Loc` cases.

Personal and demonstrative pronouns distinguish between `Case=Gen` and `Case=Dat`. In genitive they will have `Poss=Yes`.

#### Examples

* singular nominative _դպրոց&nbsp;_ “school”, dative _դպրոցի(ն),&nbsp;_ ablativ _դպրոցից,&nbsp;_ instrumental _դպրոցով,&nbsp;_ locative _դպրոցում_
* singular nominative _ժամանակ&nbsp;_ “time”, dative _ժամանակի(ն), ժամանակվա(ն),&nbsp;_ ablativ _ժամանակից, ժամանակվանից,&nbsp;_ instrumental _ժամանակով,&nbsp;_ locative _ժամանակում_
* singular nominative _արյուն,&nbsp;_ “blood”, dative _արյան(ն),&nbsp;_ ablativ _արյունից,&nbsp;_ instrumental _արյունով, արյամբ&nbsp;_
* singular nominative _մայր&nbsp;_ “mother”, dative _մոր(ն),&nbsp;_ ablativ _մորից,&nbsp;_ instrumental _մորով_

### <a name="Nom">`Nom`</a>: nominative

The base form of the noun, also used as citation form (lemma).
In Armenian this is the word form used for subjects of clauses, for direct objects of verbs and to address someone. 

### <a name="Gen">`Gen`</a>: genitive

Prototypical meaning of genitive is that the noun phrase somehow
belongs to its governor.

We not recognizing the genitive except for possessive personal, some demonstrative pronouns and _իր&nbsp;_ “one’s own”, _ում&nbsp;_ “whose”.

### <a name="Dat">`Dat`</a>: dative

This is the word form often used for indirect objects of verbs.

In Armenian this form is used also for cases when the noun phrase somehow
belongs to its governor (see above).

#### Examples

* _Ես <b>եղբորս</b> նվեր տվեցի։&nbsp;_ “I gave my brother a present.”
  (_եղբորս&nbsp;_ “my brother” is dative and
  _նվեր&nbsp;_ “present” is nominative.)
* _ Երևանը <b>Հայաստանի</b> մայրաքաղաքն է։&nbsp;_ “Yerevan is the
  capital <b>of Armenia</b>.”

### <a name="Abl">`Abl`</a>: ablative

Prototypical meaning: direction from some point (object, location or time).

#### Examples

* _սեղանից&nbsp;_ "from the table"
* _ծովափից&nbsp;_ "from the beach"
* _ամառվանից&nbsp;_ "from the summer"

### <a name="Loc">`Loc`</a>: locative

The locative case often expresses location in space or time, which
gave it its name. As elsewhere, non-locational meanings also exist and
they are not rare. On the other hand, some location roles
may be expressed using other cases (e.g. because those cases are
required by a preposition).

This is the only Czech case that is used exclusively in
combination with prepositions.

#### Examples

* _V <b>červenci</b> jsem byl ve <b>Švédsku</b>.&nbsp;_ “In <b>July</b>
  I was in <b>Sweden</b>.”
* _Mluvili jsme tam o <b>morfologii</b>.&nbsp;_ “We talked there about
  <b>morphology</b>.” (Non-locational non-temporal example)

### <a name="Ins">`Ins`</a>: instrumental

The role from which the name of the instrumental case is derived is
that the noun is used as instrument to do something (as in _psát
<b>perem</b>&nbsp;_ “to write <b>using a pen</b>”).  Many other meanings are
possible, for example the instrumental is required by the
preposition _s&nbsp;_ “with” and thus it includes the meaning expressed in
other languages by the comitative case.

In Czech the instrumental is also used for the agent-object in passive
constructions (cf. the English preposition _by_).

#### Examples

* _Tento zákon byl schválen <b>vládou</b>.&nbsp;_ “This bill has been
  approved <b>by the government</b>.” (Passive example)