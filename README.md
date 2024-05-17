# Book Multi-Char Instruct Turn Generator

Book used for demo:  
The Hypnotist - Lars Kepler  
ISBN: 9780771095726  
Libgen id for epub used: C92945521490BC022A16F4ACA0BC87F0  

> [!IMPORTANT]  
> This costs a non-negligible amount of OpenAI credits as it uses gpt-4 (non-turbo and non-o)  
> Running this script over the full text of the book will cost around $100-150 in credits  

# Showcase

Before:
```
Erik Maria Bark is yanked reluctantly from his dream when the telephone rings. Before he is fully awake, he hears himself say with a smile, "Balloons and streamers."
His heart is pounding from the sudden awakening. Erik has no idea what he meant by these words. The dream is completely gone, as if he had never had it.
He fumbles to find the ringing phone, creeping out of the bedroom with it and closing the door behind him to avoid waking Simone. A detective named Joona Linna asks if he is sufficiently awake to absorb important information. His thoughts are still tumbling down into the dark empty space after his dream as he listens.
"I've heard you're very skilled in the treatment of acute trauma," says Linna.
"Yes," says Erik.
He swallows a painkiller as he listens. The detective explains that he needs to question a fifteen-year-old boy who has witnessed a double murder and been seriously injured himself. During the night he was moved from the neurological unit in Huddinge to the neurosurgical unit at Karolinska University Hospital in Solna.
"What's his condition?" Erik asks.
The detective rapidly summarizes the patient's status, concluding, "He hasn't been stabilized. He's in circulatory shock and unconscious."
"Who's the doctor in charge?" asks Erik.
"Daniella Richards."
"She's extremely capable. I'm sure she can—"
"She was the one who asked me to call you. She needs your help. It's urgent."
When Erik returns to the bedroom to get his clothes, Simone is lying on her back, looking at him with a strange, empty expression. A strip of light from the streetlamp is shining in between the blinds.
"I didn't mean to wake you," he says softly.
"Who was that?" she asks.
"Police... a detective... I didn't catch his name."
"What's it about?"
"I have to go to the hospital," he replies. "They need some help with a boy."
```
After:
```
<|im_start|>Erik Maria Bark
I am yanked reluctantly from my dream when the telephone rings. Before I'm fully awake, I hear myself say with a smile, "Balloons and streamers." My heart is pounding from the sudden awakening. I have no idea what I meant by these words. The dream is completely gone, as if I had never had it. I fumble to find the ringing phone, creeping out of the bedroom with it and closing the door behind me to avoid waking Simone.<|im_end|>
<|im_start|>Joona Linna
I ask if he is sufficiently awake to absorb important information.<|im_end|>
<|im_start|>Erik Maria Bark
My thoughts are still tumbling down into the dark empty space after my dream as I listen.<|im_end|>
<|im_start|>Joona Linna
"I've heard you're very skilled in the treatment of acute trauma," I say.<|im_end|>
<|im_start|>Erik Maria Bark
"Yes," I say. I swallow a painkiller as I listen.<|im_end|>
<|im_start|>Joona Linna
I explain that I need to question a fifteen-year-old boy who has witnessed a double murder and been seriously injured himself. During the night, he was moved from the neurological unit in Huddinge to the neurosurgical unit at Karolinska University Hospital in Solna.<|im_end|>
<|im_start|>Erik Maria Bark
"What's his condition?" I ask.<|im_end|>
<|im_start|>Joona Linna
I rapidly summarize the patient's status, concluding, "He hasn't been stabilized. He's in circulatory shock and unconscious."<|im_end|>
<|im_start|>Erik Maria Bark
"Who's the doctor in charge?" I ask.<|im_end|>
<|im_start|>Joona Linna
"Daniella Richards."<|im_end|>
<|im_start|>Erik Maria Bark
"She's extremely capable. I'm sure she can—"<|im_end|>
<|im_start|>Joona Linna
"She was the one who asked me to call you. She needs your help. It's urgent."<|im_end|>
<|im_start|>Erik Maria Bark
When I return to the bedroom to get my clothes,<|im_end|>
<|im_start|>Simone
I'm lying on my back, looking at him with a strange, empty expression. A strip of light from the streetlamp is shining in between the blinds.<|im_end|>
<|im_start|>Erik Maria Bark
"I didn't mean to wake you," I say softly.<|im_end|>
<|im_start|>Simone
"Who was that?" I ask.<|im_end|>
<|im_start|>Erik Maria Bark
"Police... a detective... I didn't catch his name."<|im_end|>
<|im_start|>Simone
"What's it about?"<|im_end|>
<|im_start|>Erik Maria Bark
"I have to go to the hospital," I reply. "They need some help with a boy."<|im_end|>
```