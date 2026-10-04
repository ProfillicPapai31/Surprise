function nextPage(pageNumber) {

    const pages = document.querySelectorAll(".page");

    pages.forEach(function(page) {
        page.classList.remove("active");
    });

    const nextPage = document.getElementById("page" + pageNumber);

    if (nextPage) {
        nextPage.classList.add("active");
    }

    window.scrollTo({
        top: 0,
        behavior: "smooth"
    });
}


function wrongAnswer() {

    const answer = document.getElementById("answer");

    answer.textContent =
        "Excuse me??? 😭 That's illegal. Try again. 😤💗";
}
