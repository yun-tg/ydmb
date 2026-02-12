document.querySelectorAll('.sidebar > .menu > li > a').forEach(function(item) {
    item.addEventListener('click', function(event) {
        var subMenu = item.nextElementSibling;
        if (subMenu && subMenu.tagName.toLowerCase() === 'ul') {
            event.preventDefault();
            subMenu.classList.toggle('active');
        }
    });
});
