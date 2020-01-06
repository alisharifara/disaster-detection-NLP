# disaster-detection-NLP

Following are the steps to create the text classification model:

01. Importing the required libraries
02. Importing the dataset
03. Text preprocessing (Text may contain numbers, special characters, and unwanted spaces. Hence, we should remove these special characters and numbers from text)
04. Converting text to numbers
05. Spliting data into training and test sets
06. Training text classification model and predicting Sentiment
07. Evaluating the model
08. Saving the model
09. Load the model




## Just as a reference for regex (Since I have used it in the text processing)
<ul>
    <li><b style="color:red">. </b>: Wildcard, matches a single character</li>
    <li><b style="color:red">^ </b>: Indicates start of a string</li>
    <li><b style="color:red"><span>$</span> </b>: Indicates end of a string</li>
    <li><b style="color:red">[ ]</b>: Matches one of the set of characters within [ ]</li>
        <ul>
            <li>[a-z]: Matches one of the characters of a,b,c,...,z</li>
            <li>[^abc]: Matches a character that is not a, b, or c</li>
        </ul>
    <li><b style="color:red">a|b</b>: Matches either a or b, where a and b are string</li>
    <li><b style="color:red">\</b> : Escapes characters for special characters (\t,\n,\b) </li>
    <li><b style="color:red">\b</b> : Matches word boundary </li>
    <li><b style="color:red">\d</b> : Matches any digit, equivalent to [0-9]  </li>
    <li><b style="color:red">\D</b> : Matches any non-digit, equivalent to [^0-9]  </li>
    <li><b style="color:red">\s</b> : Matches any whitespace character, equivalent to [ \t\n\r\f\v]  </li>
    <li><b style="color:red">\S</b> : Matches any non-whitespace character, equivalent to [^ \t\n\r\f\v]  </li>
    <li><b style="color:red">\w</b> : Matches any alphanumeric character, equivalent to [a-zA-Z0-9_]  </li>
    <li><b style="color:red">\w</b> : Matches any non-alphanumeric character, equivalent to [^a-zA-Z0-9_]  </li>
    <li><b style="color:red">*</b> : Matches zero or more occurrences</li>
    <li><b style="color:red">+</b> : Matches one or more occurrences</li>
    <li><b style="color:red">?</b> : Matches zero or one occurrences</li>
    <li><b style="color:red">{n}</b> : Matches exactly n occurrences</li>
    <li><b style="color:red">{n,}</b> : Matches at least n occurrences</li>
    <li><b style="color:red">{,n}</b> : Matches at most n occurrences</li>
    <li><b style="color:red">{m,n}</b> : Matches at least m occurrences and at most n occurrences</li>
</ul>
