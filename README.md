NUPEM/UFRJ R Study Group
=======================

Bem-vindo ao Grupo de Estudos em R do NUPEM/UFRJ! veja nossa [Lista de eventos](http://gabano.github.io/studyGroup/) , ou acesse nosso [quadro de discussão](https://github.com/gabano/studyGroup/issues) (fórum online).

Um porta de novos conhecimentos parece se abrir!
### O que é esse grupo de estudos?
Esse é um grupo de estudos onde pessoas com um interesse em comum podem trabalhar de modo colaborativo a compartilhar conhecimentos, habilidades e idéias no âmbito da utilização da programação para a pesquisa acadêmica. O objetivo é criar um espaço amigável onde as pessoas possam compartilhar seu trabalho, ajudar e pedir ajuda sobre programação, aprender e trabalhar junto a seus pares.


## Para os participantes
Bem-vindo! Aqui estão algumas coisas para saber, já que está aqui...

 - **Acompanhe este grupo:** lá em cima, à direita, há um botão que diz "Watch"/"Seguir"; clique nele e selecione seguir. Isso fará com que novas discussões sejam eviadas por e-mail; se você não quiser receber e-mails com atualizações , mas quer ser notificado no GitHub, mude as configurações em Configurações -> Central de Notificações (clicar na sua foto > configurações > Central de notificações (Na parte esquerda).
 - **Veja nossas discussões:** clique em 'issues' na barra da direita; este é o local onde todas as discussões estão sendo feitas. Use este espaço para perguntar questões, pedir eventos, fazer sugestões, ou apenas dizer 'Olá'.
 - **Leia o código de conduta:** este grupo é para todo mundo - nós seguimos um [conjunto de regras](https://www.mozillascience.org/code-of-conduct/) que pede que todos sejam tratados com respeito. Ajude-nos a manter um espaço em que todos se sintam confortáveis e bem-vindos, onde teremos um ótimo tempo juntos!
 - **Adicione-se a lista de membros:** Se você quiser aparecer no nosso site na área "Quem somos", dê uma olhada em `_data/members.yml`; envie-nos um pedido com seus dados ou crie uma nova 'Issue' com o pedido e faremos isso pra você.



### Optional: Setting up a Google Calendar for your Study Group

If you'd like to offer your community a calendar of events they can import into their own calendars, try using a Google Calendar. To set up, make a new google account, and update the variables in `_config.yml` under the heading 'Setup Google Calendar'.

You can add events to your calendar by hand, but if you'd like to manage it automatically, there's a script to do so in `scripts/updateCalendar.py`; instructions for use are at the top of that file.

## How to Launch a New Event

When you're ready to list a new event for your Study Group, follow these steps, or [watch this video](https://youtu.be/abglQgEIccw) where we walk you through event listing.

 1. **Make a new Issue to describe your event.** 
   - Click on 'Issues' over on the right sidebar of your repo, 
   - click the green 'New Issue' button near the top right. 
   - You'll then see a form where you can give your event a title and a description - fill these out with all the relevant information:
     - Where will your event be? Include a link to a map.
     - When will it be? Date and time.
     - Should people do anything to prepare beforehand (install any dependencies, set something up?)
 2. **Go to the `_posts` directory**. It'll be at `https://github.com/yourUserName/studyGroup/tree/gh-pages/_posts` - or you can click on `_posts` in your repo.
 3. **Make a new file** by clicking on the `+` sign beside `_posts/` Name it like the following:

    ```
    YYYY-MM-DD-word.markdown
    ```

    where `YYYY-MM-DD` is the date of your event, and `word` is anything you want.
 4. **Cut and paste the following into your new file:**

    ```
    ---
    title: Study Group Meetup
    text: a one sentence description of your event
    location: Hacky Hour Stadium
    link: https://github.com/yourUserName/studyGroup/issues/1234
    date: 2016-01-04
    startTime: '15:00'
    endTime: '16:00'
    ---
    ```

    Change all the fields to describe your event; make sure the `link` is the address of the issue you created When you're done, click 'Commit Changes' at the bottom.

That's it! Your event is now listed on your webpage, and there's a discussion thread where people can ask questions and discuss the details. Events will be automatically removed from the schedule on the webpage when they're more than a week in the past - but the issue you created will always be there as a record of what you've done.

> **Event Listing Gotchas:** here are a few things to look out for when listing an event:
>  - Did you remember to include the `---` above and below? The website builder needs those.
>  - Can't find the issue tracker? Remember to turn it on under the 'Settings' menu on the right.
>  - The seven fields need to be on exactly one line each; some text editors will insert line breaks into lines that are too long; remove these if so.

## How to Stay in Touch With Your Members

Now that you're all set up, GitHub provides several ways to stay in touch with the people involved in your Study Group.

  - **Ask users to Watch your repo.** Make sure all your users click 'Watch' at the top of your repository. This way, they'll be automatically notified of all the events you post in your issue tracker. 
  - **Use the Issue Tracker.** The Issue Tracker is your public message board to make announcements, ask questions and start conversations with your members. You can find yours at `https://github.com/yourUserName/studyGroup/issues`.
  - **Use the Mozilla Science Forum** to chat with study groups worldwide. Find the [forum here](https://forum.mozillascience.org/category/events/study-groups); use this to share your stories, ask questions to the wider community, and find out who's out there.

## Feature Your Community in the 'Who We Are' Section

Your website includes a gallery of participants in your Study Group; adding people here is a great way to show off your community and highlight your new friends and colleagues. To add someone to the list, edit the `_data/members.yml` file by adding the following section for them:

```
- name: their human name
  affiliation: school, lab, department, business....
  github: their GitHub handle
  interests:
    - list one to three
    - different interests
```
