# Chess, Clearly

**[Read the GitHub Pages collection](https://knightway8.github.io/chess15/)**

Sixteen direct lessons in seeing and understanding the board.

Begin here if piece movement, checks, or notation still feel uncertain.

## Format

- 16 direct lessons, each a self-contained HTML file with its own styles and embedded vector chess pieces.
- 32 lesson diagrams: the starting position and the result of the fully explained line.
- Visible explanations throughout: no answer inputs, hidden solutions, scores, progress controls, or client-side JavaScript.
- One printable collection, Markdown notes, and PGN move sequences.

A single lesson can be saved or copied on its own and read offline. Navigation to other lessons requires those neighboring files, but the lesson text and diagrams do not. Open [collection.html](collection.html) and use your browser’s Print command to print or save as PDF.

## Lessons

1. [Every square has a permanent address](lessons/01-every-square-has-a-permanent-address.html)
2. [A rook stops at the first obstacle](lessons/02-a-rook-stops-at-the-first-obstacle.html)
3. [A bishop always keeps its square color](lessons/03-a-bishop-always-keeps-its-square-color.html)
4. [A knight jumps, then lands](lessons/04-a-knight-jumps-then-lands.html)
5. [Pawns move one way and capture another](lessons/05-pawns-move-one-way-and-capture-another.html)
6. [A king cannot capture a defended piece](lessons/06-a-king-cannot-capture-a-defended-piece.html)
7. [Blocking a check closes the attacking line](lessons/07-blocking-a-check-closes-the-attacking-line.html)
8. [Capture the checker only when the capture ends the check](lessons/08-capture-the-checker-only-when-the-capture-ends-the-check.html)
9. [Castling moves the king and rook together](lessons/09-castling-moves-the-king-and-rook-together.html)
10. [An attacked transit square prevents castling](lessons/10-an-attacked-transit-square-prevents-castling.html)
11. [En passant is an immediate pawn capture](lessons/11-en-passant-is-an-immediate-pawn-capture.html)
12. [Promotion creates a new piece immediately](lessons/12-promotion-creates-a-new-piece-immediately.html)
13. [Read notation as a short description of a move](lessons/13-read-notation-as-a-short-description-of-a-move.html)
14. [Checkmate means every legal defense fails](lessons/14-checkmate-means-every-legal-defense-fails.html)
15. [Stalemate can turn a won position into a draw](lessons/15-stalemate-can-turn-a-won-position-into-a-draw.html)
16. [Count the whole exchange, not its first capture](lessons/16-count-the-whole-exchange-not-its-first-capture.html)

## Four companion collections

| Repository | Collection | Live site |
| --- | --- | --- |
| [chess15](https://github.com/knightway8/chess15) | Chess, Clearly | [Read](https://knightway8.github.io/chess15/) |
| [chess16](https://github.com/knightway8/chess16) | Openings, Explained | [Read](https://knightway8.github.io/chess16/) |
| [chess17](https://github.com/knightway8/chess17) | Tactics, Made Visible | [Read](https://knightway8.github.io/chess17/) |
| [chess18](https://github.com/knightway8/chess18) | Endgames, Step by Step | [Read](https://knightway8.github.io/chess18/) |

## Verification and maintenance

[Sources and verification](sources.html) explains the scope. [VERIFICATION.json](VERIFICATION.json) records legal move, diagram, PGN, self-containment, and directory-size checks. The endgame collection also includes exact tablebase results. Illustrative tactical continuations are not claims of exhaustive analysis.

Edit [source/course.json](source/course.json), run `node tools/build.mjs`, then run `node tools/verify.cjs`. All directories must remain below 1,000 entries.

GitHub Pages publishes the root of `main` through `.nojekyll`. Default-branch rules require pull requests and block force pushes and branch deletion, without bypass actors. An owner can still alter settings or delete a repository.

## Credits

Original AI-created lessons prepared for knightway8. Cburnett pieces by Colin M. L. Burnett are supplied under GPL-2.0-or-later, with [unmodified SVG sources, provenance, and license](source/pieces/README.md). The artwork’s full license is also embedded as a comment in each standalone HTML file. chess.js is used for authoring checks under its [BSD-2-Clause license](vendor/chess-LICENSE.txt).
