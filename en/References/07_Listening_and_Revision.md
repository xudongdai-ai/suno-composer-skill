# Listening and Revision

**Use this category after generating or when diagnosing a supplied prompt.** Describe the location, problem and what must stay unchanged. Without playable/analyzable audio, work from the user's description and do not pretend to have heard it.

## Describe a concrete problem

| Problem | Useful request | Preserve |
|---|---|---|
| Chorus never opens up | Make the chorus contrast with the contained verse | Lyrics, main genre, tempo |
| Lead is masked | Reduce the backing density behind the vocal | Voice identity, lyrics, melodic intention |
| Too much EDM energy | Make acoustic instruments lead; reduce the drop emphasis | Core theme and form |
| Atmosphere without a hook | Emphasize one short motif and remove unrelated decoration | Main instrument and emotion |
| Voices appear in an instrumental | Check Instrumental, vocal-related wording and exclusions | Instrumental motif and roles |
| Words feel crowded | Shorten difficult phrases and leave breath | Key lines and story |

## Seven review dimensions

Use 0–5 as a human listening rubric, not an automatic accuracy claim.

| Dimension | 0 | 3 | 5 |
|---|---|---|---|
| Genre identity | Off target | Main traits present | Musical mechanism and sound identity align |
| Form | No contrast | Some sectional change | Each section has a clear function |
| Harmony | Conflicts with intent | Broadly suitable | Color, resolution and voice movement are coherent |
| Arrangement | Constant crowding | Lead audible | Lead, answer, bass and texture have distinct roles |
| Groove | Wrong backbone | Approximate | Relevant accents and rhythmic relationships work |
| Production | Unbalanced | Usable | The intended sound retains clarity and dynamics |
| Prompt quality | Conflicting and verbose | Usable | Specific, concise and easy to revise |

## A/B changes one variable

A is the baseline. B changes one factor while keeping the other text and requested parameters fixed. Natural generation may still vary, so listen rather than assuming causal certainty.

| Listening problem | First B change | Keep fixed |
|---|---|---|
| No theme | Put a clear three-note lead motif first | Tempo, groove, harmony |
| Unclear structure | Simplify to Intro–A–B–A′ | Lead instrument and genre |
| Bland harmony | Add one borrowed-iv or Dorian-sixth color | Groove and arrangement |
| Too electronic | Change the foreground to acoustic | Theme and tempo |
| Blurred voice | Reduce backing/reverb density | Lyrics and harmony |
| Muddy bass | Reduce multiple bass roles to one | Form and voice |
| Cultural style feels tokenized | Specify actual rhythm and instrument duties | Form |
| Fugue identity weak | Separate subject, answer and episodes | Central motif |
| DnB feels too slow | Emphasize rolling fast breakbeats | Harmony and timbre |
| Exact structure still absent | Edit the real audio/MIDI manually | Stop adding endless prompt detail |

## Experiment record

- Brief version and model/interface used
- Styles length
- One changed variable
- Listening notes for A and B
- Seven-dimension review
- Chosen version and remaining edits

Writing “D minor” in Styles does not establish that the output is in D minor.

## Studio suggestions — choose only relevant ones

Select the target region or track before using a suggestion. These are natural-language examples, not fixed command syntax; availability and success depend on the interface and listening review. One request should address one goal.

### A. Structure

#### Thin a selected section

```text
For the selected 8-bar section only, reduce the arrangement to felt piano and solo cello, retain the melodic motif, remove heavy percussion, and leave room for a gradual string entrance.
```

#### Develop a contrasting B section

```text
Create a contrasting B section using the existing melodic motif in a higher register. Keep the main pulse, change the harmony color, and introduce an answering woodwind countermelody.
```

#### Build a final-chorus transition

```text
Build the transition into the final chorus by removing the bass and kick briefly, then restore them with a wider harmony stack. Keep the lead vocal clear.
```

### B. Harmony and motif

#### Try borrowed minor-iv color

```text
Try a reharmonized variation that suggests borrowed minor iv color before the tonic return, but preserve the original vocal contour and phrase lengths as much as possible.
```

#### Use quartal Dorian accompaniment

```text
Rework the piano accompaniment with open quartal voicings and a Dorian modal center. Keep the bass foundation restrained and avoid busy dominant substitutions.
```

#### Answer the existing motif

```text
Make a short counterpoint answer to the existing three-note motif. Use a contrasting rhythm, not unison doubling.
```

### C. Instruments, timbre and tracks

#### Add a woodwind counterline

```text
Generate a delicate woodwind counterline for the current section, leaving the cello lead untouched. Favor clarinet in the middle register and use short breathing spaces.
```

#### Soften the pad

```text
Design a softer analog pad for the existing chord bed: warm attack, slow filter movement, restrained stereo spread, and no extra rhythmic accents.
```

#### Add a spiccato pulse

```text
Create a tightly articulated spiccato string pulse underneath the brass motif, keeping the low drum impacts sparse rather than continuous.
```

### D. Mixing and automation

#### Bring the lead forward

```text
For the selected lead track, aim for a clearer foreground presence with gentle compression and subtle short reverb. Keep the backing pad farther away and preserve the natural dynamic arc.
```

#### Separate bass and kick

```text
Reduce the overlap of the bass and kick in the low end. Preserve kick attack and make the melodic bass line easier to hear.
```

#### Make space with pad automation

```text
Gradually automate the ambient pad down during the lead melody, then bring it back between vocal phrases without obscuring the foreground.
```

### E. Review and export planning

#### Review the arrangement roles

```text
Summarize the current arrangement in terms of lead, harmony, bass, percussion, and atmosphere. Identify any sections where the main motif might be masked by accompaniment.
```

#### Prepare a multitrack export plan

```text
Help me prepare a multitrack export plan. Name the track groups by musical function and identify anything that requires manual timing checks before exporting.
```

After editing, listen for timing shifts, seams and masking. If a requested tool is unavailable, use the text as a manual production plan instead of claiming it ran.
