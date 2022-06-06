# HelloHTML
 Reviewing the basics to ramp up everything!
<!DOCTYPE html>
<html lang="en-US">

<head>
    <title>JuggernOtt81</title>
    <meta charset="utf-8">
    <meta name="author" content="ME">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link>
    </link>
    <script></script>

</head>

<style>
    ol {
        font-weight: bolder;
    }

    ol li span {
        font-weight: normal;
    }
</style>

<body onload="">
    <p>My first (not really) HTML page</p>
    <p>does changing the name of this file from Index.html to index.html allow it to be a github.pages page?</p>

    <div style="background-color:rgb(0, 139, 69);">
        <p>Hello World!</p>
        <span>Grouping in div</span>
    </div>

    <header style="background-color:rgb(7, 39, 23); color:aliceblue">
        <p>Hello World!</p>
        <span>Grouping in header</span>
    </header>

    <div style="background-color:darkred; color: azure;">
        <hr style="height:10px; color:blue ">
        <p>this section has been marked by the 'hr' tag</p>
        <hr style="height:10px; color:blue ">
    </div>

    <div style="background-color:tan">
        <br>
        <p>this section has been marked by the 'br' tag</p>
        <br>
    </div>

    <div style="color:black; font-weight: bold;">
        <p>unordered list (ul)</p>
        <ul style="background-color: red;">
            <li style="list-style-type:disc;">item 1</li>
            <ul style="background-color: orange;">
                <li style="list-style-type:circle;">sub-item 1</li>
                <ul style="background-color: yellow;">
                    <li style="list-style-type:square;">sub-sub-item 1</li>
                    <ul style="background-color: green;">
                        <li style="list-style-type: armenian;">sub-sub-sub-item 1</li>
                        <ul style="background-color: blue;">
                            <li style="list-style-type:georgian">sub-sub-sub-sub-item 1</li>
                            <ul style="background-color: indigo;">
                                <li style="list-style-type:upper-latin">sub-sub-sub-sub-sub-item 1</li>
                                <ul style="background-color: violet;">
                                    <li style="list-style-type:upper-roman">sub-sub-sub-sub-sub-sub-item 1</li>
                                    <ul style="background-color: brown;">
                                        <li style="list-style-type:lower-alpha">sub-sub-sub-sub-sub-sub-sub-item 1</li>
                                        <ul style="background-color: teal;">
                                            <li style="list-style-type:lower-greek">sub-sub-sub-sub-sub-sub-sub-sub-item
                                                1</li>
                                            <ul style="background-color: tomato;">
                                                <li style="list-style-type:none">
                                                    sub-sub-sub-sub-sub-sub-sub-sub-sub-item 1</li>
                                                <li style="list-style-type:none">
                                                    sub-sub-sub-sub-sub-sub-sub-sub-sub-item 2</li>
                                                <li style="list-style-type:none">
                                                    sub-sub-sub-sub-sub-sub-sub-sub-sub-item 3</li>
                                            </ul>
                                            <li style="list-style-type:lower-greek">sub-sub-sub-sub-sub-sub-sub-sub-item
                                                2</li>
                                            <li style="list-style-type:lower-greek">sub-sub-sub-sub-sub-sub-sub-sub-item
                                                3</li>
                                        </ul>
                                        <li style="list-style-type:lower-alpha">sub-sub-sub-sub-sub-sub-sub-item 2</li>
                                        <li style="list-style-type:lower-alpha">sub-sub-sub-sub-sub-sub-sub-item 3</li>
                                    </ul>
                                    <li style="list-style-type:upper-roman">sub-sub-sub-sub-sub-sub-item 2</li>
                                    <li style="list-style-type:upper-roman">sub-sub-sub-sub-sub-sub-item 3</li>
                                </ul>
                                <li style="list-style-type:upper-latin">sub-sub-sub-sub-sub-item 2</li>
                                <li style="list-style-type:upper-latin">sub-sub-sub-sub-sub-item 3</li>
                            </ul>
                            <li style="list-style-type:georgian">sub-sub-sub-sub-item 2</li>
                            <li style="list-style-type:georgian">sub-sub-sub-sub-item 3</li>
                        </ul>
                        <li style="list-style-type: armenian;">sub-sub-sub-item 2</li>
                        <li style="list-style-type: armenian;">sub-sub-sub-item 3</li>
                    </ul>
                    <li style="list-style-type:square;">sub-sub-item 2</li>
                    <li style="list-style-type:square;">sub-sub-item 3</li>
                </ul>
                <li style="list-style-type:circle;">sub-item 2</li>
                <li style="list-style-type:circle;">sub-item 3</li>
            </ul>
            <li style="list-style-type:disc;">item 2</li>
            <li style="list-style-type:disc;">item 3</li>
        </ul>
    </div>

    <div>
        <p>ordered list (ol)</p>
        <hr>
        <ol>
            <li><span>Item X</span></li>
            <li><span>Item Y</span></li>
        </ol>

        <hr>
        <ol>
            <li><span>Item X</span></li>
            <ol>
                <li><span>Item X</span></li>
                <li><span>Item Y</span></li>
            </ol>
            <li><span>Item Y</span></li>
        </ol>

        <hr>
        <ol>
            <li><span>Item X</span></li>
            <ol>
                <li><span>Item X</span></li>
                <ol>
                    <li><span>Item X</span></li>
                    <li><span>Item Y</span></li>
                </ol>
                <li><span>Item Y</span></li>
            </ol>
            <li><span>Item Y</span></li>
        </ol>

        <hr>
        <ol>
            <li><span>A</span></li>
            <ol reversed start="26">
                <li><span>Apple</span></li>
                <li><span>Banana</span></li>
                <li><span>Cherry</span></li>
                <li><span>Date</span></li>
                <li><span>Eggplant</span></li>
            </ol>
            <li><span>B</span></li>
            <li><span>C</span></li>
            <li><span>D</span></li>
            <li><span>E</span></li>
        </ol>

        <hr>
        <ol type="A">
            <li><span>Item X</span></li>
            <ol type="a">
                <li><span>Item X</span></li>
                <ol type="I">
                    <li><span>Item X</span></li>
                    <ol type="i">
                        <li><span>Item X</span></li>
                        <ol type="1">
                            <li><span>Item X</span></li>
                            <ol>
                                <li><span>Item X</span></li>
                                <li><span>Item Y</span></li>
                            </ol>
                            <li><span>Item Y</span></li>
                        </ol>
                        <li><span>Item Y</span></li>
                    </ol>
                    <li><span>Item Y</span></li>
                </ol>
                <li><span>Item Y</span></li>
            </ol>
            <li><span>Item Y</span></li>
        </ol>

        <hr>
        <ol style="list-style-type:upper-alpha; line-height:2rem;">
            <li><span>Item a</span></li>
            <ol style="list-style-type:lower-roman;">
                <li><span>Item a</span></li>
                <ol style="list-style-type:upper-roman">
                    <li><span>Item a</span></li>
                    <li><span>Item b</span></li>
                    <li><span>Item c</span></li>
                    <li><span>Item Y</span></li>
                    <li><span>Item Y</span></li>
                </ol>
                <li><span>Item b</span></li>
                <li><span>Item c</span></li>
            </ol>
            <li><span>Item b</span></li>
            <li><span>Item c</span></li>
        </ol>
    </div>
    <hr>
    <div>
        <p>BUTTONS!</p>
        <button type="button">Button</button>
        <button type="reset">Reset</button>
        <button type="submit">Submit</button>
        <button type="menu">Menu</button>

        <button type="submit" name="dataPassingButton" value="dataToBePassed">
            Submit Passed Value(s)
        </button>

    </div>

    <hr>

    <div>
        <p>
        <p>anchor element</p>
        <br>
        <a href="https://www.juggernott81.com" target="_blank">Portfolio Website</a>
        <br>
        <a href="https://www.juggernott81.com#preFooter" target="_blank">Portfolio Website - bottom</a>
        <br>
        <p>Be sure to check the <a href="https://www.juggernott81.com#preProjects" target="_blank">Projects</a> and
            see
            the
            fun coding <a href="https://www.juggernott81.com#preChallenges" target="_blank">Challenges</a>!</p>
        <br>
        <p>need information? call <a href="tel:12125551212">212-555-1212</a></p>
        <p>send an email <a href="mailto:BillGates@Microsoft.com">BillGates@Microsoft.com</a></p>

        <a id="imgImage" href="https://www.CoderFoundry.com" target="_blank">
            <img style="max-height: 200px;" src="https://isa.coderfoundry.com/images/cf_badge_logo.png"
                alt="I got some of my training here.">
        </a>
    </div>

    <hr>

    <div>
        paragraphs:
        <p>
            This is the first paragraph of text, aligned left by default.
        </p>
        <p class="text-center">
            This is the second paragraph of text, centered per CSS class.
        </p>
        <p class="text-end text-danger">
            This is the third paragraph, right aligned with 2 CSS classes.
        </p>
    </div>
    <hr>
    <div>
        headings:

        <h1>Heading Level 1</h1>
        <h2>Heading Level 2</h2>
        <h3>Heading Level 3</h3>
        <h4>Heading Level 4</h4>
        <h5>Heading Level 5</h5>
        <h6>Heading Level 6</h6>

    </div>
    <hr>
    <div>
        forms:
        <form>
            <div class="form-group">
                <label for="Email">Email Address</label>
                <input type="email" id="Email">
            </div>
            <div class="form-group">
                <label for="Password">Password</label>
                <input type="password" id="Password">
            </div>
            <div class="form-group">
                <button type="reset" class="btn btn-dark">Reset</button>
                <button type="submit" class="btn btn-dark">Submit</button>
            </div>
        </form>
    </div>
    <hr>
    <div>
        more forms:

        <form>
            <input type="button" value="button">
            <input type="button" value="disabled">
            <hr>
            <input type="checkbox">
            <input type="checkbox" checked>
            <input type="checkbox" disabled>
            <input type="checkbox" checked disabled>
            <hr>
            <input type="color" value="#ff993b"> CF Orange
            <br>
            <input type="color" value="212121"> CF Black
            <hr>
            <input type="date" value="2022-05-31">
            <hr>
            <input type="datetime-local" value="2022-05-31T16:24">
            <hr>
            <input type="email" placeholder="name@email.domain">
            <hr>
            <input type="file">
            <hr>
            <!--This makes an image a button (for work not just link)-->
            <input type="image" src="IMG/cf5 percent.png" height=100>
            <hr>
            <input type="month" min="1900-01" max="2099-12">
            <hr>
            <input type="number"><label>any number</label>
            <hr>
            <input type="password"><label>Password</label>
            <hr>
            <input type="radio" value="1" checked><label>Option 1</label>
            <input type="radio" value="2"><label>Option 2</label>
            <input type="radio" value="3"><label>Option 3</label>
            <hr>
            <input type="range" min="0" max="100" value="50" step="20"><label>Size</label>
            <input type="range" min="0" max="100" value="50" step="1"><label>Quality</label>
            <input type="range" min="0" max="100" value="50" step="5"><label>Speed</label>
            <input type="range" min="0" max="100" value="50" step="10"><label>Strength</label>
            <hr>
            <input type="reset">
            <hr>
            <input type="search"><label>Search</label>
            <hr>
            <input type="tel" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" required><label>Phone Number</label>
            <hr>
            <input type="time" min="00:00" max="24:00" value="23:59">
            <hr>
            <input type="url" placeholder="https://www.juggernott81.com" pattern="https://.*" size="50">
            <hr>
            <input type="week" min="1999-W52" max="2999-W52">
            <hr>
            <textarea placeholder="long form text entry"></textarea>
            <hr>
            <select>
                <option value="0">choose an option</option>
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5">5</option>
                <option value="6">6</option>
                <option value="7">7</option>
            </select>
            <input type="submit">
        </form>
    </div>
    <hr>
    <div>
        tables:
        <table>
            <tr>
                <th>Name</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>
                    ME
                </td>
                <td>
                    ME@mailinator.com
                </td>
            </tr>
        </table>
        <hr>
        <table>
            <thead>
                <th>Company A</th>
                <tr>
                    <th>Name</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>ME</td>
                    <td>ME@mailinator.com</td>
                </tr>
            </tbody>
            <tfoot>
                <tr>
                    <th>Name</th>
                    <th>Email</th>
                </tr>
            </tfoot>
        </table>
        <hr>
        <table>
            <caption>The data presented below is private and will not be shared with other entities</caption>
            <thead>
                <tr>
                    <th colspan="2" style="text-align: center;">EMPLOYEE CONTACT INFORMATION</th>
                </tr>
                <tr>
                    <th>Name</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>ME</td>
                    <td>ME@mailinator.com</td>
                </tr>
            </tbody>
            <tfoot>
                <th>a</th>
                <th>b</th>
            </tfoot>
        </table>
        <hr>
        <table>
            <caption>The data displayed if for demo purposes only</caption>
            <colgroup>
                <col>
                <col span="2" style="background-color:lightskyblue">
                <col span="2" style="background-color:lightcoral">
            </colgroup>
            <thead>
                <tr>
                    <th colspan="5">TECHNOLOGY INFORMATION</th>
                </tr>
                <tr>
                    <th>-</th>
                    <th>HTML</th>
                    <th>JS</th>
                    <th>C#.NET</th>
                    <th>SQL</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <th scope="row">Runs in Browser</th>
                    <td>YES</td>
                    <td>YES</td>
                    <td>No *</td>
                    <td>No</td>
                </tr>
                <tr>
                    <th scope="row">Compiled</th>
                    <td>No</td>
                    <td>No</td>
                    <td>YES</td>
                    <td>No</td>
                </tr>
            </tbody>
            <tfoot>
                <tr>
                    <th>-</th>
                    <th>HTML</th>
                    <th>JS</th>
                    <th>C#.NET</th>
                    <th>SQL</th>
                </tr>
            </tfoot>
        </table>
    </div>
<div>
    <nav>

    </nav>
</div>
<div>
    <header>

    </header>
    Published on <time></time>
</div>
<div>
    <main>

    </main>
</div>
<div>
    <section>

    </section>
</div>
<div>
    <article>

    </article>
    <summary>
        
    </summary>
    <details>

    </details>
    with
    <mark>

    </mark>
    content
</div>
<div>
    <aside>
        <figure>

        </figure>
        <figcaption>

        </figcaption>
    </aside>
</div>
<div>
    <footer>
        
    </footer>
</div>


</body>

</html>