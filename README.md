# eChessBoard

Pending a nicer name.

This is a project to create a low-ish budget chess board that records moves. With the addition of
LEDs, it could be used for online play as well, perhaps.

The main aim is to provide a way to export chess notation of a game as it was played over the board,
to allow importing said notation (be it FEN, PGN...) into chess software to analyze games afterwards.

## Motivation

Playing over the board is fun, but learning from mistakes is not really possible unless you manually
write down the moves, which can be cumbersome for casual play. There are existing products that solve
the same problem, but they are quite expensive. The cheapest option at the moment of writing seems to
be the Square Off PRO, but that's still £225, a lot of money.

---

This is in the early planning stages. Here's a block diagram of the electronics.

![Block diagram of basic electronics layout](https://raw.githubusercontent.com/michd/echessboard/images/basic_block_diagram.png?raw=true)

The LED driver / LED matrix is not confirmed, this might be more flexible with a string of 64
addressable RGB LEDs instead.
