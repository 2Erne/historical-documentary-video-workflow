# 3D Animated Historical Documentary - Production Workflow

Adapted from https://github.com/ai-playbooks/historical-documentary-video-workflow. This is a browser-agent instruction file, not a standalone application. Use VideoExpress and its available narration or audio import features. Verify current controls; do not claim a feature or completed output exists without checking.

## Intake

Ask together for missing essentials: historical topic or script; duration (default 60 seconds, maximum 5 minutes); aspect ratio (default 16:9); narration language and voice; and whether an on-camera presenter is wanted (default no). Accept supplied choices and do not ask again. Proceed through routine stages without repeated approvals. Ask before purchases, public posting or sharing. If login is needed, ask the user to sign in.

Do not silently shorten a supplied script. If it cannot fit, discuss an adjustment. Use the visible browser, respect the user's chosen browser, and reuse completed assets when resuming.

## Research and script

Research dates, locations, people, clothing, architecture, tools and events using reliable sources; retain source links separately. Distinguish documented facts from reconstruction, avoid invented dialogue and acknowledge uncertainty. Preserve supplied wording and flag substantive historical issues. Structure the film around context, human experience, causes, events and consequences. Explain building methods when relevant, but do not force a construction story onto unrelated subjects.

Write clear narration at a natural documentary pace, initially estimating 130-150 words per minute. Divide it at natural phrase boundaries into approximately ten-second scenes, adjusting to actual speech duration and available clip lengths. Plan each scene with its narration, timing, setting, action, camera and generation prompt. Keep internal identifiers out of generation prompts and visible footage.

## Visual style lock

Apply this style to every scene and any presenter unless the user chooses another style:

Cinematic frame from a high-budget European animated historical feature film, with painterly art-house 3D depth and hand-crafted atmosphere reminiscent of the broad visual tradition of Klaus (2019). Serious historical drama. Digital painting with dimensional form, matte non-glossy surfaces and visible rough brush strokes on skin, clothing, hair, wood, stone, metal, architecture and vegetation. Avoid glossy or clean CGI. Semi-stylized adult anatomy, approximately one head to five body heights, normal-length limbs and varied builds; no chibi or squat bodies. Visible characters have expressive oversized fleshy noses with rosy tips and large dark-dot eyes with small white catchlights. Natural poses and coherent hands. Warm, historically appropriate colors, directional atmospheric light, textured shadows and cinematic depth. Default to 16:9; use the chosen aspect ratio consistently.

This is a generated 3D-style animation aesthetic; do not claim that actual 3D models or rendered 3D scenes were built. Maintain consistent identity, costume, setting and lighting. Create character look cards and reference images where useful. Describe period-specific garments, tools, architecture and actions. Avoid anachronisms and unwanted text, logos and watermarks.

## Narration audio

1. Reuse existing completed narration for the production when available. Otherwise, use VideoExpress's Import Media → Text to Speech feature with the chosen language and voice when available (the inspected interface showed a 2,400-character limit). If unavailable, ask the user for a narration audio file or a preferred accessible voice tool. Never claim audio was generated if it was not.
2. Import or place the completed narration into the project using the visible audio controls. Record its actual duration and timeline boundaries. Wait for a generation to finish before submitting it again.
3. Preserve the complete narration and natural pacing. Do not regenerate, trim, split, time-stretch or change speed merely to force the estimate. If the actual duration exceeds the five-minute limit, report the conflict and ask how to proceed. If tool limits require separate audio segments, track their exact text and order and align them without missing words.
4. If a presenter is requested, include their speech in the total duration, use a consistent appearance and voice, and keep the speech audible. Start documentary narration at the actual presenter endpoint, or start a single narration track at the opening when there is no presenter. Avoid duplicate speech.

## Scene generation

1. Open https://app.videoexpress.ai/ in the visible browser. Set the chosen ratio and use Create Video From Prompt or the available image-to-video equivalent. Generate keyframes using the full style lock and accurate setting, clothing, lighting and action. Attach character references through the visible controls when supported. Before generating each asset, turn off and verify the 'Share this in the public gallery' checkbox; it may be enabled by default. Do not change visibility or publish without explicit authorization. Select Image Type: 3D when available, and keep the painterly style instructions in the prompt.
2. Inspect keyframes for identity, historical detail, anatomy and continuity before animation; repair defective images. Animate each image with achievable physical actions and purposeful camera movement. Use timed shots where helpful, but do not simultaneously request hard cuts and one continuous take. Use the app's available generation lengths.
3. Keep documentary clips silent or mute their generated audio beneath narration. Add music or ambience only if requested and keep narration clear. Use a cloned voice only with appropriate authorization.
4. Track each scene's narration interval and actual clip length. Generate enough footage to cover all narration; avoid gaps, repeated words and unnecessary repetition.

## Assembly and delivery

Arrange clips in story order and align visual changes to their corresponding narration phrases. Use actual durations. If video extends beyond the audio, split and remove only excess video at the audio endpoint; keep narration intact. If footage is too short, add coverage. Save and export using visible controls when available, and verify the resulting status. Do not publish, share or purchase without explicit authorization.

Check scene order, narration alignment, ratio, completed assets and timeline endpoints. Playback is optional unless the user asks for a listening or viewing review; do not claim to have heard narration or verified lip sync without doing so. Report the saved project, export status, actual duration, location and any limitations. Do not claim a video or audio file exists until it does.

## Tested VideoExpress workflow

The following sequence was tested with a private Roman aqueduct sample. The app's controls may change; verify the current UI before each action.

1. In Create with AI → Create Video From Prompt, select Landscape 16:9 and Image Type: 3D. Enter the historical image prompt and a separate camera-motion prompt. Turn off **Share this in the public gallery** and confirm it remains unchecked before generation. For the test, Creative mode was on and automatic image-prompt enhancement was off.
2. Select **Create Image** and wait for the generated image. Inspect it before proceeding. In Advanced Mode, enable **Video Only (No Sound)** and **Manual Video Length**, select 10 seconds, then submit **Create Video** once. Wait for the exact job to complete in Media Library → My AI Videos.
3. In Import Media → Text to Speech, select a language and voice, enter the scene narration, and select **Import Speech**. Wait for the confirmation that the audio was saved to My AI Audio. The observed text limit was 2,400 characters; segment longer narration without losing or repeating words.
4. Drag the matching video onto the upper timeline track and its narration onto a lower track, aligning their starts. Use the actual audio duration. Adjust only the video ending to match the audio; preserve the narration. Check the endpoints at the highest available timeline precision.
5. Save the project. Open **Export Video**, choose the available quality, resolution and format, then select **Create**. Wait for the named export to appear in **My Videos** before reporting it complete. The test produced an MP4; the app displayed a 50-day hosting notice, so advise the user to download their result.

Observed result: the test created a painterly 3D-style image, a ten-second silent source clip, and a roughly seven-second narration; both assets were placed at the timeline start, the video was shortened to the audio's approximate end, and the named project and MP4 export appeared in VideoExpress. The endpoints were aligned visually; audio quality, exact synchronization, playback and frame-accurate end alignment were not independently verified. Do not represent those checks as passed without actually performing them.
