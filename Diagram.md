# Surfboard selection flowchart

``` mermaid
flowchart LR
    A[My surfing level is:] ---- B(Beginner)
    B ----> E(Swimming competency) ---- F(Pro)
    E ---- G(Joe)
    F ---- H{"Midlength board (add about 1 ft to your height for the length)"}
    G ---- I{Softtop board at least 2ft taller than your height}
    A ---- C(Intermediate)
    C ---- C1(Surfing style preference?)
    C1 ---- C2(Shortboard)
    C1 ---- C3(Longboard)
    C2 ---- C4(Get a shortboard about your height with plenty of thickness)
    C3 ---- C5(How big are the waves?)
    C5 ---- C6(Big)
    C6 ---- C8{Performance longboard, or something with extra rocker}
    C5 ---- C7(Not so big)
    C7 ---- C9{Clasic longboard 8ft plus}
    A ---- D(Advanced)
    D ---- J(How often are you surfing?)
    J ---- J1(Almost every day)
    J1 ---- K{You'll want at least two shortboards. One for big waves and one for small waves.}
    J ---- J2(Once a week)
    J2 ---- K1{Get a shortboard that's easy and fun to surf. Maybe a little extra volume. Something that can handle bigger waves too.}
    J ---- J3(Once in a while)
    J3 ---- K1

