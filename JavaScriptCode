<script>
    function zoomImage(container) {
        // Create the zoomed container
        const zoomedContainer = document.createElement('div');
        zoomedContainer.classList.add('zoomed');

        // Create the zoomed image
        const img = document.createElement('img');
        img.src = container.querySelector('img').src; // Get the source from the clicked image

        // Append the image to the zoomed container
        zoomedContainer.appendChild(img);

        // Append the zoomed container to the body
        document.body.appendChild(zoomedContainer);

        // Remove the zoomed container on click
        zoomedContainer.addEventListener('click', () => {
            document.body.removeChild(zoomedContainer);
        });
    }
</script>

