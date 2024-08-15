# Project-Landing-Page



html, body {
    height: 100%;
    margin: 0;
}

.container {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    padding: 20px;
    background-color: #1f2937;
    height: 100vh; /* Full viewport height */
    flex-wrap: wrap;
}

.header {
    display: flex;
    align-items: center;
    width: 100%; /* Full width to ensure header spans across the container */
    margin-bottom: 20px; /* Space between header and middle section */
}

.header-image {
    height: 80px;
    width: 80px;
}

.links {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-end; /* Align links to the right */
    width: 100%; /* Full width to align links on the right */
    margin-bottom: 20px; /* Space between links and middle section */
    position: absolute;
}

.links ul {
    display: flex;
    list-style: none;
    padding: 0; 
    margin: 0; 
}

.links li {
    margin: 0 15px; 
}

.links a {
    color: white; 
    text-decoration: none; 
}

.middle {
    display: flex;
    justify-content: flex-start;
    flex-direction: row-reverse;
    width: 100%; /* Full width to allow for right alignment */
    
}

.middle-image {
    height: 300px;
    width: 300px;
    margin-right: 20%;
}

.middle-text {
    margin-right: 40%;
    font-family: cursive;
    font-weight:800;
    font-size: 48px;
    width: 100%;

}

.middle-sub {
    font-family: 'Courier New', Courier, monospace;
    font-size: 18px;
    font-weight: 300;
    width: 100%;
    text-align: center;
    



}