---
title: "Library"
icon_svg: "library"
layout: "page"
description: "My Library"
ShowBreadCrumbs: false
disableAnchoredHeadings: true
---

<style>
    input {
        color: var(--primary);
    }
</style>

This is my library. I keep it up to date as best I can, but the most up-to-date list is on my [Hardcover.app profile](https://hardcover.app/@jshmnrd?referrer_id=98561).

<details>
    <summary><b>Updates coming soon:</b></summary>
    <ul>
        <li><a href="https://hardcover.app/@jshmnrd?referrer_id=98561" target="_blank">Hardcover.app</a> links</li>
        <li>ISBNs</li>
        <li>Read/not-read checkboxes</li>
    </ul>
    <details>
        <summary>Recently completed</summary>
        <ul>
            <li><s>Goodreads links</s></li>
            <li><s>Bookwyrm links</s></li>
            <li><s>Format (in what format do I own the book)</s></li>
        </ul>
    </details>
</details>

---

<div id="book-list">
    <input class="search" placeholder="Search books..." /><br>
    <b>Sort by:</b>&emsp;
    <span onMouseOver="this.style.color='var(--darkcolor)'" onMouseOut="this.style.color='var(--primary)'">[ <button class="sort" data-sort="id" onMouseOver="this.style.color='var(--darkcolor)'" onMouseOut="this.style.color='var(--primary)'">ID</button> ]</span>&emsp;
    <span onMouseOver="this.style.color='var(--darkcolor)'" onMouseOut="this.style.color='var(--primary)'">[ <button class="sort" data-sort="title" onMouseOver="this.style.color='var(--darkcolor)'" onMouseOut="this.style.color='var(--primary)'">Title</button> ]</span>&emsp;
    <span onMouseOver="this.style.color='var(--darkcolor)'" onMouseOut="this.style.color='var(--primary)'">[ <button class="sort" data-sort="author" onMouseOver="this.style.color='var(--darkcolor)'" onMouseOut="this.style.color='var(--primary)'">Author</button> ]</span>&emsp;
    <span onMouseOver="this.style.color='var(--darkcolor)'" onMouseOut="this.style.color='var(--primary)'">[ <button class="sort" data-sort="series" onMouseOver="this.style.color='var(--darkcolor)'" onMouseOut="this.style.color='var(--primary)'">Series</button> ]</span>&emsp;
    <span onMouseOver="this.style.color='var(--darkcolor)'" onMouseOut="this.style.color='var(--primary)'">[ <button class="sort" data-sort="sernum" onMouseOver="this.style.color='var(--darkcolor)'" onMouseOut="this.style.color='var(--primary)'">Series #</button> ]</span>&emsp;
    <span onMouseOver="this.style.color='var(--darkcolor)'" onMouseOut="this.style.color='var(--primary)'">[ <button class="sort" data-sort="formats" onMouseOver="this.style.color='var(--darkcolor)'" onMouseOut="this.style.color='var(--primary)'">Formats</button> ]</span>&emsp;
    <table>
        <thead>
            <tr>
                <th title="Field #1">ID</th>
                <th title="Field #2">Title</th>
                <th title="Field #3">Author</th>
                <th title="Field #4">Series</th>
                <th title="Field #5">#</th>
                <th title="Field #6">Links</th>
                <th title="Field #7">Formats</th>
            </tr>
        </thead>
        <tbody class="list" style="vertical-align:top;">
            <tr>
                <td class="id">001</td>
                <td class="title">1984</td>
                <td class="author">George Orwell</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/223781648-1984" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/123932/s/1984" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">002</td>
                <td class="title">The Adventures of Tom Bombadil</td>
                <td class="author">J.R.R. Tolkien</td>
                <td class="series">Middle Earth</td>
                <td class="sernum">1.5</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/35736.The_Adventures_of_Tom_Bombadil" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/214513/s/the-adventures-of-tom-bombadil" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">003</td>
                <td class="title">The Ballad of Songbirds and Snakes</td>
                <td class="author">Suzanne Collins</td>
                <td class="series">The Hunger Games</td>
                <td class="sernum">0</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/51901147-the-ballad-of-songbirds-and-snakes" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/1972735/s/the-ballad-of-songbirds-and-snakes" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">004</td>
                <td class="title">The Bhagavad Gita</td>
                <td class="author">Eknath Easwaran</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/99944.The_Bhagavad_Gita" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/268412/s/the-bhagavad-gita" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">005</td>
                <td class="title">Bilbo's Last Song</td>
                <td class="author">J.R.R. Tolkien</td>
                <td class="series">Middle Earth</td>
                <td class="sernum">4.5</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/67939.Bilbo_s_Last_Song" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/417889/s/bilbos-last-song" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">006</td>
                <td class="title">The Catcher in the Rye</td>
                <td class="author">J.D. Salinger</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/5107.The_Catcher_in_the_Rye" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/496/s/the-catcher-in-the-rye" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">007</td>
                <td class="title">Catching Fire</td>
                <td class="author">Suzanne Collins</td>
                <td class="series">The Hunger Games</td>
                <td class="sernum">2</td>
                <td class="links"><a href="https://www.goodreads.com/search?q=CATCHING%20FIRE" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/342486/s/catching-fire-the-hunger-games-2" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">008</td>
                <td class="title">Chapterhouse: Dune</td>
                <td class="author">Frank Herbert</td>
                <td class="series">Dune</td>
                <td class="sernum">6</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/44439416-chapterhouse" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/129669/s/chapterhouse-dune" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">009</td>
                <td class="title">Children of Dune</td>
                <td class="author">Frank Herbert</td>
                <td class="series">Dune</td>
                <td class="sernum">3</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/44492286-children-of-dune" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/129673/s/children-of-dune" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">010</td>
                <td class="title">A Christmas Carol</td>
                <td class="author">Charles Dickens</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/5326.A_Christmas_Carol" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/147197/s/a-christmas-carol" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">011</td>
                <td class="title">A Clash of Kings</td>
                <td class="author">George R.R. Martin</td>
                <td class="series">ASOIAF</td>
                <td class="sernum">2</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/10572.A_Clash_of_Kings" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/6603/s/a-clash-of-kings" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">012</td>
                <td class="title">A Conjuring of Light</td>
                <td class="author">V.E. Schwab</td>
                <td class="series">Shades of Magic</td>
                <td class="sernum">3</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/29939230-a-conjuring-of-light" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/102212/s/a-conjuring-of-light" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">013</td>
                <td class="title">The Creative Act: A Way of Being</td>
                <td class="author">Rick Rubin</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/60965426-the-creative-act" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/691722/s/the-creative-act-a-way-of-being" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">014</td>
                <td class="title">A Dance with Dragons</td>
                <td class="author">George R.R. Martin</td>
                <td class="series">ASOIAF</td>
                <td class="sernum">5</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/10664113-a-dance-with-dragons" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/147946/s/a-dance-with-dragons" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">015</td>
                <td class="title">The Dark Tower</td>
                <td class="author">Stephen King</td>
                <td class="series">The Dark Tower</td>
                <td class="sernum">7</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/5091.The_Dark_Tower" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/208478/s/the-dark-tower-the-dark-tower-book-7" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">016</td>
                <td class="title">A Darker Shade of Magic</td>
                <td class="author">V.E. Schwab</td>
                <td class="series">Shades of Magic</td>
                <td class="sernum">1</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/22055262-a-darker-shade-of-magic" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/38240/s/a-darker-shade-of-magic" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">017</td>
                <td class="title">Demon in the Wood</td>
                <td class="author">Leigh Bardugo</td>
                <td class="series">Shadow and Bone</td>
                <td class="sernum">0.5</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/59785164-demon-in-the-wood" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/381028/s/demon-in-the-wood-graphic-novel" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">018</td>
                <td class="title">Doctor Sleep</td>
                <td class="author">Stephen King</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/16130549-doctor-sleep" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/56113/s/doctor-sleep" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">019</td>
                <td class="title">The Drawing of the Three</td>
                <td class="author">Stephen King</td>
                <td class="series">The Dark Tower</td>
                <td class="sernum">2</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/5094.The_Drawing_of_the_Three" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/21573/s/the-drawing-of-the-three" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">020</td>
                <td class="title">Dune</td>
                <td class="author">Frank Herbert</td>
                <td class="series">Dune</td>
                <td class="sernum">1</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/44767458-dune" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/46029/s/dune" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">021</td>
                <td class="title">Dune Messiah</td>
                <td class="author">Frank Herbert</td>
                <td class="series">Dune</td>
                <td class="sernum">2</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/44492285-dune-messiah" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/130225/s/dune-messiah" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">022</td>
                <td class="title">The Enchiridion</td>
                <td class="author">Epictetus</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/24615.Enchiridion" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/199628/s/enchiridion" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">023</td>
                <td class="title">A Feast for Crows</td>
                <td class="author">George R.R. Martin</td>
                <td class="series">ASOIAF</td>
                <td class="sernum">4</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/13497.A_Feast_for_Crows" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/6595/s/a-feast-for-crows" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">024</td>
                <td class="title">The Fellowship of the Ring</td>
                <td class="author">J.R.R. Tolkien</td>
                <td class="series">Middle Earth</td>
                <td class="sernum">2</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/13356706-the-fellowship-of-the-ring" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/126992/s/the-fellowship-of-the-ring" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Print</td>
            </tr>
            <tr>
                <td class="id">025</td>
                <td class="title">A Game of Thrones</td>
                <td class="author">George R.R. Martin</td>
                <td class="series">ASOIAF</td>
                <td class="sernum">1</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/13496.A_Game_of_Thrones" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/8043/s/a-game-of-thrones" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">026</td>
                <td class="title">A Gathering of Shadows</td>
                <td class="author">V.E. Schwab</td>
                <td class="series">Shades of Magic</td>
                <td class="sernum">2</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/20764879-a-gathering-of-shadows" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/39782/s/a-gathering-of-shadows" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">027</td>
                <td class="title">God Emperor of Dune</td>
                <td class="author">Frank Herbert</td>
                <td class="series">Dune</td>
                <td class="sernum">4</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/44439415-god-emperor-of-dune" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/130222/s/god-emperor-of-dune" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">028</td>
                <td class="title">The Great Gatsby</td>
                <td class="author">F. Scott Fitzgerald</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/57346727-the-great-gatsby---reader-s-library-classic" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/4898/s/the-great-gatsby" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">029</td>
                <td class="title">Greenlights</td>
                <td class="author">Matthew McConaughey</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/213156035-greenlights" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/107577/s/greenlights" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">030</td>
                <td class="title">The Gunslinger</td>
                <td class="author">Stephen King</td>
                <td class="series">The Dark Tower</td>
                <td class="sernum">1</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/247642509-the-gunslinger" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/106059/s/the-dark-tower-i" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">031</td>
                <td class="title">Harry Potter and the Chamber of Secrets</td>
                <td class="author">J.K. Rowling</td>
                <td class="series">Harry Potter</td>
                <td class="sernum">2</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/15881.Harry_Potter_and_the_Chamber_of_Secrets" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/6123/s/harry-potter-and-the-chamber-of-secrets" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">032</td>
                <td class="title">Harry Potter and the Cursed Child</td>
                <td class="author">J.K. Rowling</td>
                <td class="series">Harry Potter</td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/29056083-harry-potter-and-the-cursed-child" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/120105/s/harry-potter-and-the-cursed-child" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">033</td>
                <td class="title">Harry Potter and the Deathly Hallows</td>
                <td class="author">J.K. Rowling</td>
                <td class="series">Harry Potter</td>
                <td class="sernum">7</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/58613224-harry-potter-and-the-deathly-hallows" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/122887/s/harry-potter-and-the-deathly-hallows" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">034</td>
                <td class="title">Harry Potter and the Goblet of Fire</td>
                <td class="author">J.K. Rowling</td>
                <td class="series">Harry Potter</td>
                <td class="sernum">4</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/58613424-harry-potter-and-the-goblet-of-fire" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/228347/s/harry-potter-and-the-goblet-of-fire" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">035</td>
                <td class="title">Harry Potter and the Half-Blood Prince</td>
                <td class="author">J.K. Rowling</td>
                <td class="series">Harry Potter</td>
                <td class="sernum">6</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/58613345-harry-potter-and-the-half-blood-prince" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/5582/s/harry-potter-and-the-half-blood-prince" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">036</td>
                <td class="title">Harry Potter and the Order of the Phoenix</td>
                <td class="author">J.K. Rowling</td>
                <td class="series">Harry Potter</td>
                <td class="sernum">5</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/58613451-harry-potter-and-the-order-of-the-phoenix" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/7723/s/harry-potter-and-the-order-of-the-phoenix" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">037</td>
                <td class="title">Harry Potter and the Philosopher's Stone</td>
                <td class="author">J.K. Rowling</td>
                <td class="series">Harry Potter</td>
                <td class="sernum">1</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/42844155-harry-potter-and-the-philosopher-s-stone" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/6055/s/harry-potter-and-the-philosophers-stone" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">038</td>
                <td class="title">Harry Potter and the Prisoner of Azkaban</td>
                <td class="author">J.K. Rowling</td>
                <td class="series">Harry Potter</td>
                <td class="sernum">3</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/5.Harry_Potter_and_the_Prisoner_of_Azkaban" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/6203/s/harry-potter-and-the-prisoner-of-azkaban" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">039</td>
                <td class="title">Heretics of Dune</td>
                <td class="author">Frank Herbert</td>
                <td class="series">Dune</td>
                <td class="sernum">5</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/44492287-heretics-of-dune" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/21513/s/heretics-of-dune-dune-chronicles-book-5" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">040</td>
                <td class="title">The Hobbit, or There and Back Again</td>
                <td class="author">J.R.R. Tolkien</td>
                <td class="series">Middle Earth</td>
                <td class="sernum">1</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/5907.The_Hobbit_or_There_and_Back_Again" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/1165963/s/the-hobbit" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Print</td>
            </tr>
            <tr>
                <td class="id">041</td>
                <td class="title">Holly</td>
                <td class="author">Stephen King</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/65916344-holly" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/1373489/s/holly" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">042</td>
                <td class="title">The Hunger Games</td>
                <td class="author">Suzanne Collins</td>
                <td class="series">The Hunger Games</td>
                <td class="sernum">1</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/2767052-the-hunger-games" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/16953/s/the-hunger-games" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">043</td>
                <td class="title">Hunters of Dune</td>
                <td class="author">Frank Herbert</td>
                <td class="series">Dune</td>
                <td class="sernum">7</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/20249.Hunters_of_Dune" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/23974/s/hunters-of-dune" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">044</td>
                <td class="title">The Iliad</td>
                <td class="author">Homer</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/77265004-the-iliad" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/1225201/s/the-iliad" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">045</td>
                <td class="title">In the Buddha's Words</td>
                <td class="author">Bhikku Bodhi</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/209576.In_the_Buddha_s_Words" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/114472/s/in-the-buddhas-words" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">046</td>
                <td class="title">The Institute</td>
                <td class="author">Stephen King</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/43798285-the-institute" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/169218/s/the-institute" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook, Print</td>
            </tr>
            <tr>
                <td class="id">047</td>
                <td class="title">The Invisible Life of Addie LaRue</td>
                <td class="author">V.E. Schwab</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/50623864-the-invisible-life-of-addie-larue" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/191867/s/the-invisible-life-of-addie-larue" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">048</td>
                <td class="title">It</td>
                <td class="author">Stephen King</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/830502.It" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/1682317/s/it" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">049</td>
                <td class="title">The Little Sisters of Eluria</td>
                <td class="author">Stephen King</td>
                <td class="series">The Dark Tower</td>
                <td class="sernum">0.5</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/6356190-the-little-sisters-of-eluria" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/411445/s/the-little-sisters-of-eluria" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">050</td>
                <td class="title">Lord of the Flies</td>
                <td class="author">William Golding</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/7624.Lord_of_the_Flies" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/453/s/lord-of-the-flies" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">051</td>
                <td class="title">The Martian</td>
                <td class="author">Andy Weir</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/18007564-the-martian" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/175316/s/the-martian" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">052</td>
                <td class="title">Meditations</td>
                <td class="author">Marcus Aurelius</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/233411514-meditations" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/123985/s/meditations" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">053</td>
                <td class="title">The Midnight Library</td>
                <td class="author">Matt Haig</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/52578297-the-midnight-library" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/668773/s/the-midnight-library" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">054</td>
                <td class="title">Moby Dick, or The Whale</td>
                <td class="author">Herman Melville</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/153747.Moby_Dick_or_The_Whale" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/789249/s/moby-dick-or-the-whale" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">055</td>
                <td class="title">Mockingjay</td>
                <td class="author">Suzanne Collins</td>
                <td class="series">The Hunger Games</td>
                <td class="sernum">3</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/7260188-mockingjay" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/16823/s/mockingjay" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">056</td>
                <td class="title">Nicomachean Ethics</td>
                <td class="author">Aristotle</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/19068.The_Nicomachean_Ethics" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/269588/s/the-nicomachean-ethics" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">057</td>
                <td class="title">The Nightjar</td>
                <td class="author">Deborah Hewitt</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/43263556-the-nightjar" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/555563/s/the-nightjar" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">058</td>
                <td class="title">The Odyssey</td>
                <td class="author">Homer</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/1381.The_Odyssey" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/17616/s/the-odyssey" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">059</td>
                <td class="title">Peter Nimble and His Fantastic Eyes</td>
                <td class="author">Jonathan Auxier</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/10806008-peter-nimble-and-his-fantastic-eyes" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/675591/s/peter-nimble-and-his-fantastic-eyes" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">060</td>
                <td class="title">Quidditch through the Ages</td>
                <td class="author">J.K. Rowling</td>
                <td class="series">Harry Potter</td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/111450.Quidditch_Through_the_Ages" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/28621/s/quidditch-through-the-ages" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">061</td>
                <td class="title">Ready Player One</td>
                <td class="author">Ernest Cline</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/9969571-ready-player-one" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/6933/s/ready-player-one" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">062</td>
                <td class="title">The Republic</td>
                <td class="author">Plato</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/30289.The_Republic" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/146466/s/the-republic" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">063</td>
                <td class="title">Return of the King</td>
                <td class="author">J.R.R. Tolkien</td>
                <td class="series">Middle Earth</td>
                <td class="sernum">4</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/601137.The_Return_of_the_King" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/110862/s/the-return-of-the-king" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Print</td>
            </tr>
            <tr>
                <td class="id">064</td>
                <td class="title">The Rookery</td>
                <td class="author">Deborah Hewitt</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/51321755-the-rookery" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/1242965/s/the-rookery" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">065</td>
                <td class="title">Ruin and Rising</td>
                <td class="author">Leigh Bardugo</td>
                <td class="series">Shadow and Bone</td>
                <td class="sernum">3</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/14061957-ruin-and-rising" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/106774/s/ruin-and-rising" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">066</td>
                <td class="title">Sandworms of Dune</td>
                <td class="author">Frank Herbert</td>
                <td class="series">Dune</td>
                <td class="sernum">8</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/42434.Sandworms_of_Dune" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/129667/s/sandworms-of-dune" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">067</td>
                <td class="title">Shadow and Bone</td>
                <td class="author">Leigh Bardugo</td>
                <td class="series">Shadow and Bone</td>
                <td class="sernum">1</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/37834723-shadow-and-bone" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/151434/s/shadow-and-bone" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">068</td>
                <td class="title">The Shining</td>
                <td class="author">Stephen King</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/11588.The_Shining" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/1875747/s/the-shining-the-shining-1" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">069</td>
                <td class="title">Siddhartha</td>
                <td class="author">Herman Hesse</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/52036.Siddhartha" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/21006/s/siddhartha" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">070</td>
                <td class="title">Siege and Storm</td>
                <td class="author">Leigh Bardugo</td>
                <td class="series">Shadow and Bone</td>
                <td class="sernum">2</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/14061955-siege-and-storm" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/304238/s/siege-and-storm" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">071</td>
                <td class="title">The Silmarillion</td>
                <td class="author">J.R.R. Tolkien</td>
                <td class="series">Middle Earth</td>
                <td class="sernum">0.5</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/7332.The_Silmarillion" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/15451/s/the-silmarillion" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Print</td>
            </tr>
            <tr>
                <td class="id">072</td>
                <td class="title">Song of Susannah</td>
                <td class="author">Stephen King</td>
                <td class="series">The Dark Tower</td>
                <td class="sernum">6</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/5093.Song_of_Susannah" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/109381/s/song-of-susannah-the-dark-tower-book-6" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">073</td>
                <td class="title">Sophie Quire</td>
                <td class="author">Jonathan Auxier</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/24795920-sophie-quire-and-the-last-storyguard" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/942226/s/sophie-quire-and-the-last-storyguard" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">074</td>
                <td class="title">A Storm of Swords</td>
                <td class="author">George R.R. Martin</td>
                <td class="series">ASOIAF</td>
                <td class="sernum">3</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/62291.A_Storm_of_Swords" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/6984/s/a-storm-of-swords" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">075</td>
                <td class="title">The Stranger</td>
                <td class="author">Albert Camus</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/49552.The_Stranger" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/4017/s/the-stranger" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">076</td>
                <td class="title">Sunrise on the Reaping</td>
                <td class="author">Suzanne Collins</td>
                <td class="series">The Hunger Games</td>
                <td class="sernum">0.5</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/214331246-sunrise-on-the-reaping" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/1740472/s/sunrise-on-the-reaping" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">077</td>
                <td class="title">The Tales of Beedle the Bard</td>
                <td class="author">J.K. Rowling</td>
                <td class="series">Harry Potter</td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/4020390-the-tales-of-beedle-the-bard" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/63468/s/the-tales-of-beedle-the-bard" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">078</td>
                <td class="title">Tao Te Ching</td>
                <td class="author">Stephen Mitchell</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/439655.Tao_Te_Ching" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/444698/s/tao-te-ching" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">079</td>
                <td class="title">Thus Spake Zarathustra</td>
                <td class="author">Friedrich Nietzsche</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/27832470-thus-spake-zarathustra" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/154539/s/thus-spake-zarathustra-thus-spoke-zarathustra" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">080</td>
                <td class="title">To Kill a Mockingbird</td>
                <td class="author">Harper Lee</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/56916837-to-kill-a-mockingbird" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/134243/s/to-kill-a-mockingbird" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">081</td>
                <td class="title">The Two Towers</td>
                <td class="author">J.R.R. Tolkien</td>
                <td class="series">Middle Earth</td>
                <td class="sernum">3</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/55608406-the-two-towers" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/215427/s/the-two-towers" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Print</td>
            </tr>
            <tr>
                <td class="id">082</td>
                <td class="title">The Wastelands</td>
                <td class="author">Stephen King</td>
                <td class="series">The Dark Tower</td>
                <td class="sernum">3</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/34084.The_Waste_Lands" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/24388/s/the-waste-lands" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">083</td>
                <td class="title">The Westing Game</td>
                <td class="author">Ellen Raskin</td>
                <td class="series"> </td>
                <td class="sernum"> </td>
                <td class="links"><a href="https://www.goodreads.com/book/show/902.The_Westing_Game" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/54638/s/the-westing-game" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">084</td>
                <td class="title">The Wind Through the Keyhole</td>
                <td class="author">Stephen King</td>
                <td class="series">The Dark Tower</td>
                <td class="sernum">4.5</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/12341557-the-wind-through-the-keyhole" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/36386/s/the-wind-through-the-keyhole" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">085</td>
                <td class="title">The Winds of Winter</td>
                <td class="author">George R.R. Martin</td>
                <td class="series">ASOIAF</td>
                <td class="sernum">6</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/12111823-the-winds-of-winter" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/192599/s/the-winds-of-winter" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook</td>
            </tr>
            <tr>
                <td class="id">086</td>
                <td class="title">Wizard and Glass</td>
                <td class="author">Stephen King</td>
                <td class="series">The Dark Tower</td>
                <td class="sernum">4</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/5096.Wizard_and_Glass" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/20023/s/the-dark-tower-iv" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
            <tr>
                <td class="id">087</td>
                <td class="title">Wolves of the Calla</td>
                <td class="author">Stephen King</td>
                <td class="series">The Dark Tower</td>
                <td class="sernum">5</td>
                <td class="links"><a href="https://www.goodreads.com/book/show/4978.Wolves_of_the_Calla" target="_blank">Goodreads</a><br><a href="https://bookwyrm.social/book/22971/s/wolves-of-the-calla" target="_blank">Bookwyrm</a></td>
                <td class="formats">eBook, Audiobook</td>
            </tr>
        </tbody>
    </table>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/list.js/2.3.1/list.min.js"></script>

<script>
    var options = {
        valueNames: ['id', 'title', 'author', 'series', 'sernum', 'links', 'formats']
    };

    var bookList = new List('book-list', options);
</script>

---

Cover image: [“Celestial Library : Arias Rune” by Maethavee.Kay'E on Artstation](https://www.artstation.com/artwork/AqKwKm)