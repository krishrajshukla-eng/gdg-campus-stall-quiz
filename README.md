# GDG Campus Stall Quiz

A welcoming, one-minute tech quiz and club introduction designed for a GDG campus stall.

Visitors can try three beginner-friendly questions, see their score immediately, and learn how a QR-based sign-up could connect them with a club team. The project is deliberately lightweight: one responsive HTML page, no framework, no build step, and no data collection.

## Try it

Open [`index.html`](./index.html) in a browser, or serve this folder locally:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## What’s included

- **Interactive quiz:** three multiple-choice questions, instant scoring, and a reset button.
- **Join plan:** a suggested Google Form flow for collecting a preferred team and contact details with consent.
- **Stall fallback:** a simple plan for continuing the presentation if the projector fails.
- **Accessible, responsive layout:** semantic sections and labels, keyboard-operable controls, live score announcements, and reduced-motion support.

The quiz is self-contained and keeps answers in the browser. The Google Form and QR code are a proposal only; no sign-up form is connected and no personal information is collected by this demo.

## Project reflection

I made this small page to give students an easy first interaction at a tech-club stall. The quiz is the activity; the team sign-up plan provides a next step for anyone interested.

Keeping the idea useful without making it complicated was the main challenge. I want to learn more about building web projects with a team and turning a prototype into something students can use.

If the projector stops working, I can introduce the club without slides, invite the audience to play the quiz on a phone or laptop, and use a QR code or printed sheet for sign-ups.

## Project notes

- No dependencies or API keys are required.
- The quiz is a demonstration, not a formal assessment.
- The sign-up flow needs a real, organizer-approved form before it can collect responses.
