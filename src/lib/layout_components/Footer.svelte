<style>
    footer {
        font-size: 85%;

        display: grid;
        grid-auto-flow: column;
        grid-auto-columns: 1fr;
        gap: 3em;

        --r: min(1em, 2.5vw);
        padding: calc(var(--r) * 3) calc(var(--r) * 2) calc(var(--r) * 5);

        @media screen and (max-width: 45em) {
            grid-auto-flow: row;
        }

        ul,
        p {
            margin-top: 0;
            margin-bottom: 0.5em;
        }
    }
</style>

<footer class="shrink">
    <div>
        <ul>
            <li>
                <a href="/meta/team">Team</a>
            </li>
        </ul>
    </div>
    <div>
        <p>&copy; 2024 MCBÜ Kimono</p>
    </div>
</footer>
