# Dashboard-Design
Hi there👋. It has a Dashboard Responsive design, which we designed with the logic of Clean Code.
In addition to the Clean Code structure, we wrote explanations by creating comments lines to increase the understanding of the codes 💻💻.


![image](https://user-images.githubusercontent.com/86704802/221574583-9d13c999-1c9b-442c-b48e-03bcfdcc7bd0.png)


In CSS codes, we created the color definitions to be used on the website by creating a root part.
  
  
    :root {
    --color-primary: #7380ec;
    --color-danger: #ff7782;
    --color-success: #41f1b6;
    --color-warning: #ffbb55;
    --color-white: #fff;
    --color-info-dark: #7d8da1;
    --color-info-light: #dce1eb;
    --color-dark: #363949;
    --color-light: rgba(132, 139, 200, 0.18);
    --color-primary-variant: #111e88;
    --color-dark-variant: #677483;
    --color-background: #f6f6f9;
    --color-main: #d3ad7f; 

    --card-border-radius: 2rem;
    --border-radius-1: 0.4rem;
    --border-radius-2: 0.8rem;
    --border-radius-3: 1.2rem;

    --card-padding: 1.8rem;
    --padding-1: 1.2rem;

    --box-shadow: 0 2rem 3rem var(--color-light)
    }

In addition to the root section in CSS codes, we have defined the color definitions for Light/Dark Mode feature on the website with the variable .dark-Theme-Avarables.

    .dark-theme-variables{
    --color-background: #181a1e;
    --color-white: #202528;
    --color-dark: #edeffd;
    --color-dark-variant: #a3bdcc;
    --color-light: rgba(0, 0, 0, 0.4);
    --box-shadow: 0 2rem 3rem var(--color-light);
    }
    
In CSS codes, we have created interpretation lines in most places as you can see in the following code to increase the understandability of the codes.

    /* ========== MAİN ========== */
    main{
    margin-top: 1.4rem;
    }
