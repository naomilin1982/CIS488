// Function to get URL parameters
function getUrlParameter(name) {
    name = name.replace(/[\[]/, '\\[').replace(/[\]]/, '\\]');
    var regex = new RegExp('[\\?&]' + name + '=([^&#]*)');
    var results = regex.exec(location.search);
    return results === null ? '' : decodeURIComponent(results[1].replace(/\+/g, ' '));
}

// Get the utm_content parameter
var utmContent = getUrlParameter('utm_content');

// Add class to body based on utm_content
if (utmContent === 'example1') {
    document.body.classList.add('utm-example1');
} else if (utmContent === 'example2') {
    document.body.classList.add('utm-example2');
} else {
    document.body.classList.add('utm-default');
}
