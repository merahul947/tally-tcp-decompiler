# After recovery checklist

Recovered TDL is a starting point. Work through this list before using it in a live company.

1. **Use a test setup.** Load the recovered file in a separate Tally installation or a test company, never straight into live data.
2. **Check it loads.** Confirm Tally accepts the file without errors.
3. **Compare behaviour.** If you still have the original TCP running somewhere, compare reports, forms and calculations side by side.
4. **Rename unclear identifiers.** Obfuscated or generic names are easier to maintain once renamed to something meaningful.
5. **Add comments.** Original comments are not recovered, so document what each section does.
6. **Store it in version control.** Keep the recovered `.tdl` in Git so future changes are tracked.
7. **Keep the original TCP.** Archive it alongside the recovered source.
8. **Confirm you have the right to modify it.** Respect the original developer's licence terms.

Back to the [TCP to TDL guide](tcp-to-tdl-guide.md) or the [FAQ](faq.md).
