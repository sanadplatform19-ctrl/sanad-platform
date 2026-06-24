document.querySelector("form").addEventListener("submit", function(e) {
    e.preventDefault();
    alert("✅ تم استلام طلبك! سنتواصل معك خلال 24 ساعة.");
    this.reset();
});
