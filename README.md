# Reinforcement Learning From Human Feedback

### L1_How does RLHF work

```
Input text: Before I go to university, I want to take a road trip in Europe. I've lived in several European
cities (mostly in central Europe), but there's still a lot I haven't seen. I want to make the route as short
as possible, while making sure I get to see some mountains and the beach. I'm wondering, should I go mostly to
places that are significant from my childhood, or should I try to go mostly to places that Ive never seen?

summary: User wants to take a road trip in Europe before university. They want to see as much as possible in a short time.
They are wondering if they should go to places that are significant from their childhood or places they have never seen.
```

* As an example,
```
Summary I: User wants to take a road trip In Europe before university. They want to see as much as possible in a short time.
They are wondering if they should go to places that are significant from their childhood or places they have never seen.

Summary 2: How to balance visiting places you've been before versus visiting new places on a road trip.

{input text, summary or 2?}
```


<img width="422" alt="image" src="https://github.com/thisarakaushan/Reinforcement-Learning-From-Human-Feedback/assets/125348115/b095134f-d11f-4eec-9d18-e916d540b312">
<br>

* RLHF consists of 3 stages
  
  <img width="550" alt="image" src="https://github.com/thisarakaushan/Reinforcement-Learning-From-Human-Feedback/assets/125348115/eec834d8-256f-4781-9944-7844b5e525fe">
  <br>

### What is an ML pipeline?

  <img width="210" alt="image" src="https://github.com/thisarakaushan/Reinforcement-Learning-From-Human-Feedback/assets/125348115/3bd2bfad-2603-472b-a12f-94db0e9fc0fe">

  * Orange boxes are components, or steps of your ML workflow
  * Blue boxes are the artifacts produced

### RLHF pipeline (simplified view)

  <img width="319" alt="image" src="https://github.com/thisarakaushan/Reinforcement-Learning-From-Human-Feedback/assets/125348115/64775730-ff7a-4f54-8dbd-c2953cf2d5d7">

 
