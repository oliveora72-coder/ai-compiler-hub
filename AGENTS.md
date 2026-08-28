<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

# Lovable task

The project owner previously supplied a ZIP containing the mapper source and requested that the existing project/files from that ZIP be continued and modified, not replaced with a new unrelated implementation. The relevant ZIP available from the owner's previous work is `keysync-mouse-working-no-accel.zip`.

Use the existing mapper implementation/files that came from the previously supplied project as the basis for the work. Review the existing code and apply the requested changes to the relevant existing files.

Previously requested conditions:
- The current sensitivity is good as the baseline and should be preserved.
- Fix the moments when the sensitivity becomes too heavy.
- Remove the remaining acceleration from mouse/input movement so the response is consistent.
- The mapper has noticeable lag during gameplay, especially in the middle of a game; investigate the actual cause and fix it.
- Optimize mapper/overlay processing for low latency and stable input response.
- Preserve all existing functionality and previous changes from the supplied project.
- Do not replace the mapper with a simplified mock or unrelated implementation.
- Inspect the existing source and modify the relevant files from the previous project directly.

Continue from the existing implementation and verify that the requested fixes do not regress the working sensitivity or other mapper features.
