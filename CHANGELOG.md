# House of Dice — what changed at the table

## v0.11.3 — "Same safe, new lock" (2026-07-20)

- Nothing at the table changes. Under the hood, the way your run survives
  a closed tab now runs on the shared engine's machinery — proven
  byte-for-byte identical to the old code, so the run you have going
  keeps resuming exactly as before.

## v0.11.2 — "The counter holds still" (2026-07-20)

- **The dealer's services stand still.** Arming *retire a die* or *sell a
  charm* used to shrink the button and drag the whole row around; now the
  armed service just lights up, and nothing at the counter moves while you
  choose. The dealer's patter swaps without shoving the shelf around,
  either.
- **"Back to the table" is always in reach.** On short screens the way out
  of the shop sat below the fold, a scroll away every single visit. The
  services row now rides the bottom of the screen whenever the counter
  runs taller than it.

## v0.11.1 — "The den fits your pocket" (2026-07-20)

- **Your score rides the top bar.** The night's running total now sits in
  the header next to the bag — you always know what the run is worth. Tap
  it and the history opens with the whole story so far.
- **The counter fits a phone.** The dealer's services — new stock, retire,
  sell a charm, back to the table — used to walk off the right edge of a
  phone screen. They now share it in tidy, even rows.
- **A full bag shows every die.** Ten dice at the counter wrap into rows
  you can actually read (and tap), instead of being crushed into one line.
- **The room stays the room.** Browsers with a forced "dark mode" (Brave's
  Night Mode, Chrome's auto-dark) were repainting the den — a white dealer,
  a muddy ledger. The den now declares its own darkness, and they leave the
  lamp alone.

## v0.11.0 — "The dealer buys regrets" (2026-07-20)

- **Sell a charm back.** A new standing service at the counter: *Sell a
  charm, +$2*. Tap it, pick the chip, and the charm is gone for the night —
  the dealer pays flat, asks no questions, and doesn't resell regrets. A
  blind pick doesn't brick your run anymore; whether it was *worth* $2 is
  between you and the shelf.

## v0.10.0 — "The night doubles down" (2026-07-20)

- **Some nights deal two rules.** About one night in five now comes with a
  second house rule on top of the first — a welcoming night with the taxman
  in, a crowded night short on sixes. A quiet night is still just quiet.
  Both rules show under the top bar, and both show in the run review.
- **Three new night rules.** *An open bar* — one more reroll every turn, on
  the house. *Last orders* — one reroll a turn; make it count. *The sixes
  never came* — the shipment ran short, and every 6 on your dice rolled
  over to a 1. The shop can still carve new ones, if you pay.
- **The night can bend the numbers, your rules still win.** Night rules may
  now adjust the house numbers for the length of the run (that's how the
  bar pours the extra reroll). If your own house-rule link touches the same
  number, yours wins — a challenge link plays exactly as written.
- **Plaques judge you, not the night.** The untouched-bag plaques now
  measure your dice against what the night dealt you: when the house grinds
  your sixes down at the door, that's the house's doing, and a bare-handed
  win still hangs the plaque.
- **The table was cleared once.** The save format changed for the rule
  lists: a night left mid-run on an older version won't resume — the next
  visit simply deals fresh. Records, plaques, and history all carry over.

## v0.9.2 — "The chairs are counted" (2026-07-19)

- **Tonight's Table knows its crowd.** The nightly offer now says how many
  sat tonight — "14 sat tonight's table." A number, never names: the same
  anonymous day-count the stats board already keeps, now visible where it
  matters. The line only appears when the count room answers; playing
  offline or from disk simply keeps it quiet.

## v0.9.1 — "New workshop, same table" (2026-07-19)

- **Nothing at your table moved.** The house changed workshops behind the
  scenes — the game is built from a new home now, on machinery shared with
  games yet to come. Same rooms, same dice, same odds, same everything. If
  you can spot a difference, we owe you a drink.

## v0.9.0 — "Change of rooms" (2026-07-19)

- **Pick your room.** The house keeps more than one room, and now you choose
  which you play in — a new room button (◑) up top opens a picker to switch
  between the den and the dungeon. Change it whenever you like, even mid-run:
  it's the same night, dealt exactly the same, only the skin changes. Your
  seed, your dice, your luck — all untouched.
- **A tidier top bar.** The run readouts (act, bag, money) are now framed as
  one group, and the controls are grouped by kind — a small cleanup for
  clarity.

## v0.8.4 — "Reconnect the wire" (2026-07-18)

- **The count room is actually plugged in again.** Everything 0.8.3 promised
  about your runs reaching the house was true in the game — but the last couple
  of builds shipped with the wire to the count room unplugged, so nothing was
  getting through. Reconnected. (No change to how you play.)

## v0.8.3 — "Second thoughts" (2026-07-18)

- **Are you sure?** On the last write of a round, if you pick an entry that
  *won't* take the round while another open one would, the house stops you
  once to ask. Easy to miss that you're down to your final turn and throw a
  winnable round away on the wrong box — now it checks. (Only when a win was
  actually on the table; it never nags otherwise.)
- **Your best runs now actually count.** A long night — especially a full
  clear — makes a big record, and the count room was quietly turning the
  biggest ones away at the door (they outgrew what the browser would send in
  one go). Fixed: the whole run gets through now, however far it ran. And if a
  send ever fails — a dropped connection, a closed tab — the game holds onto
  it and tries again next time you play. If you've cleared the house and
  wondered why it didn't show, this was why.

## v0.8.2 — "For your own good" (2026-07-18)

- **The set bonus says its name.** Fill the upper section — Ones through
  Sixes, no zeros — and the house has always paid a bonus for it. Now the
  ledger tells you the moment it lands: the entry that closes the set reads
  *"with the set,"* win or not, so the reward you just earned doesn't slip
  by unremarked.
- **Tidier tables.** Small housekeeping: your pockets no longer clutter the
  "?" tables where they were never in play, and the record book's upper
  tally only credits a bonus the house actually paid.
- **A favor, if you're up for it.** The house counts its tables —
  anonymously, no names, no faces (see v0.8.0). The more nights it sees, the
  better it can tune the odds. So if you're willing: leave the count on, or
  let the house remember your table across nights. Your call, always —
  "count me out" is one tap away, and the count room shows you every byte
  before you decide.
- **Soon: the house shows its numbers.** A public tally of how the room
  *really* does — win rates, how far the nights get, the high scores, who's
  made it upstairs to the Owner. No names, no faces, just the count. Watch
  this space.

## v0.8.1 — "Your call" (2026-07-18)

- **The house asks once.** The first time a run ends now, the count room
  puts the choice in front of you plainly: let the house remember your
  table across nights, keep the count anonymous as it already is, or tell
  it to count you out entirely. One card, one time — and whatever you pick,
  the count room stays open to change your mind. If you'd already made the
  call, the house doesn't ask again.

## v0.8.0 — "The count room" (2026-07-17)

- **The house counts its tables now.** When a run settles, a slip goes to
  the count room: how the night ended, how far it got — no names, no
  faces, nothing that ties one night to the next. A quiet line at the
  bottom of every settle says so, and tapping it opens the count room,
  where the actual slip sits under glass: every byte the house sends,
  readable before you decide anything. "Count me out" is right there, and
  the house honors it without argument.
- **Say the word, and the house remembers your table.** An offer, not a
  condition: volunteer an anonymous table mark and the house can watch a
  table grow across many nights — still no name, no face. Changed your
  mind? *The house forgets*, and it does: here and in the back room both.
- **A note for the house.** The report desk at the end of the night is
  gone; in its place, one line. Write what the night was like and it rides
  the same slip to management. Your own shelf keeps a copy with the run.

## v0.7.0 — "The wall" (2026-07-17)

- **The house keeps a wall now.** Your records grew a second page: a wall
  of plaques, one for every feat worth hanging. First loss, first back
  room, a clean run through all eight acts — and a chair for every keeper
  you've ever put away, filling in as you meet them. Some hang empty and
  dare you. A couple aren't on the wall at all until you've done the thing.
  Earn one mid-night and the house says so, right where your eyes are, and
  the records desk keeps them next to the ledger — on their own tab, so the
  shelf doesn't crowd them.
- **A new regular takes a late chair: the Leveler.** He spreads your dice
  in a neat row and slides every fourth one aside. No face counts past its
  third die at his table — three of a kind is a hand, he'll tell you, and
  five is showing off. Anyone who's stacked a single number into a cannon
  will find it firing blanks, deep in the night where he sits.
- **The Assayer takes a stool at the end of the bar.** A charm for the gold
  players at last: every gold die that scores now adds to the write, not
  just the pile — he bites each one before it counts, and they keep
  passing. Gold was always good money. Now it's good paper too.
- **Old seed links deal new nights** (a keeper seated, a charm on the
  shelf). The house apologizes to no one, as ever.

## v0.6.1 — "Turned-out pockets" (2026-07-17)

- **You can see your pockets now.** At the counter — and at the "?"
  tables — what you're holding shows above the shelf, next to your charms:
  each held item, each empty loop. The shelf plays fair in return: it
  says "one in your pocket already" when you're about to double up, and
  admits when your pockets are full instead of letting you find out the
  hard way.

## v0.6.0 — "Re-bound" (2026-07-17)

- **Some feats no longer go unwitnessed.** The house has always kept one
  particular account in perfect silence. It still won't say what it is —
  but the moment now gets the ceremony it always deserved, and late in an
  act, close to something, you may hear the house counting under its
  breath.
- **The Landlady takes the middle table.** Your charms don't work at her
  door — the rack stays on, the rack stays quiet. Bring dice, not jewelry.
- **The Regular moved deeper into the night.** He no longer wastes his
  chair on acts where nobody's instinct is worth taxing — act 4 at the
  earliest now.
- **The Pawnbroker buys anything.** Plain dice at the old price; glass
  and gold at a premium — he knows what they're worth. He'll also buy
  your last die, if you insist. The money is real. The game, unfortunately,
  was dice.
- **The night explains itself better.** Turns are pips you can count (Last
  Call's extra turn joins the row, cut square). A loss one write short
  tells you the bar was still open. The night review speaks your table's
  language everywhere — the crypt included, where five keepers and the
  Passing Bell finally learned their own tongues.
- **Stale bundles can't haunt live runs.** A cached old build can no
  longer wake up mid-night and deal retired rules onto your save — saves
  are stamped and checked now. Existing mid-run saves retire once,
  politely, with the update.
- **Old seed links deal new nights** (a chair moved, a keeper seated,
  the counter restocked). The house apologizes to no one, as ever.

## v0.5.0 — "New regulars" (2026-07-14)

- **Four new faces work the floor.** The Proofreader lays a ruler across
  your ledger — nothing gets rewritten at her table. The Regular charges
  for instinct — every reroll you don't spend costs points at write time.
  The Critic pays half for Chance and the of-a-kinds; show him structure.
  And The Rake draws a cut of your cash across the felt, every turn,
  without counting it.
- **The pools outgrew the chairs.** There are more keepers now than seats
  in a night. Some stay home; the veiled map still shows only the weight
  of what's waiting, so you can no longer be sure which of a class you'll
  meet. Plan for the family, not the face.
- **Last Call joins the shelf.** One more turn at this table, held until
  you need it. The dealer pretends not to notice the clock. Fifteen
  entries in one act has always been possible; now it's plannable.
- **Old seed links deal new nights.** New chairs and new stock draw their
  luck differently — a seed shared before tonight replays as a different
  evening. The house apologizes to no one, as ever.

## v0.4.2 — "Exact change" (2026-07-13)

- **The till learned to say no.** Arming a die-picker and then shopping
  around could let the pick go through on money you no longer had — the
  house was quietly extending credit. No longer: your funds are checked
  when the die is picked, not when the item was armed.
- **The Ledger Stamp quotes its real price.** It was charging tomorrow's
  price for today's stamp — every stamp cost more than the shelf tag said.
  The tag and the till agree now.
- **"Review the night" hears fresh runs.** The recent shelf only answered
  for older nights; a night finished minutes ago now opens like any other.

## v0.4.1 — "One per patron" (2026-07-13)

- **Lost Property honors a full shelf.** The hatch no longer greys out when
  you already carry five charms — claim, and something of yours goes back
  through it instead. Changing your mind costs nothing; the attendant
  doesn't look up either way.
- **Old nights say so.** Sitting back down at a run dealt under an earlier
  build, the table now tells you — "this night was dealt under v0.2.6, it
  plays out under its own rules." Your save always worked this way; now it
  admits it.

## v0.4.0 — "Tonight's Table" (2026-07-13)

- **The dealer keeps a special table now.** Every day deals one night — the
  same night for everyone who sits down to it, wherever they sit. Your first
  sitting is the official one; revenge is allowed, and marked. One tap on the
  settle screen shares the card — spoiler-light, group-chat sized, with a
  link that deals the same night fresh for whoever thinks they'd have played
  it better.
- **The keepers formed weight classes.** The light company works the early
  acts, the heavier ones wait deeper in, and the House still takes the last
  chair. The map now keeps their confidence: tonight's keeper shows face and
  rule, the rest of the evening shows only a veiled portrait and the weight
  of what's waiting.
- **Old seed links deal new nights.** The new seating draws its luck
  differently, so a seed shared before tonight replays as a different
  evening. The night you shared is gone; the house apologizes to no one.
- **The back office grew more dials.** Nearly every number the house keeps
  is now a house rule you can bend — and one new rule for the brave:
  `bosses.revealHorizon = 0` plays the whole night blind.

## v0.3.0 — "The house gets a wardrobe" (2026-07-12)

- **Nothing at your table changed.** Every deal, price, and payout is
  the same to the byte — the house checked, twice, against its own books.
- **Under the felt, the game learned to wear other clothes.** The words
  now live apart from the works. The curious can try `?theme=dungeon` —
  a crypt: every round an enemy, the target its HP, the prices in teeth.
  Same dice. Same odds. Older light.

## v0.2.10 — "The stamp learns arithmetic" (2026-07-12)

- **The stamp learned arithmetic.** Each level already inked makes the
  next Ledger Stamp dearer. The first one costs what it always cost;
  the tenth costs what a tenth stamp is worth to the kind of person
  who buys ten.
- **The Notary keeps his appointment.** One back-room table per night,
  guaranteed. Whether you have his price is your business.

## v0.2.9 — "The first playtests speak" (2026-07-12)

- **The deed got scarcer.** A regular sells his piece once a night —
  the whole deed no longer assembles off the regulars alone. One piece
  per source; the house does not repeat itself.
- **The Owner asks less, and means it.** The fight upstairs demands
  three times the natural curve, not five. Every playtest that reached
  the door died against the old number; now the door is the hard part
  and the fight is a fight.
- **First Instinct counts to two.** Unspent rerolls beyond the second
  no longer pay. The first thought was correct; the sixth was greed.
- **The ink runs thinner.** A reopened ledger entry pays three quarters.
  The stamped-Chance printing press still prints — the paper is just
  worth what reopened paper is worth.
- **The house remembers every night now.** A recent-nights shelf under
  the records keeps your last ten runs — the losses too. Any reviewed
  night can be downloaded as the full report, and a saved page carries
  its whole trace inside it.
- **Every review states its table.** Seed and the version the run was
  born under, right in the summary — no more guessing which rules dealt
  the night.

## v0.2.8 — "The arrangement" (2026-07-11)

- **Some tables can be folded.** A certain charm lets you buy your way
  out of a round going wrong: pay, the table looks away, and the night
  simply continues. Nothing is paid out — you didn’t win, you paid.
- **Deciding late is the expensive part.** Fold early and the dealer
  offers a discount for the good read. Wait until the last write and
  it costs the full price. He does arithmetic, not favors.
- **Even the regulars have a price.** Double, at their chairs. They
  take it without counting it — and leave nothing behind.
- **Some things are not for sale.** The last table of the night holds
  its own paper. And upstairs, money is not what changes hands.
- **Where to find it? Not on any winner’s table.** Arrangements are
  made where the house does its quieter business. Watch the drawer.
  And check lost property — its previous owner stopped needing it.

*The house checked the books: the odds of the night did not move.
This is a matter of style. The house respects style.*

## v0.2.7 — "The back office" (2026-07-11)

- **The house takes requests now.** A shared link can deal more than a
  seed: it can bend the numbers — targets, prices, payouts — and the
  night plays out under those house rules for whoever opens it. The
  table wears a gold **CUSTOM RULES** notice all night; click it for
  the fine print, next to what the house would normally charge.
- **Records tell the truth.** A night under house rules goes on the
  board as one — tagged, itemized, stamped into the review and the
  report. The house does not launder results.
- **Links knock first.** Following a shared night while yours is still
  going now asks — sit back down, or take the dare. Nothing is lost
  until you choose.
- **The back office is open. Quietly.** Somewhere behind the house
  rules card, management keeps a door. Behind it: every number the
  house runs on, editable, and a fresh deck. Deal it, or pocket it as
  a link. The house will allow it. Once.

*Mid-run saves carry over. Custom nights wake up custom.*

## v0.2.6 — "The front door sticks less" (2026-07-11)

- **The night was re-tuned.** Gentler at the door. No kinder upstairs.
- Prices changed. The dealer will not be taking questions.

*Mid-run saves wake up under the new numbers. The house honors old
debts. At new rates.*

## v0.2.5 — "Paperwork" (2026-07-10)

- **A piece of paper has entered the building.** The house declines to
  elaborate.
- Housekeeping under the felt: every number the house runs on now lives
  in one ledger of its own. Same game, tidier books. You won't notice.
  That's the point.

*Mid-run saves carry over, as always. The house honors old debts.*

## v0.2.4 — "The house keeps the tapes" (2026-07-10)

- **Old nights can be reviewed.** Every run that makes the records from
  now on keeps its full story — expand a records row and "Review the
  night" replays it round by round: the dice, the holds, the charms
  firing, what you bought between hands. Records from before tonight
  were kept the old way; the house didn't tape those.
- **Reviews can leave the building.** "Save as page" on any review
  downloads it as a single file — send a friend the whole night, no
  game required. Pairs well with sharing the seed.
- The dealer no longer greets you with an empty speech bubble when you
  come back mid-shopping. He says something. He always says something.

## v0.2.3 — "Management has had a word" (2026-07-10)

- **The dealer was rounding in his own favor.** Every Wild Face since
  the prices started climbing charged a dollar over the number on the
  shelf — in a bad moment it could even put you in the red. Fixed: you
  pay exactly what the tag says. Management apologizes for nothing,
  but the books are correct now.
- **You can think better of it.** Buying a charm with a full shelf no
  longer commits you on the spot — the "make room" choice can be
  walked away from (button, ×, or Esc). Nothing is paid until you
  actually let something go. Backing out of a regular's charm returns
  you to the choice, cash option included.

## v0.2.2 — "Forgeries, priced accordingly" (2026-07-10)

- **Copying a ★ with a Loaded Face now costs like the scarce thing it
  forges** — the more wilds you own, the more a ★-copy runs. An honest
  copy of a six stays $4, always.
- **Both prices are on the tag** before you choose — the shelf reads
  "$4 · ★ $9", and the dealer quotes you again while you pick the die.
  The house is many things. Coy about money isn't one.

## v0.2.1 — "The notice actually gets posted" (2026-07-10)

- The management notice now reaches players who were here before the
  house started posting notices. Which was everyone.
- The number in the corner tells you which build you're on, not which
  build your run remembers. Click it any time to reread the notices.

## v0.2.0 — "The night has a number" (2026-07-10)

- **Every night has a number now.** The same seed deals the same night —
  dice, shop, visitors, all of it. Finish a run and share its number;
  see if a friend survives what you survived. Paste a seed on the front
  door to play someone else's night.
- **Three new night rules** joined the rotation. Harder. Weirder. The
  house doesn't apologize.
- **Wild Faces got scarcer.** The price climbs with every ★ you already
  own. The good ones get scarce — the dealer always said so, and now
  the shelf agrees.
- **First Instinct only trusts your own hands.** Rerolls banked up a
  sleeve no longer count toward it — the reroll button shows the split,
  so you always know which is which.
- The night's report now records shelf rerolls too. The bookkeeping
  sees you fishing.
- Plays properly on phones now. End-of-run screens say more; modals
  close the way you expect; the build number sits quietly in the
  corner.

*Mid-run saves from v0.1.0 carry over — an in-flight run just wakes up
under the new prices. The house honors old debts. At new rates.*

## v0.1.0 — "The doors open" (2026-07-08)

The first public night. Eight acts, a shuffled table of regulars, a
counter that sells you rope and calls it a lifeline. Everything works;
nothing is safe. Pull up a chair.

*The ledger keeps its own private notes on every hand you play — the
house calls it bookkeeping. If a night ever feels off, the "Review the
night" button will show you exactly where it went.*
