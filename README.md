# Simplon Off

> Flip the lights off on AI.

**Simplon Off** helps you run AI locally on your own machine — private, offline, and energy-aware. Instead of routing every prompt to a giant data center, Simplon Off recommends a right-sized open model you can run on your laptop, packaged as a single [llamafile](https://github.com/Mozilla-Ocho/llamafile) executable.

Built during a **GreenTech Hackathon** by Fabio, Oleg, David and Stephan.

🌐 [simplon-off.ch](https://simplon-off.ch)

---

## Why

Most everyday AI tasks — drafting an email, summarizing a note, brainstorming — don't need a frontier model. Running a small local model is:

- **Private** — your prompts never leave your device.
- **Offline** — works on a plane, in a tunnel, anywhere.
- **Sustainable** — orders of magnitude less energy than a hyperscale inference call.

## How it works

1. **Tell us what you want help with** — pick a few friendly bundles (writing, learning, coding, creative) or describe your own use case.
2. **Tell us about your device** — RAM, OS, and rough comfort level.
3. **Get a recommendation** — a specific open model, a llamafile download, and setup instructions tailored to your machine.

## Tech stack

- [TanStack Start](https://tanstack.com/start) (React 19, Vite 7, SSR)
- Tailwind CSS v4 with semantic design tokens
- shadcn/ui components
- Deployed on Cloudflare Workers

## Local development

```bash
bun install
bun dev
```

The app runs at `http://localhost:5173`.

## Credits

- Models packaged via [Mozilla Ocho · llamafile](https://github.com/Mozilla-Ocho/llamafile)
- Built with [Lovable](https://lovable.dev)

## Team

Fabio · Oleg · David · Stephan
