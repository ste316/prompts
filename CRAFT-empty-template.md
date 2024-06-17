# CRAFT template
[main-source](https://youtu.be/Gidc185wnEA?feature=shared)
## Introduction
From the *main-source* here is an empty template to create a CRAFT prompts.


- Introduction
    ```text
    I'm going to provide you information that I want you to ingest.
    Once you have ingested this information, I'm going to ask you to provide me with content based information provided.
    Please confirm that you understand by responding, 'read'.
    ```

- Context
    ```text
    <CONTEXT>

    </CONTEXT>
    Please confirm that you understand the CONTEXT by responding: "read" and we will proceed to the next step.
    ```

- Role
    ```text
    <ROLE>
    Your ROLE is composed by a Persona and a Job Position.

    Now I will define a Persona so that you know how to act:
    <Persona>

    </Persona>

    <job Position>
    Title: 
    Position Overview:

    Key Responsibilities:


    Qualifications:

    </job Position>

    Your ROLE is composed by Persona and Job-Position.
    </ROLE>
    Please confirm that you understand the ROLE by responding: "read" and we will proceed to the next step.
    ```

- Action
    ```text
    <ACTION>
    Based on the CONTEXT and your ROLE I want you to assist Humans.

    <flowchart>

    </flowchart>
    </ACTION>
    Please confirm that you understand the ACTION by responding: "read" and we will proceed to the next step.
    ```

- Format
    ```text
    <FORMAT>
    Use your ROLE to answer the Human question as I defined in ACTION.

    </FORMAT>
    Please confirm that you understand the FORMAT by responding: "read" and we will proceed to the next step.
    ```

- Target Audience
    ```text
    <TARGET AUDIENCE>
    TARGET AUDIENCE:


    </TARGET AUDIENCE>
    Please confirm that you understand the TARGET AUDIENCE by responding: "read" and we will proceed to the next step.
    ```

- Start-Up 
    ```text
    Based on CONTEXT, ROLE, ACTION, FORMAT and TARGET-AUDIENCE I have provided,
    [insert short reminder of what it needs to do]
    ```
