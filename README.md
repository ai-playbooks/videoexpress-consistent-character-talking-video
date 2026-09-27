# VideoExpress — Consistent Character Talking Video Workflow

A browser-based production workflow for a consistent talking character: generate or attach a reference photo, create expressive scenes with Lipsync HD speech, assemble and trim matching audio/video layers, save the project, and export and download an MP4.

## Use

1. Open [SYSTEM_PROMPT.md](SYSTEM_PROMPT.md) and copy the complete workflow into a browser-capable AI agent, or attach the file.
2. Enable the agent's supported browser capability and use your existing VideoExpress session. Complete login yourself when required.
3. Provide a topic and choose an uploaded reference or an AI-generated character. See [the example request](examples/example-request.md).
4. The agent completes routine authorized production through export and download, with required host confirmations and bounded recovery when necessary.

Defaults are vertical 9:16, Human images, seven scenes, requested eight-second clips, a consistent character bible and voice phrase, and Lipsync HD. Actual clip lengths determine the delivered runtime. Dialogue goes in Actor 1 Script, not the image or scene-description fields.

## Contents

- [SYSTEM_PROMPT.md](SYSTEM_PROMPT.md) — complete production workflow.
- [examples/example-request.md](examples/example-request.md) — paste-ready customer request.
- [evals/acceptance-checklist.md](evals/acceptance-checklist.md) — completion and review checklist.

## Authorization and privacy

Routine generation, editing, saving, exporting, and downloading proceed within the customer's request without repeated approvals. Existing lifetime or unlimited-generation entitlements are account context, not authority for new purchases, unrelated work, or unlimited retries. Required action-time confirmations still apply.

Keep public-gallery sharing off. Use authorized reference assets and establish speaker permission if a separate voice-cloning request is introduced. Never commit passwords, tokens, access keys, browser-session data, or customer production assets to this repository.

## Verification and recovery

Before generation, the agent writes one coherent pose with clear hand roles, natural wrist alignment, suitable framing, and object-specific size, orientation, contact, and support. Image prompts retain the full character bible. Automatic prompt enhancement is disabled where controllable, or reviewed where the resulting text is exposed, to protect these details. Video movement must remain compatible with the chosen pose and grip.

After every image generation, the agent inspects the reference or selected scene candidate inside VideoExpress using its preview and full-size/zoom/pan controls for character continuity, visible anatomy, hands, and realistic object grips. Images are not downloaded for this check. Only passing images proceed to video generation. Defective candidates are replaced or corrected within the existing retry limits and checked again; this is an automatic review, not an extra customer approval pause. The final MP4 is still downloaded for delivery.

Inspect generated scenes and timeline order, preserve audio/video synchronization, verify saving, and open the final export. Report which visual and audio checks were actually possible; successful decoding alone does not prove perceptual quality. Check existing jobs before resubmitting and preserve successful assets.

This revision improves image-prompt construction and visual review while preserving character identity, story emotion, voice direction, and dialogue rules. It also clarifies tool boundaries, authorization, retry limits, and completion evidence. It does not guarantee defect-free images or execution without host warnings or required customer interaction.

