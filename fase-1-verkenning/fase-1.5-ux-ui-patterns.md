# Fase 1.5 - UX/UI patterns

## Intro

### Onderzoeksvragen

Ik heb de volgende onderzoeksvragen gesteld binnen deze fase:

1. Hoe omgaan met foutmeldingen?

### Bronnen:

Giner, P., & Perea, P. \(2017\). UX Design for Mobile. Birmingham, Verenigd Koninkrijk: Packt Publishing.

Eckerson, W. \(2010\). UX Design for Performance Dashboards: Measuring, Monitoring, and Managing Your Business \(2e ed.\). Hoboken, NJ: John Wiley & Sons.

Cotgreave, A. \(2017, October 19\). 7 tips and tricks from the dashboard experts. Retrieved May 15, 2019, from https://www.tableau.com/about/blog/2017/10/7-tips-and-tricks-dashboard-experts-76821

## Mobile design patterns 

### Handling errors

**Humanize errors**

> **Users do not speak the language of servers, nor do they understand codes**, especially if we are talking about a mobile phone application. We should phrase the errors in the same way we would speak to another person. Avoid technical terms that could confuse the user and make the problem seem more important and complex to solve. \(Giner & Perea, 2017\)

**Use proportional language**

> **Not all errors are equally serious, and this should be reflected in the explanation of the error.** The seriousness with which we express an error situation affects the users perception of the error. We must use language that is soft and reassuring in those errors that do not convey a serious application failure. \(Giner & Perea, 2017\)

**Avoid interruptions when possible**

> Use interface elements to display the errors that match the severity of the problem. When we have to inform the user of an error that prevents the operation of the application, the error can interrupt the user and request an action in order to continue. For example, an application might not work due to a malfunction of the servers that support the application. However, **errors that do not affect the overall operation of the application** should be displayed locally and allow the user to continue with the rest of the application. Some applications allow the user to continue despite having a malfunction in some parts of the application. For example, an application might report poor internet access, but allow the user to continue browsing the local content or content that has already been loaded. \(Giner & Perea, 2017\)

**Provide a solution if possible**

> Users will appreciate that the message, in addition to explaining what is wrong, tells them **how the error can be solved**. We can include tappable actions in the error itself, so that the user is guided to solve the problem from the error message. Guiding users in resolving an error will help make the experience more satisfying, reducing any feelings that an application is complex or requires prior learning. \(Giner & Perea, 2017\)

**Allow a user to explore or cancel**

> Those errors that do not need to be solved straight away, should allow the user to explore and get further information, or undo the action to resolve the problem later. We can inform the user that a section of our application needs action by the user in order to function properly. Through a visible action the user can **get more information about the problem to solve, but decide to fix it later**. Keep the user navigation history when possible, so the users can recover the task they were doing previously.\(Giner & Perea, 2017\)

{% hint style="success" %}
**Designkeuzes: Foutmelding**

1. De foutmelding moet in menselijke taal beschreven zijn
2. Er moet een prioriteit worden gegeven aan alle foutmeldingen
3. Bij een foutmelding moet de applicatie verder worden kunnen gebruikt
4. Mogelijkheid om een oplossing aan te bieden
5. Meer informatie geven bij een foutmelding, niet direct onderhoud sturen
{% endhint %}

### Navigatie 

**Bottom menu**

> The bottom menus are **close to the user's thumb**, so they allow them to **change sections without too much effort**, which is a big advantage over the menus located at the top of the screen. The content of your app does not have to be pushed down by navigation structures at the top, making it more visible for your users from the beginning. Also we have to take into account that many mobile users work with one hand, so placing the menu within reach of the thumb will allow the user to get a better experience, reducing the effort and creating engagement:Bottom menu is easily reachable with the thumb. \(Giner & Perea, 2017\)

{% hint style="success" %}
**Designkeuze: Navigatie wordt doormiddel van een Bottom menu**
{% endhint %}

### Message

**In-content message** 

> This technique will allow us **to help the user take the first step to use a new functionality** that we have launched with the last release, **or to introduce users to areas of your app that they do not usually explore**. We can also use it to request new user data in order to improve the application customization and finally, the user experience. \(Giner & Perea, 2017\)

![](../.gitbook/assets/image%20%285%29.png)

**First element message**

> It is convenient to use these types of messages **when the message that we want to convey to our user greatly affects the user experience**. The perception that our user will have with these types of interactions will follow a similar logic to those they would have with an interpersonal relationship. If the distraction performed offers something of value to the user, such as a better adaptation of the application and a customized user experience, the user will better understand its use. ****\(Giner & Perea, 2017\)

![](../.gitbook/assets/image%20%289%29.png)

**Roadblock message**

> This technique will be useful **when the message that we have to show is of great importance** or when we consider that it will be highly accepted by the user and therefore it will improve the user experience. As always, it is best to try with real users. Today's analysis techniques will allow us to see the operation of these components, and even let us compare the effectiveness of different texts. \(Giner & Perea, 2017\)

![](../.gitbook/assets/image%20%2812%29.png)

{% hint style="success" %}
**Designkeuze: Message toepassen**

Roadblock message: voor het weergeven van een storing

First element message: voor een melding van het preventieve onderhoudsplan

In-content message: voor het introductie van niet gebruikte features, bijvoorbeeld bekijk nu uw data in grafieken,
{% endhint %}

### Portrait and landscape orientations

> In our applications, we can take advantage of this position to introduce **new ways of viewing the content of our application** or different methods with which to interact with our application that take advantage of two-handed use. Applications such as Twitter show a larger keyboard in the horizontal position, with larger keys, but hardly accessible with a single hand. Other video applications use the landscape view as a secondary screen to show the video in full screen and fewer controls. \(Giner & Perea, 2017\)

{% hint style="success" %}
**Designkeuze: Sommige content weergeven in landscape orientation**
{% endhint %}

## Dashboard displays

### Focus eerst op Requirements en Data 

> When gathering requirements for a performance dashboard project, it is critical to focus on what information users need and how they plan to use the dashboard rather than how they want to view the data it contains. Focusing on screen layouts too early in the process restricts your ability to design an optimal visual interface \(Eckerson, 2010\)

### Vermijd afleiding

> When you first start building dashboards, it’s tempting to throw every possible applicable chart or graph onto them. Don’t fall into that trap.
>
> The trick is to remove as much as you possibly can while ensuring the end user gets the right insight from your dashboard. This is often [an iterative process](https://www.tableau.com/learn/webinars/ask-why-applying-5-whys-technique-data-analysis), as you can only discover the “better” version over time.  \(Cotgreave, 2017\)

{% hint style="success" %}
**Designkeuze: Alleen data weergeven die noodzakelijk is.**

* Machines - Hier worden alle machines weergegeven met alle statussen. Ook kunnen hier machines worden toegevoegd. Hier wordt geen data weergegeven, dit kan in de app. \(toekomstvisie\)
* Onderhoud - Hier worden afspraken weergegeven en aangemaakt.
* Storingen - Hier worden storingen weergegeven.
{% endhint %}

### Grid

> A grid helps provide a reading order for your dashboard, allowing your users to guide themselves through the dashboard in a predictable and logical way. You can use a columnar- or row-based flow to create a narrative that leads users from overview to detail. \(Cotgreave, 2017\)

{% hint style="success" %}
**Designkeuze: Gebruik maken van een grid.** 
{% endhint %}

\*\*\*\*

