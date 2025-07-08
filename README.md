# Event_Invitation
## Aim:
To design a visually appealing event invitation using HTML elements and basic CSS styling for structure and layout.

## Tasks:
1. Set Up the HTML Document
Use <!DOCTYPE html>, <html>, <head>, <title>, and <body>.

Set the title as "Event Invitation".

➤ CSS Styling:

Set background color for the body (e.g., light beige or pastel).

Apply font-family (e.g., sans-serif) for consistent typography.

2. Create the Invitation Container
Use a <div> with a class like invite-card to wrap the entire content.

➤ CSS Styling:

Set width, padding, border-radius, and a soft box-shadow.

Center the card using margin: auto and margin-top.

3. Add Event Title and Subtitle
Use <h1> for the event name (e.g., "Annual Alumni Meet").

Use <h3> for a subtitle (e.g., "Reconnect & Celebrate Together").

➤ CSS Styling:

Center the headings.

Use custom colors and spacing for visual emphasis.

4. Insert Date, Time, and Venue
Use <p> tags for:

Date (e.g., August 25, 2025)

Time (e.g., 6:00 PM onwards)

Venue (e.g., College Auditorium)

➤ CSS Styling:

Use bold text for labels (e.g., Date:).

Align text centrally or left with padding/margin adjustments.

5. Add an Image or Banner (Optional)
Use <img> for a decorative image or event logo.

➤ CSS Styling:

Use max-width: 100%, border-radius, and center alignment.

6. Add RSVP or Contact Info
Use a separate <div> or <footer> section.

Include contact name, phone number, or RSVP link.
## Html code:
```
<!DOCTYPE html>
<html>
    <head>
        <title>Event Invitation</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <div class="Invite card">
            <h1>Alumni meet</h1>
            <h3>Reconnect & Celebrate together</h3>

            <p>
             We warmly welcome all our esteemed alumni to this special gathering. It’s a pleasure to have you back on campus, where countless memories were made and lifelong bonds began. Let’s cherish the past, celebrate the present, and look forward to a future filled with continued connection and success.  
            </p>
            <img src="alumi.jpeg" alt="Event banner">
            <p>Date:May 22, 2025</p>
            <p>Time:5:00 pm onwards</p>
            <p>Venue:College Auditorium</p>
            <footer>
                <p>Phone:+91 6379266788/p>
                <p>Email:yogabharathi76@gmail.com</p>
            </footer>
        </div>
    </body>
</html>
```
## CCS code:
```
body {
    background-color:bisque;
    font-family: Arial, sans-serif;
    display: flex;          
    justify-content: center;   
    align-items: center;       
    height: 100vh;            
}

invite-card {
    width: 80%;
    max-width: 700px;          
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
    background-color: white;   
}

h1, h3 {
    text-align: center;
    color:rebeccapurple;
    word-spacing: 5px;
}

p {
    text-align: center;
    line-height: 1.5;
}

img {
    border-radius: 50%;
    display: block;
    margin: 20px auto;
    max-width: 100%;
}

footer {
    background-color:lightblue;
    padding: 10px;
    font-size: smaller;
    text-align: center;
    border-radius: 0 0 10px 10px;
}

a {
    text-decoration: none;
}

label {
    font-weight: bold;
}
```
# Output:
![image](https://github.com/user-attachments/assets/a2cf585e-bcde-4820-99e5-64cbd98ff782)
# Result:
The event invitation was successfully created using HTML for structure and CSS for styling. It features a clean, visually appealing design that effectively communicates the event details.
