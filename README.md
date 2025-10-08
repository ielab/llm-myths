# Support material for "Humans are more gullible than LLMs in believing common psychological myths"


## 50 myths dataset

The table below provides the 50 myths taken from Lilienfeld, 2009. Each represents a myth that generally has widespread belief but has been proven false. These 50 myths have been used in a number of psychology experiments to understand myth belief in people, including how myth belief varies according to education, cognitive ability and personality.

| Psychological Myths |
|----------------------|
| We only use 10% of our brains. |
| Most people in their 40s and 50s experience a midlife crisis. |
| Keeping a positive attitude can help keep cancer at bay. |
| During an emergency, having more people present increases the chance that someone will help. |
| All effective psychotherapies make people confront the causes of their problems in childhood. |
| The polygraph (Lie Detector) test accurately detects dishonesty. |
| Hypnosis causes a “trance” state, different from wakefulness. |
| Dreams hold symbolic meaning. |
| People are either left-brained or right-brained. |
| Intelligence tests are biased against certain groups. |
| People who have amnesia forget all of the details of their life prior to their accident. |
| Psychiatric labels stigmatize and cause harm to people. |
| Handwriting reveals our personality traits. |
| Human memory works like a camera and accurately records our experiences. |
| Our eyes emit light that causes us to see. |
| A major cause of psychological problems is low self-esteem. |
| If someone confesses to a crime, they are almost always guilty of it. |
| Recently there has been a massive epidemic of autism in childhood. |
| Stress is the primary cause of ulcers. |
| People's typical handshakes are revealing of their personality traits. |
| Reversing letters is the central characteristic of dyslexia. |
| Adolescence is a time of psychological chaos. |
| Extrasensory perception (i.e., ESP or “psychic feelings”) is a scientifically established phenomenon. |
| If we inherit a trait, we can't change it. |
| The only effective treatment for alcoholics is abstinence. |
| People with Schizophrenia have multiple personalities. |
| Raising children similarly leads to similar adult personalities. |
| It's better to let out anger than to hold it in. |
| Happiness mostly comes from our external circumstances. |
| Hypnosis can help retrieve suppressed or forgotten memories. |
| Most mentally ill people are violent. |
| Most people who were sexually abused in childhood have severe personality disturbances. |
| Adult children of alcoholics display distinctive symptoms. |
| Playing classical music to infants increases their intelligence. |
| Being senile and being dissatisfied with life are typically associated with old age. |
| Only people who are very depressed commit suicide. |
| A person's consciousness leaves the body during out-of-body experiences. |
| If you're unsure of an answer when taking a test, it's best to stick with your first hunch. |
| Individuals are capable of learning new information while asleep. |
| Criminal profiling helps solve cases. |
| Subliminal messages can persuade us to purchase products. |
| Men and women communicate in completely different ways. |
| Electroconvulsive (shock) therapy is a physically dangerous and brutal treatment. |
| Students learn best when teaching styles are matched to their learning styles. |
| Criminals commonly use the insanity defense to get off free. |
| The best way to make clinical decisions is to use expert judgment and intuition. |
| It is common to repress the memories of traumatic events. |
| Psychiatric hospital admissions and crimes increase during full moons. |
| We are romantically attracted to people who are different from us. |

## Statistical Significance Tests

### Table: Chi-square significance matrix (* indicates p < 0.05)

| Label | Model Name | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R |
|-------|---------------------------------------------|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| A     | Human - Junior Psychology Students (63%)   | * |   |   |   |   |   |   |   |   |   |   |   |   | * |   |   |   |
| B     | Human - Senior Psychology Students (51%)   |   |   |   | * | * | * |   |   |   |   |   |   |   | * |   |   |   |
| C     | Llama-3.3-70B (22%)                        |   |   |   | * | * |   |   |   |   |   |   |   |   |   |   |   |   |
| D     | Llama-4-17B (8%)                           |   | * |   | * | * |   |   |   |   | * |   |   |   |   |   |   |   |
| E     | GPT-4o (24%)                               |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| G     | RAG + Llama-3.3-70B (20%)                  |   | * |   | * | * |   |   |   |   |   |   |   |   | * |   |   |   |
| H     | RAG + Llama-4-17B (0%)                     |   |   |   | * | * |   |   |   |   |   |   |   |   |   | * |   |   |
| I     | RAG + GPT-4o (16%)                         |   | * | * | * | * | * |   |   | * |   | * |   | * |   | * | * |   |
| J     | RAG + Gemini-2.5-Flash (10%)               |   | * | * | * | * | * |   |   |   | * |   |   | * |   | * |   |   |
| K     | Sway Sceptic + Llama-3.3-70B (0%)          |   |   |   |   | * |   |   |   |   |   |   |   |   |   |   |   |   |
| L     | Sway Sceptic + Llama-4-17B (0%)            |   |   |   |   | * |   |   |   |   |   |   |   |   |   | * |   |   |
| M     | Sway Sceptic + GPT-4o (8%)                 |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| N     | Sway Sceptic + Gemini-2.5-Flash (0%)       |   |   |   |   |   |   |   |   |   |   |   |   |   |   | * |   |   |
| O     | Sway Believer + Llama-3.3-70B (65%)       |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| P     | Sway Believer + Llama-4-17B (4%)          |   | * | * | * | * |   |   |   |   | * |   |   |   |   |   |   |   |
| Q     | Sway Believer + GPT-4o (41%)              |   | * |   | * | * | * | * |   | * |   |   |   |   | * | * |   | * |
| R     | Sway Believer + Gemini-2.5-Flash (51%)    |   | * |   | * |   | * |   |   |   |   |   |   |   | * |   |   |   |




