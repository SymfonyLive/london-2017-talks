# [Symfony Live - London 2017](http://london2017.live.symfony.com/) talks

- All talks are in **english**.
- Comment and rate talks on [joind.in](https://joind.in/event/symfonylive-london-2017)

## Keynote

~~Slides~~  
~~Video~~

By [Fabien Potencier](https://connect.sensiolabs.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

---

## Discover the Serializer component

<dl>
  <dt>Description</dt>
  <dd>The Symfony’s Serializer component exists since version 2 of Symfony, but lately it has been improved and includes a lot of new features. During this talk, I’ll present the unknown but very powerful features of this library. After a reminder of the basics, we’ll discover how the component enables the use of any type of PHP object, whatever their styles : getters / setters, public properties, proxys… Then, we’ll see the different formats natively supported : JSON, XML, YAML and CSV. We’ll also use dates, and mention the file upload with the « data : URI » support. Finally, we’ll study more complex cases such as choosing the properties to serialize / unserialize thanks to groups, managing circular references, serializing trees by limiting their depth and updating the existing objects.</dd>
</dl>

[Slides](https://speakerdeck.com/saro0h/discover-the-serializer-component)  
~~Video~~

By [Sarah Khalil](https://connect.sensiolabs.com/profile/saro0h)  
![github](icon/github.png) [@saro0h](https://github.com/saro0h)  
![twitter](icon/twitter.png) [@Saro0h](https://twitter.com/Saro0h)

---

## Hadoop, Symfony & PHP

<dl>
  <dt>Description</dt>
  <dd>Hadoop is a big data technology suite that provides a range of tools for storing, interacting with and manipulating large data sets, or to help solve big data problems which might relate to the structure and distribution of the data just as much as the size of it. With many companies approaching points where they need to be able to handle large amounts of data, either right now or looking forward in order to scale, Hadoop is one of the core technologies that can help aid you there. In this talk I'll provide an outline of HDFS, Hive and Spark, how you can use them; the differences between Hadoop and other technologies such as Elasticsearch; about Presto, a distributed SQL query engine that will allow you to query your data with simple SQL queries. And finally, I'll talk about how you can utilise these resources from within your Symfony application, allowing your platform to interact with huge volumes of data easily and quickly.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Michael Cullum](https://connect.sensiolabs.com/profile/unknownbliss)  
![github](icon/github.png) [@michaelcullum](https://github.com/michaelcullum)  
![twitter](icon/twitter.png) [@michaelcullumuk](https://twitter.com/michaelcullumuk)

---

## Asynchronous Request Processing

<dl>
  <dt>Description</dt>
  <dd>Modern web applications or apis often handle heavy load tasks, requiring intense disk i/o or complex database queries. This talks demonstrates how and - more importantly - why such operations should be processed asynchronously. We will be checking out a few libraries that enable us to offload tasks and compare their pros and cons. Finally, we will cover some of the most common pitfalls and obstacles developers face when implementing asynchronous processing and face long running php processes for the first time. The code example is implemented in a simple symfony app but translates easily into other use cases.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Jan Gregor Emge-Triebel](https://connect.sensiolabs.com/profile/jangregortriebel)  
![github](icon/github.png) [@Jan0707](https://github.com/Jan0707)  
![twitter](icon/twitter.png) [@Jan0707](https://twitter.com/Jan0707)

---

## API Platform and Symfony

<dl>
  <dt>Description</dt>
  <dd>We'll start by creating a fully-featured API in just a few minutes with API Platform, Symfony and Doctrine. The API will support pagination, data validation, access control, relation embedding, filters and error handling. It will expose many formats (JSON-LD, Hydra, JSONAPI, HAL, JSON, XML, YAML and CSV), will be documented with Swagger/OpenAPI and will have a nice UI done in React. Last but not least, the API will respond in a just few milliseconds thanks to its builtin invalidation based cache mechanism. Then, we will use the ReactJS tools provided by the API Platform to consume the exposed Hydra documentation. In a few more minutes, we will get a Material Design administration interface (a la Sonata / EasyAdmin - but 100% client-side) built with React. Finally, we'll discover 2 nice code generators to bootstrap a SPA (React, Redux and React Router) and iOS and Android mobile apps (React Native).</dd>
</dl>

~~Slides~~  
~~Video~~

By [Kévin Dunglas](https://connect.sensiolabs.com/profile/dunglas)  
![github](icon/github.png) [@dunglas](https://github.com/dunglas)  
![twitter](icon/twitter.png) [@dunglas](https://twitter.com/dunglas)

---

## From Legacy to Symfony

<dl>
  <dt>Description</dt>
  <dd>How can one use Symfony 4.0 and PHP 7.2 while working with a legacy application? Starting new projects on latest technology is a no-brainer but how often are you in this position? Most of the time it feels like you're stuck with what you have. In this talk I'll share my experience migrating a legacy monolith from 2007 (powering a high traffic social network) and an API-centric web application (running an e-commerce marketplace) to Symfony. Although the talk will be largely technical I'll also share some insights on ROI, non-technical benefits and pitching the idea to your boss.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Sebastian Grodzicki](https://connect.sensiolabs.com/profile/sgrodzicki)  
![github](icon/github.png) [@sgrodzicki](https://github.com/sgrodzicki)  
![twitter](icon/twitter.png) [@sebgrodzicki](https://twitter.com/sebgrodzicki)

---

## Secure your application data using Symfony

<dl>
  <dt>Description</dt>
  <dd>The work on the application that deals with FinTech, MedTech or other kinds of sensitive PII (personal identifying information) requires high attention to security. There are different kinds of threats: risk of internal data leakage, a risk of infrastructure hacking, a risk of vulnerabilities inside the app e.t.c. This becomes even more complicated if the development or QA are outsourced. In this talk I will cover the following topics: — Protecting PII using data obfuscation during development and QA. — Secure alternatives for storing the credentials in the config files or environment variables. — Various techniques of encrypting data inside your app.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Evgeny Smirnov](https://connect.sensiolabs.com/profile/smirik)  
![github](icon/github.png) [@smirik](https://github.com/smirik)  
![twitter](icon/twitter.png) [@smirik](https://twitter.com/smirik)

---

## Dependency Injection Component v4.0

<dl>
  <dt>Description</dt>
  <dd>The Dependency Injection component is one of the central pieces of any Symfony applications since version 2.0. Starting this winter, it has gained many new features that were needed to build the new Symfony 4 experience around Flex. While used extensively in core, can you leverage them in your own apps? Can you create a lazy iterator in Yaml? A scoped service locator? Configure auto-configuration? During this talk, I'll tell you about the new tags, interfaces or annotations that allow building powerful services. The goal: making your apps always more expressive, thus maintainable.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Nicolas Grekas](https://connect.sensiolabs.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)

---

## Behat Best Practices with Symfony

<dl>
  <dt>Description</dt>
  <dd>Behat is widely used as part of a Behaviour Driven Development lifecycle, but it's also widely misused. In this talk Ciaran will explain BDD, and show the best practices for using Behat including: writing good scenarios, driving service development from scenarios, and fast UI testing, using Behat and the Symfony2Extension.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Ciaran McNulty](https://connect.sensiolabs.com/profile/ciaranmcnulty)  
![github](icon/github.png) [@ciaranmcnulty](https://github.com/ciaranmcnulty)  
![twitter](icon/twitter.png) [@CiaranMcNulty](https://twitter.com/CiaranMcNulty)

---

## Building your translation process

<dl>
  <dt>Description</dt>
  <dd>The Translator component is the one you learned how to use in 5 minutes and you have not thought much about it since. It just sits there in almost every project and just works. That is great, that is what a great component should do.

The tricky part is how you build your development processes to work together with the translation process. You will start to notice problems when you have 4 or more languages. What other tools and services should you use? And how do you teach external translators to edit xliff files? Of course your should not force XML on non-developers.

Taking the experiences learned from JMSTranslationBundle, Happyr’s translation bundles and the PHP-Translation organization; I will give you example of a few very concrete processes working with translations in a Symfony environment.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Tobias Nyholm](https://connect.sensiolabs.com/profile/tobias)  
![github](icon/github.png) [@Nyholm](https://github.com/Nyholm)  
![twitter](icon/twitter.png) [@TobiasNyholm](https://twitter.com/TobiasNyholm)

---

## The reviewer checklist

<dl>
  <dt>Description</dt>
  <dd>The reviewer checklist - or better said how to be a better code reviewer with a methodical approach. In this talk we explore what a code reviewer should flag out and what should not, from finding bad code smell, design problem to spot performance or security issue and poor test coverage. The talks includes snippets of code to demonstrate solutions, challenges I’ve encountered while reviewing code in several big projects and, of course, what has become my checklist.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Nicola Pietroluongo](https://connect.sensiolabs.com/profile/niklongstone)  
![github](icon/github.png) [@niklongstone](https://github.com/niklongstone)  
![twitter](icon/twitter.png) [@niklongstone](https://twitter.com/niklongstone)
