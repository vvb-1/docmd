## VVB @claude (Claude Code Action)

Svara på svenska, kort. Gate-reglerna ligger i `.github/workflows/claude-gate.yml`.

- Ändra bara det Kristian ber om. Minsta korrekta ändring. Kör test/lint om det finns och redovisa resultatet.
- Commits går bara till aktuell PR-branch eller en ny `claude/`-branch. Aldrig main.
- Rör aldrig `.github/workflows/`, secrets, `.env*`, HDB116-/Trisys-kod eller migrations om Kristian inte uttryckligen ber om exakt det.
- Merga, approva eller gör aldrig om en PR till Draft.
