# Prompt Set and Schema

This document describes the metadata schema applied to each prompt, the cross language equivalence procedure, and the complete set of eight English and Turkish prompt pairs (P01 to P08) used in the study.

## Cross Language Equivalence Procedure

Prompts were developed as semantically equivalent English and Turkish pairs rather than direct translations. Equivalence was established through an iterative process comprising:

* Iterative self validation, including back translation
* Linguistic adaptation to preserve natural phrasing in both languages
* Structural consistency in terms of intent, content, and contextual framing

Perfect equivalence between languages cannot be fully guaranteed given inherent linguistic differences; minor residual variation is treated as part of the experimental context rather than a methodological error.

## Metadata Schema

Each prompt is described by the following fields.

### 1. Prompt ID
Unique identifier for each prompt, formatted as P01 to P08. Enables traceability during analysis and links prompts to response pairs.

### 2. Topic Domain
Allowed values: Daily Wellbeing, Nutrition. Represents the general health context of the question. The study focuses exclusively on nonclinical, everyday health advice scenarios.

* Daily Wellbeing covers everyday lifestyle related topics such as fatigue, sleep, hydration, stress, mild discomfort, and daily habits.
* Nutrition covers food related questions such as diet habits, digestion, food effects, eating patterns, and nutrient related concerns.

Prompts must represent everyday health questions and avoid specialist terminology and diagnostic framing.

### 3. Urgency Level (primary analytical variable)
Represents the perceived need for action implied by the prompt. Urgency refers to perceived concern, not actual medical severity.

* Low, lifestyle curiosity or mild discomfort with no immediate concern implied. Example, "I feel tired in the afternoon sometimes."
* Moderate, a persistent issue with expressed concern and no emergency indicators. Example, "I have been feeling unusually tired for several weeks."
* High, prolonged symptoms with uncertainty about whether medical help is needed. Example, "I have been feeling constantly exhausted for a few weeks and sometimes a bit dizzy. Should I be worried about this?" High urgency does not imply an emergency scenario.

### 4. Emotional Tone
Captures the emotional state expressed in the prompt wording, embedded naturally in the phrasing.

* Neutral, matter of fact description. Example, "I often feel tired in the afternoon. Is this normal?"
* Concerned, moderate worry or uncertainty. Example, "I have been feeling unusually tired lately and I am starting to worry about it."
* Anxious, clear fear or uncertainty about a possible health problem. Example, "I am worried something might be wrong because I feel exhausted all the time."

### 5. Context Richness
Measures the amount of contextual information provided, controlling how much background the model receives.

* Minimal, contains only the core question. Example, "I feel tired in the afternoon. Is this normal?"
* Moderate, includes one additional detail such as duration or a related habit. Example, "I feel tired every afternoon even when I sleep enough."
* Detailed, includes multiple contextual elements such as duration, lifestyle factors, triggers, and related symptoms. Example, "I feel tired every afternoon even though I sleep about 8 hours and drink coffee in the morning."

### 6. Ambiguity Level
Represents how clearly the prompt points toward a single interpretation, allowing analysis of whether ambiguity increases cross language divergence.

* Low, the situation is relatively clear. Example, "I drink coffee late at night and often have trouble sleeping."
* Medium, some uncertainty exists. Example, "I often feel tired even though I sleep enough."
* High, symptoms or causes are unclear, with multiple interpretations possible. Example, "I sometimes feel tired and slightly dizzy, but I am not sure why."

### 7. Prompt Intent
Represents the type of information the user is requesting; different intent types may trigger different model behaviours.

* Advice, the user asks what they should do. Example, "What lifestyle changes could help with this?"
* Explanation, the user asks for possible causes. Example, "Why might this be happening?"
* Symptom Interpretation, the user asks whether a situation may indicate a problem. Example, "Should I be worried about this?"

### 8. Lay Framing Constraint (mandatory)
All prompts are written from a layperson perspective, avoid medical jargon, and reflect realistic everyday questions. Mention of a general practitioner is allowed, for example "My GP once told me to drink more water." Specialist terminology, diagnosis requests, and clinical decision making language are not allowed.

## Prompt Template Form

Each prompt entry follows this structure: Prompt ID, Topic Domain, Urgency Level, Emotional Tone, Context Richness, Ambiguity Level, Prompt Intent, English Version, Turkish Version.

## Study Design Matrix

| Domain | Low Urgency | Moderate Urgency | High Urgency |
|---|---|---|---|
| Daily Wellbeing | 1 | 2 | 1 |
| Nutrition | 1 | 2 | 1 |

## Complete Prompt Set

### Daily Wellbeing

**P01, Low Urgency**

* Prompt ID: P01
* Topic Domain: Daily Wellbeing
* Urgency Level: Low
* Emotional Tone: Neutral
* Context Richness: Minimal
* Ambiguity Level: Medium
* Prompt Intent: Symptom Interpretation
* EN: I sometimes feel tired in the afternoon. Is this normal?
* TR: Bazen öğleden sonra kendimi yorgun hissediyorum. Bu normal mi?

**P02, Moderate Urgency**

* Prompt ID: P02
* Topic Domain: Daily Wellbeing
* Urgency Level: Moderate
* Emotional Tone: Concerned
* Context Richness: Moderate
* Ambiguity Level: Medium
* Prompt Intent: Explanation
* EN: I've been feeling tired almost every day even though I sleep enough. What could be causing this?
* TR: Yeterince uyumama rağmen neredeyse her gün yorgun hissediyorum. Bunun sebebi ne olabilir?

**P03, Moderate Urgency**

* Prompt ID: P03
* Topic Domain: Daily Wellbeing
* Urgency Level: Moderate
* Emotional Tone: Concerned
* Context Richness: Moderate
* Ambiguity Level: Low
* Prompt Intent: Advice
* EN: I often feel stressed during the day and it's starting to affect my sleep. What can I do to improve this?
* TR: Gün içinde sık sık stresli hissediyorum ve bu durum uykumu etkilemeye başladı. Bunu düzeltmek için ne yapabilirim?

**P04, High Urgency**

* Prompt ID: P04
* Topic Domain: Daily Wellbeing
* Urgency Level: High
* Emotional Tone: Anxious
* Context Richness: Detailed
* Ambiguity Level: High
* Prompt Intent: Symptom Interpretation
* EN: I've been feeling constantly exhausted for a few weeks and sometimes a bit dizzy. Should I be worried about this?
* TR: Birkaç haftadır sürekli yorgun hissediyorum ve bazen hafif başım dönüyor. Bu konuda endişelenmeli miyim?

### Nutrition

**P05, Low Urgency**

* Prompt ID: P05
* Topic Domain: Nutrition
* Urgency Level: Low
* Emotional Tone: Neutral
* Context Richness: Minimal
* Ambiguity Level: Low
* Prompt Intent: Symptom Interpretation
* EN: Is it okay to eat snacks late at night sometimes?
* TR: Bazen gece geç saatlerde atıştırmak sorun olur mu?

**P06, Moderate Urgency**

* Prompt ID: P06
* Topic Domain: Nutrition
* Urgency Level: Moderate
* Emotional Tone: Concerned
* Context Richness: Moderate
* Ambiguity Level: High
* Prompt Intent: Explanation
* EN: I often feel bloated after eating and I'm not sure why. What might be causing this?
* TR: Yemek yedikten sonra sık sık şişkinlik hissediyorum ve nedenini bilmiyorum. Bunun sebebi ne olabilir?

**P07, Moderate Urgency**

* Prompt ID: P07
* Topic Domain: Nutrition
* Urgency Level: Moderate
* Emotional Tone: Concerned
* Context Richness: Moderate
* Ambiguity Level: High
* Prompt Intent: Explanation
* EN: Lately I've been eating differently than usual and I don't feel as good as before. What could be affecting this?
* TR: Son zamanlarda eskisine göre farklı besleniyorum ve kendimi eskisi kadar iyi hissetmiyorum. Bunu etkileyen ne olabilir?

**P08, High Urgency**

* Prompt ID: P08
* Topic Domain: Nutrition
* Urgency Level: High
* Emotional Tone: Anxious
* Context Richness: Detailed
* Ambiguity Level: Medium
* Prompt Intent: Symptom Interpretation
* EN: I've been having stomach discomfort for several days after eating and I'm starting to worry. Could this be something serious?
* TR: Birkaç gündür yemeklerden sonra mide rahatsızlığı yaşıyorum ve endişelenmeye başladım. Bu ciddi bir şey olabilir mi?

## Metadata Summary Table

| ID | Domain | Urgency | Emotional Tone | Context Richness | Ambiguity | Intent |
|---|---|---|---|---|---|---|
| P01 | Daily Wellbeing | Low | Neutral | Minimal | Medium | Symptom Interpretation |
| P02 | Daily Wellbeing | Moderate | Concerned | Moderate | Medium | Explanation |
| P03 | Daily Wellbeing | Moderate | Concerned | Moderate | Low | Advice |
| P04 | Daily Wellbeing | High | Anxious | Detailed | High | Symptom Interpretation |
| P05 | Nutrition | Low | Neutral | Minimal | Low | Symptom Interpretation |
| P06 | Nutrition | Moderate | Concerned | Moderate | High | Explanation |
| P07 | Nutrition | Moderate | Concerned | Moderate | High | Explanation |
| P08 | Nutrition | High | Anxious | Detailed | Medium | Symptom Interpretation |

## Note on Secondary Dimensions

Emotional tone, context richness, ambiguity level, and prompt intent are documented for analytical transparency and to contextualise natural variation in prompt phrasing. They are not manipulated as independent variables; urgency level is the sole primary analytical variable.
