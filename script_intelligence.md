style: sales copy

Coming soon: Script Intelligence

Talking with AI can be helpful, but AI models easily get lost when dealing with a whole script. 
They also don't have precise references [expand]

Our AI-Powered Script Parsing pipeline gives a powerful foundation for AI models to analyze scripts.
This allows AIs to combine their reading of the script, with data analysis that they run on structured data. 
This results in responses that are **grounded**, **extensive**, and provide **citations** that enhance trust.

Here's a concrete example based on our demo analysis of No Country for Old Man. The goal is to list the exact scenes where Moss and Carla Jean appear together.

Note: this experiment was run on Claude.ai with the model Claude Sonnet 3.7.

EXPERIMENT A: BASE MODEL, JUST PDF

Prompt:
What are the exact scenes in which Moss and Carla Jean appear together?
Provide exact references to the scenes and scene numbers. Respond precisely and ground your responses with scene name, scene number and page number.
Respond textually, listing all the data and explaining what happens in each scene.
You are provided with the full script in PDF.

Answer:
Looking at the provided script of "No Country For Old Men," I'll identify all scenes where Moss and Carla Jean appear together. The script doesn't have formal scene numbers, but I'll reference them by location and approximate page position in the PDF.

### Scenes with Moss and Carla Jean Together:

1. **Moss's Trailer - Night** (Early in script)
   - Moss enters the trailer carrying the document case
   - Carla Jean asks "What's in the satchel?"
   - Moss responds "It's full a money"
   - They have a conversation where Carla Jean questions him about the pistol
   - This is their first scene together, establishing their relationship

2. **Moss's Trailer Bedroom - Night** (Shortly after previous scene)
   - Moss lies in bed next to Carla Jean
   - He gets up while she's sleeping
   - She wakes and asks where he's going
   - He says he's "fixin' to do somethin' dumbern hell"

3. **Moss's Trailer - Night** (After Moss returns from the scene at the river)
   - Moss tells Carla Jean she needs to go to Odessa
   - They discuss leaving, with Moss explaining that people will be looking for the money
   - Carla Jean reluctantly begins packing
   - Moss tells her "anything you leave you ain't gonna see again"

4. **Trailways Bus - Day**
   - Moss and Carla Jean are on the bus
   - He explains he's going to Del Rio to borrow a car from Eldon
   - Carla Jean expresses concern: "I got a bad feelin', Llewelyn"
   - Moss promises to call her in a couple of days
   - This is their final scene together in the script

The script doesn't contain formal scene numbers, but these are all the scenes where Moss and Carla Jean appear together. Their relationship is characterized by Carla Jean's concern for Moss and his protective but somewhat dismissive attitude toward her. Their final interaction on the bus is particularly significant as it's the last time they see each other before Moss is killed later in the script.

EXPERIMENT B: PDF + TABLE
I'll analyze where Moss and Carla Jean appear together in the script. Let me examine the data carefully.

Based on the script analysis, here are all the scenes where Moss and Carla Jean appear together:

## Scene 1: INT. TRAILER - NIGHT (Scene 18, Page 11-12)
This is the first scene where Moss and Carla Jean appear together. Moss returns to their trailer with the document case full of money and a pistol. Carla Jean questions him about both items, and Moss is evasive about where he got them. The dialogue shows their dynamic - Carla Jean being inquisitive and Moss being secretive about what he's found. Their conversation includes:
- Carla Jean asking about the satchel, with Moss revealing it's "full a money"
- Carla Jean questioning about the pistol, with Moss claiming he "found it"
- Their back-and-forth reveals tension as Moss refuses to explain where he's been

## Scene 2: INT. TRAILER KITCHEN - NIGHT (Scene 20, Page 13)
In this scene, Moss wakes up in the middle of the night and decides to go back to the scene of the drug deal. Carla Jean catches him as he's filling a water jug. Their conversation shows Moss's determination and Carla Jean's concern:
- Moss tells her he's "fixin' to do somethin' dumbern hell but I'm goin' anyways"
- He makes the ominous statement "If I don't come back tell Mother I love her"
- When Carla Jean reminds him his mother is dead, he says "Well then I'll tell her myself"

## Scene 3: INT. MOSS' TRAILER - LATER (Scene 29, Page 24-25)
After Moss returns from being chased and injured at the river, he tells Carla Jean they need to leave. This scene shows them preparing to flee:
- Moss tells Carla Jean she needs to go to Odessa to stay with her mother
- He explains that authorities will track his truck to their trailer by morning
- They argue about what to tell her mother
- Carla Jean is upset at his lack of apology, and Moss says "Things happened. I can't take 'em back"

## Scene 4: INT. TRAILWAYS BUS - DAY (Scene 39, Page 34-35)
This scene shows Moss and Carla Jean as they're separating. They're on a bus, and Moss is explaining his plans:
- Moss tells her he's going to borrow a car from someone named Eldon
- Carla Jean expresses concern, saying "I got a bad feelin', Llewelyn"
- Moss tries to reassure her that everything will be fine
- Carla Jean asks if he's coming back, and Moss responds "I shall return"
- He also tells her she's "retired" from her Walmart job

## Scene 5: INT. GREYHOUND STATION - DEL RIO - DAY (Scene 124, Page 89-90)
This is their final interaction, which takes place over the phone. Moss calls Carla Jean from a bus station:
- They discuss Sheriff Bell having contacted Carla Jean
- Carla Jean can tell Moss is hurt just from his voice
- Moss tells her to meet him at the Heart of Texas motel in El Paso
- He plans to give her the money and put her on a plane
- Carla Jean refuses to "leave him in the lurch"
- Moss explains his plan: with her gone and him without the money, "he can't touch me"
- They argue about what to do with Carla Jean's mother who has cancer

These are all the scenes where Moss and Carla Jean directly interact with each other. Their relationship shows mutual care but also tension as Moss puts them in danger by taking the money. Their final phone conversation becomes tragically significant as they never see each other again before Moss is killed at the El Paso motel.

COMPARISON:

Output 2 is the superior response.

It correctly identifies all the scenes where the characters are physically together (matching Output 1).

It includes the crucial final phone call interaction, providing a more complete picture of their relationship and plot arc within the script.

It provides significantly more detail, including specific dialogue examples and scene/page references, making it more useful for detailed analysis.

[you can maybe show the prompts side by side to show that they're almost identical]

-------

Besides this, there is a wealth of analysis that we can run on the script breakdown to facilitate VFX bidding work.

The following is an example of an experimental dashboard built on a code analysis of "No Country for Old Men".

[dashboard image]
[links to https://claude.site/artifacts/45aa84ba-ddc6-4ed2-a61e-8ccd25a64bca]

Some of the metrics that this dashboard includes:

Key VFX Metrics - Shows the number of VFX scenes (66, representing 42% of all scenes), exterior locations (70), night scenes (51), and weather effect scenes (29)
VFX Elements Distribution - Bar chart showing the frequency of VFX elements like gun/weapon effects (68 mentions), blood (29 mentions), fire (15), etc.
Location Types - Pie charts showing the breakdown between interior/exterior scenes and day/night scenes
VFX Sequence Complexity - Table analyzing the most complex VFX scenes with details on length, character count, and action lines
Violence/Action Intensity Map - Line chart showing potential VFX-heavy moments across the script by page, with identified peaks around pages 61-64, 16-17, and 91
Location Continuity Requirements - Charts showing locations that appear multiple times and require consistent VFX treatment
Budget Considerations - Breakdown of high-impact elements, complex sequences, and resource planning needs

---- 

This examples illustrate the potential of Script Intelligence to enhance VFX bidding work [etc. etc. more sales]

While this is experimental and in alpha, we are excited to [etc. etc.]

Do you have any feedback? Want to work with us on these frontier capabilities? Interested in an early preview? Let us know [contact page]

[Add anything you think is important]