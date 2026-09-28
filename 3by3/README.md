# `3 * 3` Rubik's Cube Solver

## 1. Choose any color (white)

First, choose one color that you want to solve first.

For this guide, we will choose **white**.

## 2. Now look at the chosen opposite color (yellow)

The color opposite to white is **yellow**.

So, keep the **yellow center** facing you.

We will first create the white cross around the yellow center.

## 3. Now create white `+` shape on yellow side

Our first goal is to bring the four **white edge pieces** around the yellow center.

It should look like this:

```text
 ┌───┬───┬───┐
 │   │ W │   │
 ├───┼───┼───┤
 │ W │ Y │ W │
 ├───┼───┼───┤
 │   │ W │   │
 └───┴───┴───┘
```

Here:

- `Y` = yellow center
- `W` = white edge piece

Don't worry about the corners yet.

The important thing is to create a **white** `+` **shape** around the yellow center.

## 4. Match the side colors of the white cross

Now look at the four white edge pieces.

Each white edge piece has **two colors**.

Turn the cube until the second color of each white edge matches the center color of the corresponding side.

For example, if a white edge piece is:

```text
White + Red
```

then the red part should be aligned with the red center.

## 5. Move the matched white cross to the white side

Now the match edge turn to the white side.

Do this for all four white edges.

Once all four white edges are matched with their corresponding center colors, turn the cube so that the **white center is facing you/up**.

You should now have a proper white cross:

```text
 ┌───┬───┬───┐
 │   │ W │   │
 ├───┼───┼───┤
 │ W │ W │ W │
 ├───┼───┼───┤
 │   │ W │   │
 └───┴───┴───┘
```

The side colors should also match their center pieces.

## 6. Solve the white corners

Now find a corner piece containing **white**.

A white corner has three colors.

For example:

```text
White + Red + Green
```

This corner belongs between:

- White center
- Red center
- Green center

Move the corner into its correct position.

Repeat this for all four white corners.

When finished, the entire white face should be solved.

## 7. Solve the middle layer

Now ignore the white and yellow faces.

Look at the four edge pieces that do not contain yellow.

Move each edge piece into its correct position in the middle layer.

Repeat until all four middle-layer edges are solved.

## 8. Create a yellow cross

Now work on the yellow face.

Keep yellow face to top.

The goal is to create:

```text
 ┌───┬───┬───┐
 │   │ Y │   │
 ├───┼───┼───┤
 │ Y │ Y │ Y │
 ├───┼───┼───┤
 │   │ Y │   │
 └───┴───┴───┘
```

To create yellow `+` share apply this algorithm:

Keep that side on the right side that not have yellow edge.

```text
R B U B' U' R'
```

Keep applying the required moves until you get the yellow cross.
