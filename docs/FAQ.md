# FAQ

## What is Content Studio?

Content Studio is a local-first AI knowledge workspace for turning scattered source material into a structured Markdown knowledge base on your own computer.

## What can I put into it?

Current public scope:

- PDF files
- DOCX and text documents
- scanned documents and images via OCR
- web pages
- YouTube videos
- GitHub repositories and documentation-style text sources

## What comes out?

Content Studio can generate:

- structured Markdown notes,
- summaries and linked concepts,
- reports,
- HTML slides,
- PPTX slide decks,
- charts,
- Obsidian Canvas boards.

## Does it store my files on AlphaTech servers?

No, not as the default operating model.

Your raw files, wiki notes, and generated outputs live on your machine. Content Studio is local-first.

However, the app can still use network connections for:

- the AI provider you configure,
- fetching web/YouTube/GitHub sources,
- license/update traffic.

## Is it fully offline?

Not fully.

It is local-first, but not network-free. The exact behavior depends on how you use it:

- local files can stay on-device,
- cloud LLM providers require outbound API calls,
- remote sources obviously require network fetches.

## How does YouTube support work?

The app first tries to use captions. If a video has usable captions, it can ingest from those.

If a video has no usable captions, Content Studio can optionally fall back to speech-to-text. Public-facing claim should stay conservative:

- caption path is primary,
- speech-to-text fallback depends on the user enabling it and the build/provider path available,
- clear audio gives the best results.

## Does speech-to-text always run locally?

Not always.

There are two possible modes:

- local speech-to-text on the user's machine,
- API-based speech-to-text through the configured provider.

That distinction matters. Local mode keeps audio on-device. API mode sends audio to the chosen provider.

## Do I need Obsidian?

No, but it helps.

Content Studio outputs standard Markdown and Canvas-friendly artifacts, so Obsidian is a strong companion tool. The product is designed to work well with Obsidian rather than replace it.

## Is Content Studio a replacement for ChatGPT, Claude, Notion, or Obsidian?

No.

- ChatGPT / Claude: strong general chat tools
- Notion: strong workspace/database/collaboration tool
- Obsidian: strong editor and note environment
- Content Studio: structured ingest + local knowledge compilation + output generation from curated notes

The product is best understood as part of a workflow, not a universal replacement.

## What platforms are supported?

Current public target:

- Windows 10/11 x64

macOS is not public-ready yet.

## What is the pricing?

Current public commercial model:

- Trial: 15 days, full features
- Paid plan: Lifetime Personal - `1,250,000 VND`
- Refund: 30 days

Payment and key delivery are handled directly, not through this repository.

## Can I buy it from GitHub?

No.

This GitHub repository is for product information and support routing. The purchase path is the landing page and direct contact.

## Is the source code public?

No.

Content Studio is a commercial closed-source desktop product. This repository is public-facing documentation only.
