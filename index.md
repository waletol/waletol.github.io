---
layout: default
---

[Solo](http://chibicode.github.io/solo) is a Jekyll theme that supports **single-page websites** only, but supports them well. Yes, it's responsive.

<iframe src="https://ghbtns.com/github-btn.html?user=chibicode&amp;repo=solo&amp;type=watch&amp;count=true&amp;size=large"
  allowtransparency="true" frameborder="0" scrolling="0" width="170" height="30"></iframe><br/>

Looking for a more standard Jekyll theme? Try out [Shiori](http://github.com/ellekasai/shiori) theme, which has Bootstrap integration.

## Survey

<ng-app>
var surveyJSON = {pages:[{name:"page1",questions:[{type:"matrix",columns:["Column 1","Column 2","Column 3"],name:"question1",rows:["Row 1","Row 2"]}]}]}

function sendDataToServer(survey) {
    //send Ajax request to your web server.
    alert("The results are:" + JSON.stringify(s.data));
}

@Component({
  selector: 'ng-app',
        template: 
        <div id='surveyElement'></div>",
})
export class AppComponent {
    ngOnInit() {
        var survey = new Survey.Model(surveyJSON);
        survey.onComplete.add(sendDataToServer);
       Survey.SurveyWindowNG.render("surveyElement", { model: survey });
    }
} 
</ng-app>
