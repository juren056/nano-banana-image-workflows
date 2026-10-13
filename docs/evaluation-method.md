# Image evaluation results and method

Use these checks before judging an image workflow. An attractive illustration demonstrates a design idea; a recorded website task demonstrates that an operation ran. Neither alone establishes reliability across your work.

## What counts as a verified case

A published case must include its full prompt, reusable input images with permission, actual provider endpoint, settings, test date and original downloadable output. Record the time from submission to a usable result, quoted and charged credits, retries, failures and any manual editing. Keep a sanitized case identifier rather than publishing private account details.

Our [public workflow repository](https://github.com/juren056/nano-banana-image-workflows) separates illustrative artwork from the recorded website outputs below. These are operator tests, not independent reviews.

## Twenty-task acceptance set

[View the table on the website](https://nanobanana21pro.com/evaluation-method)

This is the acceptance **method**, not a claim that all twenty tasks have already passed. Test status and outputs must be reported separately. Repeated calls and comparisons increase the request count and cost.

## Recorded website tests — 13 October 2026

We submitted twenty single-output tasks through the production website. All twenty returned an image, costing **150 site credits** in total, with no retries or manual retouching. This records technical completion, not a 100% visual pass rate. Provider billing is separate from site credits. The test account’s balance is not a customer price.

The final set includes four bottle edits, four Chinese designs, four fictional-character edits, three cutouts, one background replacement and four two-reference tasks. Three of the last four use the same scene to compare 2.1, 2 and Pro; this replaces two originally planned independent multi-reference scenes. There are no three-object or person-plus-product tests in this run.

### What the outputs show

- **Chinese designs (NB-05–08):** the requested words and numbers are legible in these four outputs. Slash separators become layout breaks, and spacing/punctuation can vary. This small set does not establish accuracy for longer text or other fonts.
- **Bottle scenes (NB-01–04, NB-16):** the ivory bottle, black pump and DAILY SERUM label remain recognizable. This is a visual check, not an exact geometry measurement.
- **Character edits (NB-09–12):** the same fictional subject, shirt and camera remain recognizable, with changes in pose and fine facial details. No identity similarity score is claimed.
- **Background removal (NB-13–15):** all three PNGs contain real alpha transparency. The person cutout retains a tabletop and the shoe cutout retains pedestal fragments. These need cleanup for a person-only or shoe-only asset; transparent pixels alone are not a clean-cutout pass.
- **Model comparison (NB-17–19):** all three models return a distinct bottle and shoe on separate pedestals. Composition, scale and texture vary. Each model ran once; 2.1 used 1K while 2 and Pro used provider defaults. This is an example comparison, not a controlled resolution benchmark or model ranking.

The most supported starting scenario in this run is **short Chinese promotional designs**, followed by simple bottle-background edits. Proofread each output and verify product details before publication. This is an operator assessment; external reviewers have not evaluated this set.

### Reproduce and inspect every submitted result

The [complete case manifest](https://nanobanana21pro.com/evidence/2026-10-13/results.json) contains all twenty full prompts, reusable public source references, exact endpoints, stored settings, quoted and charged credits, dimensions, SHA-256 hashes and per-case review notes. References pasted into the browser were converted from the public WebP source to PNG, without intentional content changes. The manifest records which cases used reencoded uploads. No private account identifiers or customer records are published.

Timing below is the server task’s `created_at` to `updated_at` interval. It includes the polling/completion-recording delay, so it is neither a browser stopwatch nor provider-only inference time. A paused test runner can inflate it. No seed was fixed; following the procedure will not reproduce identical pixels.

![Contact sheet of the twenty recorded website outputs](https://nanobanana21pro.com/evidence/2026-10-13/contact-sheet.png)

[View the table on the website](https://nanobanana21pro.com/evaluation-method)

## Comparing models fairly

Freeze the prompt, input files and pass rules before seeing outputs. Match aspect ratio and resolution where both models support them. Record unsupported settings instead of silently substituting models. Show every submitted result, including failures; do not select only the most attractive image. Report technical completion separately from text accuracy, preservation and usefulness.

For costs, count all charged attempts and edits required to reach a usable file. A low first-request quote does not prove a lower finished-project cost. Current model quotes are displayed in the [generator](https://nanobanana21pro.com/#tool-generator); site subscriptions are explained on [pricing](https://nanobanana21pro.com/pricing).

## Independent reviewer guide

Choose a task you would actually use, record your input and inspect the original output. Describe both useful results and limitations. Disclose gifted credits or any relationship with the operator. You can publish an honest assessment without providing a positive review. Obtain permission before publishing another person's references or images.

Send corrections or an existing public review through [contact](https://nanobanana21pro.com/contact). We will not manufacture testimonials or publish your private generation history without permission.

## Questions

### Does a completed task guarantee a usable image?

No. Completion means the provider returned a result. Spelling, object preservation, composition and suitability need separate review.

### Can the same prompt reproduce identical pixels?

Usually not. Record supported seed and settings where available, but treat reproducibility as following the same documented procedure rather than guaranteeing an identical image.

### Are failed tasks and subscriptions part of the checks?

Yes. Verify task status and credit reversal, download ownership, renewal disclosure and cancellation behavior. Use isolated fixtures for forced failures and subscription changes; a fixture test must not be described as a real paid purchase.
