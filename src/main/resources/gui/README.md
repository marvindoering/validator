# KoSIT Validator - Daemon

[API usage](docs/api)

[configurations](docs/configurations)

# Server information
View [validator configuration](/server/config) or <a href="/server/health" target="_blank">health information</a> 

# Try it
<div>
    <form>
        <div>
            <label for="files">Choose a files</label>
            <input type="file" id="files" name="myFiles" accept="text/xml" multiple>
            <input type="button" id="submit" value="Validate" onclick="return validate();">
        </div></br>
        <div id="results">
            <div id="result_0"></div>
            <input type="button" id="dwn-btn_0" value="Download Report" onclick="return download('dwn-btn_0');" hidden>
        </div>
    </form>
</div>


