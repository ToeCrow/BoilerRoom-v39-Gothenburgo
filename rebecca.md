.about-box {
    display: grid;
    grid-template-rows: 1fr auto auto;
    grid-template-columns: 1fr 1fr;
    grid-template-areas: 
    "name . picture"
    ". . picture"
    "description description description"
    ;

    /* border: 1px solid #827f4a; */
    border-radius: 12px;
    box-shadow: #1f1f1f;

    /* box placement */
    gap: 1rem;
    padding: inherit;
    padding-top: 1.5rem;

    /* box sizing */
    width: clamp(20rem, 40rem, 40rem);
    min-height: 15rem;
}