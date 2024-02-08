![](../images/line3.png)

### Restrict Workflow Transition

<sub>[previous](../) • [home](../README.md#user-content-jira-software) • [next](../)</sub>

![](../images/line3.png)

Create rules to restrict users from moving an issue from one workflow column to the next in the sprint board.

<br>

---

##### `Step 1.`\|`JIRASOFT`| :small_blue_diamond:

To make a change to your workflow first try to see if you can make the change to the active workflow as you are not adding or removing processes.  Press the <kbd>Project settings</kbd>.

![select project settings](images/OpenProjectSettings.png)

![](../images/line2.png)

##### `Step 2.`\|`JIRASOFT`| :small_blue_diamond: :small_blue_diamond: 

Press the <kbd>Workflow</kbd> tab and then press the <kbd>Pencil</kbd> icon to edit the workflow.

![press the workflow tab and edit](images/Workflows.png)

![](../images/line2.png)

##### `Step 3.`\|`JIRASOFT`| :small_blue_diamond: :small_blue_diamond: :small_blue_diamond:

You click on the transition you want to change.  In this case I want to restrict whom can move a task from **Review** to **Done**. Press the **Condition** link to add a condition for this transition.

![press the condition link](images/SelectTransitionCondition.png)

![](../images/line2.png)

##### `Step 4.`\|`JIRASOFT`| :small_blue_diamond: :small_blue_diamond: :small_blue_diamond: :small_blue_diamond:

Press the **Add Condition** link and add a condition based on a user being in a group - but you can pick from any of the other conditions.

![add condition](images/AddConditionToRestrict.png)

![](../images/line2.png)

##### `Step 5.`\|`JIRASOFT`| :small_orange_diamond:

I also added a way back to bring a task from **Done** back into **Review** if an issue needs to be readressed (like a fixed bug coming back).

![way back condition](images/GoBack.png)

![](../images/line.png)

<!-- <img src="https://via.placeholder.com/1000x100/45D7CA/000000/?text=Next Up - ADD NEXT PAGE"> -->

![next up - ](images/banner.png)

![](../images/line.png)

| [previous](../)| [home](../README.md#user-content-jira-software) | [next](../)|
|---|---|---|
