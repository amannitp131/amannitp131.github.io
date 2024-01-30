
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Complaint Registration - Homepage</title>
    <link rel="stylesheet" href="homepage-style.css">
  <stlyle>
      body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 15px;
    text-align: center;
}

nav {
    background-color: #333;
    color: #fff;
    padding: 15px;
    text-align: center;
}

nav a {
    text-decoration: none;
    color: #fff;
    padding: 10px 20px;
    margin: 0 10px;
    border-radius: 5px;
    transition: background-color 0.3s;
}

nav a:hover {
    background-color: #555;
}


section {
    max-width: 500px;
    margin: 20px auto;
    padding: 20px;
    background-color: rgb(132, 123, 123);
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

label {
    display: block;
    margin-bottom: 8px;
}

input,
textarea {
    width: 100%;
    padding: 8px;
    margin-bottom: 16px;
    box-sizing: border-box;
    border: 1px solid #ccc;
    border-radius: 4px;
}

button {
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #555;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

footer a {
    text-decoration: none;
    color: white;

}
main aside {
    min-width: 20%;
}
aside nav {
    min-width: 40%;
    height: 80vh;
    background-color: #333;
    color: #fff;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    display: flex;
    flex-direction: column;
    align-items: flex-start;
}

aside nav a {
    text-decoration: none;
    color: #fff;
    padding: 10px 0;
    margin-bottom: 10px;
    border-bottom: 1px solid #555;
    width: 100%;
    box-sizing: border-box;
    text-align: left;
}

aside nav a:last-child {
    border-bottom: none;
}

main {
    display: flex;
    align-items: center;
}

#para {
    font-size: 1.2rem;
}

.right div {
    text-align: center;


}

.right {
    /* margin: auto; */
    background-image: url("student\ counsil.png");
    background-repeat: no-repeat;
    background-size: cover;
}

/* Start here */

.header_container {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 2.5rem;
    line-height: 1.2rem;
}

.header_container h2 {
    margin-bottom: 1.5rem;
    font-size: 1.2rem;
}

.header_container p {
    width: 60%;
    font-size: 1.2rem;
    text-align: center;
}

a {
    text-decoration: none;
}




.main_container {
    /* border: 2px solid black; */
    width: 70%;
    display: grid;
    padding: 0.7rem;
    /* justify-content: center;
    align-items: center; */
    gap: 2rem;
    grid-template-columns: repeat(4, 1fr);
    margin: 0 15%;
}

@media (max-width:1100px) {
    .main_container {
        grid-template-columns: repeat(3, 1fr);

    }
}
@media (max-width:880px) {
    .main_container {
        grid-template-columns: repeat(2, 1fr);

    }
}
@media (max-width:650px) {
    .main_container {
        grid-template-columns: repeat(1, 1fr);

    }
}

.card_container {
    /* border: 2px solid orange; */
    display: flex;
    flex-direction: column;
    border-radius: 7px;
    overflow: hidden;
    gap: 1.2rem;
    box-shadow: rgba(50, 50, 93, 0.25) 0px 30px 60px -12px inset, rgba(0, 0, 0, 0.3) 0px 18px 36px -18px inset;
}

.card_container:hover .card_image {
    transform: scale(1.2);
    transition: all 2s ease-out 1s;

}

.image_container {
    position: relative;
    overflow: hidden;
    height: 9rem;

}

.card_image {
    object-fit: cover;
    object-position: center;
    position: absolute;
    height: 100%;
    width: 100%;
    border-top-right-radius: 4px;
    border-top-left-radius: 4px;
}

.card_title_container {
    /* border: 2px solid green; */
    display: flex;
    flex-direction: column;
    gap: 1.2rem;
    padding: 0 1.2rem;
}

.card_title_anchor {
    margin: auto;
}

.card_title_anchor:hover .card_title {
    color: red;
}

.card_footer {
    /* border: 2px solid red; */
    display: flex;
    justify-content: space-between;
}

.card_author {
    /* border: 1px solid pink; */
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 1rem;

}

.author_avatar {
    height: 2.5rem;
    width: 2.5rem;
    overflow: hidden;
    border: 1px solid rgb(55, 49, 49);
    border-radius: 90%;
    background-color: rgb(187, 174, 174);
}

.tag_container {
    display: flex;
    align-items: center;

}

.tag_container span {
    border: 1px solid black;
}
  </stlyle>
</head>

<body>
    <header>
        <nav>
            <a href="homepage.html">Home</a>
            <a href="#about">About</a>
            <a href="#">Services</a>
            <a href="#Contact">Contact</a>
        </nav>
    </header>

    <main>
        <aside>
            <nav>
                <a href="#">Complaints</a>
                <a href="graph.html">Status</a>
                <a href="#gamma">Prof.In-Charge</a>
                <a href="#">Notification</a>
            </nav>
        </aside>
        <div class="right">

            <div>
                <h2 id="about">About Us</h2>
                <p id="para">Welcome to the Student Council Complaint about Mess website! We understand the importance
                    of a clean
                    and organized dining environment, and we are here to address your concerns. Our platform serves as a
                    direct channel for students to voice their feedback, report issues, and contribute to the
                    improvement of the mess facilities on campus.</p>
            </div>
            <section class="complaintForm">
                <form action="mailto:kingshivamsaxena862006@gmail.com" method="post" id="complaintForm"
                    enctype="text/plain">
                    <label for="name">Area of Compliant:</label>
                    <select name="name" id="name" style="display: inline;">
                        <Option>Academics</Option>
                        <option value="">Hostel Facilities</option>
                        <option value="">Mess Food</option>
                        <option value="">Hostel Room</option>
                        <option value="">Transportation</option>
                    </select>

                    <label for="complaint" aria-placeholder="Write Your Complaint">Your Complaint:</label>
                    <textarea id="complaint" name="complaint" rows="8" required></textarea>

                    <button type="submit">Submit Complaint</button>
                </form>
            </section>
        </div>
    </main>
    <div class="main_container" id="gamma">
        <!-- card1 start here -->
        <div class="card_container">
            <a href="#" class="image_container">
                <img src="https://source.unsplash.com/random/600×400?technology" alt="card1_image" class="card_image"
                    loading="lazy">
            </a>
            <div class="card_title_container">
                <a href="#" class="card_title_anchor" target="_blank">
                    <h3 class="card_title">Maintainance</h3>
                </a>
                <p class="card_desc">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illum ipsam rerum excepturi adipisci.
                </p>
            </div>
            <div class="card_footer">
                <div class="card_author">
                    <div class="author_avatar">
                        <img src="https://api.dicebear.com/7.x/notionists/svg?seed=John?size=64" alt="Avatar"
                            loading="lazy">
                    </div>
                    <div class="author_info">
                        <span>
                            Anshu Jha
                        </span>
                        <span>
                            08/11/2024
                        </span>
                    </div>
                </div>

                <div class="tag_container">
                    <span>Technology</span>
                </div>
            </div>
        </div>
        <!-- card1 end here -->
        <div class="card_container">
            <a href="#" class="image_container">
                <img src="https://source.unsplash.com/random/600×400?healthy" alt="card1_image" class="card_image"
                    loading="lazy">
            </a>
            <div class="card_title_container">
                <a href="#" class="card_title_anchor" target="_blank">
                    <h3 class="card_title">Mess Food</h3>
                </a>
                <p class="card_desc">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illum ipsam rerum excepturi adipisci.
                </p>
            </div>
            <div class="card_footer">
                <div class="card_author">
                    <div class="author_avatar">
                        <img src="https://api.dicebear.com/7.x/notionists/svg?seed=John?size=64" alt="Avatar"
                            loading="lazy">
                    </div>
                    <div class="author_info">
                        <span>
                            S. Saxena
                        </span>
                        <span>
                            29/01/2024
                        </span>
                    </div>
                </div>

                <div class="tag_container">
                    <span>Health</span>
                </div>
            </div>
        </div>
        <div class="card_container">
            <a href="#" class="image_container">
                <img src="https://source.unsplash.com/random/600×400?student" alt="card1_image" class="card_image"
                    loading="lazy">
            </a>
            <div class="card_title_container">
                <a href="#" class="card_title_anchor" target="_blank">
                    <h3 class="card_title">Academics</h3>
                </a>
                <p class="card_desc">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illum ipsam rerum excepturi adipisci.
                </p>
            </div>
            <div class="card_footer">
                <div class="card_author">
                    <div class="author_avatar">
                        <img src="https://api.dicebear.com/7.x/notionists/svg?seed=John?size=64" alt="Avatar"
                            loading="lazy">
                    </div>
                    <div class="author_info">
                        <span>
                            Aakash
                        </span>
                        <span>
                            16/11/2020
                        </span>
                    </div>
                </div>

                <div class="tag_container">
                    <span>Academic</span>
                </div>
            </div>
        </div>
        <div class="card_container">
            <a href="#" class="image_container">
                <img src="https://source.unsplash.com/random/600×400?transport" alt="card1_image" class="card_image"
                    loading="lazy">
            </a>
            <div class="card_title_container">
                <a href="#" class="card_title_anchor" target="_blank">
                    <h3 class="card_title">Transport</h3>
                </a>
                <p class="card_desc">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illum ipsam rerum excepturi adipisci.
                </p>
            </div>
            <div class="card_footer">
                <div class="card_author">
                    <div class="author_avatar">
                        <img src="https://api.dicebear.com/7.x/notionists/svg?seed=John?size=64" alt="Avatar"
                            loading="lazy">
                    </div>
                    <div class="author_info">
                        <span>
                            Aman
                        </span>
                        <span>
                            16/11/2020
                        </span>
                    </div>
                </div>

                <div class="tag_container">
                    <span>Loco</span>
                </div>
            </div>
        </div>
    </div>
    <footer class="bottom-container" id="Contact">
        <a style="padding: 20px;" class="footer-link"
            href="https://www.linkedin.com/in/shivam-saxena-aa8754289?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">LinkedIn</a>
        <a style="padding: 20px;" class="footer-link"
            href="https://x.com/Shivam562006?t=9i0jfcSJV7CURFDcSW5Y_A&s=09">Twitter</a>
        <a style="padding: 20px;" class="footer-link"
            href="https://www.instagram.com/shivamsaxena744846?igsh=YzVkODRmOTdmMw==">instagram</a>
        <p class="copyright">© 2023 Student Council Web-Diver @nitp</p>
    </footer>



    <script src="homepage.js"></script>
</body>

</html>
