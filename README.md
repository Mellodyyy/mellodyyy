<!DOCTYPE html>
<html>
<head>
    <title>act#2</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            padding: 10px;
        }
        .form-container {
            background-color: #ffffff;
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0 0 8px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            margin: 0 auto;
        }
        .form-title {
            text-align: center;
            margin-bottom: 15px;
            color: #333333;
        }
        .form-group {
            margin-bottom: 10px;
        }
        .form-label {
            font-weight: bold;
        }
        .form-input {
            width: 100%;
            padding: 8px;
            border-radius: 5px;
            border: 1px solid #cccccc;
        }
        .form-textarea {
            width: 100%;
            padding: 8px;
            border-radius: 5px;
            border: 1px solid #cccccc;
            resize: none;
        }
        .form-button {
            width: 100%;
            padding: 10px;
            border: none;
            border-radius: 5px;
            background-color: #FF69B4;
            color: #ffffff;
            cursor: pointer;
        }
        .form-button:hover {
            background-color: #FF1493;
        }
    </style>
</head>
<body>
    <div class="form-container">
        <h2 class="form-title">Suitors Application Form</h2>
        <form>
            <div class="form-group">
                <label for="name" class="form-label">Your Name:</label>
                <input type="text" id="name" name="name" class="form-input" required>
            </div>
            <div class="form-group">
                <label class="form-label">Your Gender:</label><br>
                <input type="radio" id="male" name="gender" value="male" required>
                <label for="male">Male</label>
                <input type="radio" id="female" name="gender" value="female">
                <label for="female">Female</label>
                <input type="radio" id="other" name="gender" value="other">
                <label for="other">Other</label>
            </div>
            <div class="form-group">
                <label for="age" class="form-label">Your Age:</label>
                <input type="number" id="age" name="age" class="form-input" required>
            </div>
            <div class="form-group">
                <label for="hobbies" class="form-label">Your Hobbies:</label>
                <input type="text" id="hobbies" name="hobbies" class="form-input" required>
            </div>
            <div class="form-group">
                <label for="favorite-pet" class="form-label">Your Favorite Pet:</label>
                <input type="text" id="favorite-pet" name="favorite-pet" class="form-input" required>
            </div>
            <div class="form-group">
                <label for="love-language" class="form-label">Your Love Language:</label><br>
                <input type="checkbox" id="physical-touch" name="love-language" value="physical-touch">
                <label for="physical-touch">Physical Touch</label>
                <input type="checkbox" id="words-of-affirmation" name="love-language" value="words-of-affirmation">
                <label for="words-of-affirmation">Words of Affirmation</label>
                <input type="checkbox" id="acts-of-service" name="love-language" value="acts-of-service">
                <label for="acts-of-service">Acts of Service</label>
                <input type="checkbox" id="quality-time" name="love-language" value="quality-time">
                <label for="quality-time">Quality Time</label>
                <input type="checkbox" id="gifts" name="love-language" value="gifts">
                <label for="gifts">Gifts</label>
            </div>
            <div class="form-group">
                <label for="message" class="form-label">Why do you want to be my suitor? HAHAHA</label>
                <textarea id="message" name="message" class="form-textarea" rows="3" required></textarea>
            </div>
            <button type="submit" class="form-button">Apply</button>
        </form>
    </div>
</body>
</html>
