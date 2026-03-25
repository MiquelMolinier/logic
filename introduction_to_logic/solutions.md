# Basic Logical Concepts

## Exercise 1.1

01. A well-regulated militia being necessary to the security of a free state, the right of the people to keep and bear arms shall not be infringed.
Premise: A well-regulated militia is necessary for the security of a free state.
Conclusion: The right of the people to keep and bear arms shall not be infringed.
02. What stops many people from photocopying a book and giving it to a pal is not integrity but logistics; it’s easier and inexpensive to buy your friend a paperback copy.
Premise: It's easier and inexpensive to buy a paperback copy of a book.
Conclusion: Logistics stop many people from photocopying a book and giving it to a pal.
03. Thomas Aquinas argued that human intelligence is a gift from God and therefore “to apply human intelligence to understand the world is not an affront to God, but is pleasing to him.
Premise: Human intelligence is a gift from God.
Conclusion: To apply human intelligence to understand the world is pleasing to him.
04. Sir Edmund Hillary is a hero, not because he was the first to climb Mount Everest, but because he never forgot the Sherpas who helped him achieve this impossible feat. He dedicated his life to helping build schools and hospitals for them.
Premise 1: Sir Edmund Hillary never forgot the Sherpas who helped him to be the first to climb Mount Everest
Premise 2: He dedicated his life to helping build schools and hospitals for them.
Conclusion: Sir Edmund Hillary is a hero.
05. Standardized tests have a disparate racial and ethnic impact; white and Asian students score, on average, markedly higher than their black and Hispanic peers. This is true for fourth-grade tests, college entrance exams, and every other assessment on the books. If a racial gap is evidence of discrimination, then all tests discriminate.
X = {all that are standardized test}
Y = {all that contain racial gap}
Z = {all that contain discrimination}
Premise 1: All X is Y
Conclusion: All Y is Z then all X is Z
Proof:
(1) All X is Y
    (2) (All Y is Z) or not (All Y is Z) [Tautology]
        (2.1) not (All Y is Z) []
            (2.2) not (All Y is Z) or (All X is Z)
        (2.1) (All Y is Z) then (All X is Z)
        (3.1) (All Y is Z)
            (3.2) (All X is Y) and (All Y is Z)
            (3.3) (All X is Z)
        (3.1) (All Y is Z) then (All X is Z)
    (3) not (All Y is Z) then ((All Y is Z) then (All X is Z))
    (4) (All Y is Z) then ((All Y is Z) then (All X is Z))
    (5) (All Y is Z) or ((All Y is Z) then (All X is Z))
    (6) not (All Y is Z) or ((All Y is Z) then (All X is Z))
    (7){5,6} not ((All Y is Z) and not (All Y is Z)) or ((All Y is Z) then (All X is Z))
    (8){7} ((All Y is Z) and not (All Y is Z)) then ((All Y is Z) then (All X is Z))
    (9){2,8} ((All Y is Z) then (All X is Z))
(1) (All X is Y) then ((All Y is Z) then (All X is Z))
