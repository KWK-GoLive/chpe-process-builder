# ChPE Process Builder

A browser game from the **ChPE Open House**, Chemical and Process Engineering, Department of Chemical Engineering, Faculty of Engineering, Chulalongkorn University.

High-school students build a chemical plant on a board: they place storage tanks, pumps, heat exchangers, separators and product tanks around a fixed reactor, connect every pipe, set the conditions and press **Deploy** to see whether their plant works.

**Play:** https://kwk-golive.github.io/chpe-process-builder/

- **Example Process:** A + B → C + D + E, a simple teaching process built live by the teacher.
- **Competition:** CO₂ → methanol. Students join from the QR code on the projector.
- **Sandbox:** seven processes in Normal or Advanced mode.

The game is one self-contained file (`index.html`) and also works offline. The Example Process and the Sandbox send nothing: boards, points and times stay on the player's device.

**Class board (Competition only):** when the teacher runs the Competition with a class code, each student's device sends the class code, the nickname the student picks (not a real name), a random run ID made by the game (no personal data), the deploy count, the milestone reached, the points (0–100) and the time to the class board, a Google Sheet run by the department. Nothing else is sent.

The class board ranks by points, then by shorter time. Anyone who opens the board and types the class code can watch it read-only (nicknames, points, milestones, deploys and times); only the teacher can open, clear or download a class.

Every number in the game comes from a cited source, a calculation or a stated design assumption. The full reference list is on the game's **Sources** page.

© Department of Chemical Engineering, Chulalongkorn University. All rights reserved.
