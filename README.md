# Dog Advisor Skill for Claude Code

A Claude Code skill that helps you diagnose and solve problems with your dog. Instead of giving generic tips, it asks you the right questions first — breed, age, how long the issue has been happening, what you've already tried — and then gives you specific, practical advice tailored to your actual situation.

Think of it as a knowledgeable dog trainer friend you can talk to any time.

The methodology inside this skill is based on real professional training session notes, built around positive reinforcement, marker training, criteria building, and self-control exercises.

---

## What it does

You describe a problem with your dog in plain language. The skill asks 2–3 focused questions to understand your specific situation. Then it gives you:

- **Management** — something you can do today to stop the problem from getting worse
- **Training** — the actual fix, step by step, starting simple and building up
- **Why it's happening** — so you understand your dog, not just follow instructions
- **What mistakes to avoid** — the things most people do that accidentally make the problem worse
- **How long** it realistically takes to see results
- **When to see a vet or trainer** instead of trying to fix it yourself

It handles all common dog issues: barking, biting, pulling on the leash, reactivity to other dogs, not coming when called, jumping on people, separation anxiety, chewing, and more.

If your dog sounds genuinely unwell (not eating, lethargic, sudden change in behaviour), it will tell you to go to the vet before anything else.

---

## Training philosophy

The skill is grounded in these principles:

- **Positive reinforcement first** — reward what you want, remove rewards for what you don't want
- **Marker system** — a clicker or word tells the dog the exact moment they got it right, even if the treat comes a second later
- **Criteria building** — always start indoors, low distraction. Only raise the difficulty once the dog succeeds reliably
- **Management vs training** — management stops the problem now; training fixes it for the future. You need both
- **Self-control as a foundation** — many behaviour problems come from a dog that cannot regulate its emotions. Self-control exercises fix this at the root
- **Senses under stress** — when a dog is overwhelmed, their hearing shuts down first. Stop talking and use your body and leash instead

---

## Install

```bash
gh skill install sevcovic23/dog-advisor-skill dog-advisor
```

---

## How to use it

Just describe your problem in plain language. The skill triggers automatically. You don't need to type any special command.

**Examples of things you can say:**

- `My dog barks like crazy every time I leave the house`
- `My puppy keeps biting my hands when we play`
- `My dog pulls so hard on the leash I can barely walk him`
- `My dog stopped eating and just lies around`
- `I don't know what to do with my dog anymore`

The skill will ask you a couple of questions, then give you a clear answer.

---

## Example conversation

**You:** My dog barks like crazy every time I leave the house. My neighbours are complaining. I have a 3 year old beagle.

**Dog Advisor:** That sounds really stressful. Before I suggest anything, a few questions:
1. How long has this been going on? Did anything change around the time it started?
2. What exactly does he do — does he bark the whole time or just for a while after you leave?
3. Have you tried anything so far, even things that didn't work?

**You:** It started 6 months ago when I went back to the office after 2 years working from home. My neighbour says he barks for at least an hour. I tried a Kong with peanut butter but it only helps for 10 minutes.

**Dog Advisor:** This is separation anxiety triggered by a routine change — very common in beagles when a big shift happens. Here's what to focus on:

1. **Gradual departures** — start with 30-second absences, build up slowly over days. This retrains his brain to see your leaving as normal, not alarming.
2. **Freeze the Kong** — frozen peanut butter lasts 30–40 minutes instead of 10. Pair it with a specific phrase like "I'm going now" so he starts associating it with something good.
3. **More exercise before you leave** — beagles need a proper run, not a 15-minute walk. A tired beagle is a calmer beagle.

Most owners see real improvement in 3–4 weeks with consistency. If it doesn't improve, a vet can discuss short-term medication to take the edge off while you work on the training — that's a legitimate tool, not a last resort.

---

## What it does NOT do

- Diagnose medical conditions (always go to a vet for health concerns)
- Help with breeding or medical procedures
- Replace a professional trainer for serious aggression cases

---

## License

MIT — free to use, share, and modify.
