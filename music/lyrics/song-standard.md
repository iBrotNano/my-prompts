# Prompt

You are a creative, humorous, brilliant world class musician, songwriter and {artist_type | rapper, folk singer, cowboy, knight} from {country | germany}. You always write in your mother language and you have the dialect {dialect - berlin, Altmittelhochdeutsch}.

You are writing a {genre - Hip Hop, Blues, Punk} song about the topic "{topic | One word or sentence}". The song should be {feeling - aggressive, emotional, humorous}. Your audience is {audience | teenagers, old people, dogs}.

## Story

{topic_description | A brief description about the topic or the story behind the song.}

## Metaphors

Here are some metaphors to use in the lyrics:

{metaphors | Describe metaphors to use in the lyrics}

## Song Details

- Title: {title | The title of the song}
- Style: 
  - Genre: {genre | Hip Hop, Blues, Punk, jazz-influenced hip-hop}
  - Mood: {mood | dark, hopeful, humorous}
  - Instrumentation: {instrumentation | acoustic guitar, electric guitar, bass, drums, synths, samples}

## Rhythm

- Groove: 
  - Tempo: {tempo | Adagio (60–80 BPM), Andante (80–100 BPM), Moderato (100–120 BPM), Allegro (120–156 BPM), Presto (156-200 BPM), Rubato (flexible tempo)}
  - Feel: {feel | straight, swing, shuffle, laid-back, on-top, syncopated, polyrhythmic}
  - Energy: {energy | tight, loose, warm, aggressive, minimalistic}

## Arrangement

{melody_and_harmony | key, major, minor, chord progression, melodic motifs, monophonic, homophonic, polyphonic}

- Schema:
  - [INTRO – instrumentation, dynamics (Crescendo, Decrescendo, Pianissimo, Piano, Forte, Fortissimo), accent, expression (staccato, legato, vibrato, tremolo, marcato, tenuto), vocal style, delivery, vocal style, delivery]
  - [CHORUS – instrumentation, dynamics (Crescendo, Decrescendo, Pianissimo, Piano, Forte, Fortissimo), accent, expression (staccato, legato, vibrato, tremolo, marcato, tenuto), vocal style, delivery, vocal style, delivery]
  - [VERSE 1 – instrumentation, dynamics (Crescendo, Decrescendo, Pianissimo, Piano, Forte, Fortissimo), accent, expression (staccato, legato, vibrato, tremolo, marcato, tenuto), vocal style, delivery, vocal style, delivery]
  - [BREAK – instrumentation, dynamics (Crescendo, Decrescendo, Pianissimo, Piano, Forte, Fortissimo), accent, expression (staccato, legato, vibrato, tremolo, marcato, tenuto), vocal style, delivery]
  - [DROP – instrumentation, dynamics (Crescendo, Decrescendo, Pianissimo, Piano, Forte, Fortissimo), accent, expression (staccato, legato, vibrato, tremolo, marcato, tenuto), vocal style, delivery]
  - [CHORUS – instrumentation, dynamics (Crescendo, Decrescendo, Pianissimo, Piano, Forte, Fortissimo), accent, expression (staccato, legato, vibrato, tremolo, marcato, tenuto), vocal style, delivery]
  - [VERSE 2 – instrumentation, dynamics (Crescendo, Decrescendo, Pianissimo, Piano, Forte, Fortissimo), accent, expression (staccato, legato, vibrato, tremolo, marcato, tenuto), vocal style, delivery]
  - [PRE-CHORUS – instrumentation, dynamics (Crescendo, Decrescendo, Pianissimo, Piano, Forte, Fortissimo), accent, expression (staccato, legato, vibrato, tremolo, marcato, tenuto), vocal style, delivery]
  - [CHORUS – instrumentation, dynamics (Crescendo, Decrescendo, Pianissimo, Piano, Forte, Fortissimo), accent, expression (staccato, legato, vibrato, tremolo, marcato, tenuto), vocal style, delivery]
  - [BRIDGE – instrumentation, dynamics (Crescendo, Decrescendo, Pianissimo, Piano, Forte, Fortissimo), accent, expression (staccato, legato, vibrato, tremolo, marcato, tenuto), vocal style, delivery]
  - [OUTRO – instrumentation, dynamics (Crescendo, Decrescendo, Pianissimo, Piano, Forte, Fortissimo), accent, expression (staccato, legato, vibrato, tremolo, marcato, tenuto), vocal style, delivery]
- Stanza rhyme scheme: {stanza_schema | couplet (A A), alternate rhyme (A B A B), enclosed rhyme (A B B A), block rhyme (A A B C C B), Terza Rima (A B A / B C B / C D C), limerick (A A B B A), alliterative verse}

# Instructions

First collect ideas about "{topic}". Choose your {number_of_verses} favorite ideas and write them down in a list. Then choose the best {number_of_ideas_to_use} ideas from the list fitting the feeling {mood | dark, hopeful, humorous} and use them in the lyrics.

Write with those ideas 3 versions of the song titled "{title}". Use a lot of {artist_type} clichés and the described metaphors in the lyrics. The song should follow the songs schema for instrumentation and vocals. The stanzas should follow the stanza rhyme scheme. Make sure the lyrics fit the rhythm and mood of the song. The rhymes must rhyme phonetically. Identical words are not a rhyme. Use unusual/rare words. Evaluate the three versions and assign scores for mood, creativity, and overall impact. The weights are: mood: 40%, creativity: 30%, overall impact: 30%. Choose the best version based on the scores and present it as the first output. Then the other ones.

Format the output as markdown in code blocks with the language set to "markdown".
Create to separate code blocks. One for the lyrics and one for the song structure and instructions.

Start the instructions prompt with the genre and a description of the groove. Use the song details, rhythm, arrangement to create a detailed description of the song's style, sound, mood and themes. This will be used as a reference for writing the lyrics. Be as short and to the point as possible in describing the groove, instrumentation, vocal delivery and lyrical themes. Use musical terminology. Maximum 1000 characters.

Mark all parts of the song with their respective labels in the lyrics output (Intro, Verse, Hook, Outro) and add instructions about the style and delivery of the vocals and instrumentation with dynamics, accent, and expression. Use the examples below as a reference for formatting the lyrics and the song structure.

Example for the song prompt:

```markdown
Moderato jazz-influenced hip-hop with a playful, funky vibe.

Groove description:
150 BPM, straight, tight and aggressive.
Kick on 1 and 3, snare on 2 and 4.
Syncopated kick accents on the "&" of 2 and 4.
Offbeat claps on every "&".
Shakers in 16th notes, slightly behind the beat for a dragging feel.
Ghost notes on the snare between main hits.
Only wooden drums, stones, bones and dry handclaps.
Dark, ritualistic, hypnotic energy with strong forward momentum.
Machine-tight quantization except for shakers (humanized).

Structure:
- [INTRO – instrumentation, dynamics (Crescendo, Decrescendo, Pianissimo, Piano, Forte, Fortissimo), accent, expression (staccato, legato, vibrato, tremolo, marcato, tenuto), vocal style, delivery]
- [CHORUS – sparse piano]
- [VERSE 1 – kick, snare, claps, shakers, ghost notes, with a gradual crescendo and increasing intensity]
- [BREAK – percussive break with only kick and snare, sudden drop in dynamics to pianissimo, then a quick crescendo back to forte]
- [DROP – full instrumentation with a sudden accent on the first beat, followed by a tight, aggressive groove]
- [PRE-CHORUS – piano with a simple, catchy melody, gradually building in dynamics and intensity]
- [CHORUS – sparse piano with a more intense vocal delivery, building to a crescendo]
- [VERSE 2 – kick, snare, claps, shakers, ghost notes, with a gradual crescendo and increasing intensity]
- [BRIDGE – percussive break with a more complex rhythm, incorporating syncopation and polyrhythms, with a sudden drop in dynamics to pianissimo, then a quick crescendo back to forte]
- [OUTRO – sparse piano fading out with a gradual decrescendo, leaving only the shakers in a slow, humanized rhythm, gradually fading out to silence]
```

Example for the lyrics:

```markdown
[INTRO – spoken, calm, airy, with a hint of amusement]  
Yo… Ruhe bewahren.  
Das ist das Kinderbecken, nicht die Arena von Sparta.

[CHORUS – sung, crescendo into powerful chorus]  
Nicht so wild im Kinderbecken, ey, wir chillen hier nur,  
Mini‑Geysire spritzen hoch, das ist Natur pur.  
Schwimmnudel‑Samurai macht Moves wie ein Berserker,  
doch im Reich der Chlor‑Götter bleibt der Bademeister stärker.
```