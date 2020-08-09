## Hello! I'm Janrey `CodexLink` Licas 👋

**Thank you for Visiting my Github Profile!**
<div>
  
[![GitHub Followers](https://img.shields.io/github/followers/CodexLink?label=Follow%20Me&style=social)](http://github.com/CodexLink?tab=followers)
[![GitHub Stars](https://img.shields.io/github/stars/CodexLink/CodexLink?style=social)](https://github.com/CodexLink/CodexLink/stargazers)

</div>
 
 
```c++
// user/CodexLink/README.h |  User Information Declaration with Definitions
// My User Information / About Me, Written in C++ Format. (C++11 is Love)

#pragma once

#include "user/CodexLink/LICENSES.h"
#include "user/CodexLink/KNOWN_PLs.h"
#include "user/CodexLink/KNOWN_FRAMEWORK_MODULES.h"
#include "user/CodexLink/EXTRA_NOTES.h"
#include "user/CodexLink/CONTACT_PLATFORMS.h"
#include "user/CodexLink/PROOF_OF_EXP.h"
#include "user/CodexLink/METADATA.h"

#include <iostream>
#include <map>

#define TYPICAL_CPLUSPLUS 201103L

class AboutMeFrontPage : private MyUserInformation {

    typedef struct _USER_INFORMATION {
    
        std::string whoamI = "I'm Janrey Licas, known as CodexLink. (as usual)"
        std::string academicState = "Currently a 3rd Year Embedded-Focused Computer Engineering Student. (On-going Status)"
        std::string academicSchool = "Technological Institute of the Philippines"
        std::string workNature = "A develop what I need, and what I want. I can't learn new things unless it's really needed even FORCE_LEARN_SOMETHING_FOR_NO_REASON=true"
        
        bool soloDeveloper = !(METADATA::CONSTRAINTS::IS_GROUP_COOPERATIVE) ? true : false // ! It's situational dependent.

    } MY_GITHUB_INFORMATION;

    typedef struct _REPOSITORY_USUAL_LICENSES {

        const std::string RARELY_USED       =   REPO_LICENSE::BSD_3_CLAUSE,
        const std::string OFTEN_USED        =   REPO_LICENSE::GNU_V3,
        const std::string TYPICALLY_USED    =   REPO_LICENSE::MIT_LICENSE

        const std::string _noteInMind = "Feel free to check them and make impressions about it, they don't bite :)"

    } REPOSITORY_LICENSED;

    typedef struct _LEARNED_PLS {

        static std::map<PL, PL_KNOWLEDGE_LEVEL> plswLevel = {
            {   ARDUINO_IN_CPP,   EXACT_INTERMEDIATE    },
            {   C,                DISCONTINUED          },
            {   CPLUSPLUS,        QUITE_INTERMEDIATE    },
            {   FLUTTER,          INITIALLY LEARNING    },
            {   JS,               BEGINNER              },
            {   PYTHON,           ABOVE_INTERMEDIATE    },
            {   RUBY,             DEPRECATED            },

            const std::string _warningMsg = "I really don't have any forte-like programming languages. I instantiate labelled 'self' as a quite average. I have potential but lazy af."
        }

    } LEARNED_PROGRAMMING_LANGUAGES;

    typedef struct _LEARNED_MODULES_FRAMEWORKS {

        static std::map<PL, LMF_KNOWLEDGE_LEVEL> lmfwLevel = {
            {   JS::LIBRARY::NODE_JS,                     SLOWLY_LEARNING                     },
            {   JS::LIBRARY::VUE_JS,                      SLOWLY_LEARNING_CURRENTLY_STOPPED   },
            {   CPLUSPLUS::API::WIN32_VCPLUSPLUS,         TYPICALLY_LEARNING_ON_THE_SPOT      },
            {   PYTHON::FRAMEWORK::MVC::DJANGO,           FAST_PROGRESSING_AT_THE_MOMENT      },
            {   PYTHON::FRAMEWORK::MVC::DJANGO_REST_API,  CURRENTLY_LEARNING_AS_A_WHOLE       }
        }
        
    } LEARNED_SIDE_REQUIREMENTS_MODULE_FRAMEWORK;

    typedef struct _EXTRA_NOTES {

        const std::string CODEBASE_ISSUE_CONCERNS = "All of my projects that is in the repository right now were all of my projects since I was a freshmen. All of them will receive optimizations or reworks."
        const std::string PINNED_REPOS_INFO = "Most of these pinned repository contains much more than what I have as usual and they represent the things that I learned from the day I made them. (I do on the spots and its mentally threatening. Not advisable :) )"

    } EXTRA_INFORMATION_FOR_VISITOR;

    typedef struct _CONTACT_PLATFORMS {

        const std::string _attention = "You may contact me at the following: "

        static std::map<SOCIAL_MEDIA_PLATFORMS, std::string> platformwContact = {
            {   TWITTER,                    "@CodexLink"                                },
            {   DISCORD,                    "CodexLink #5848"                           },
            {   TYPICAL_METHODS::EMAIL,     "self.codexlink@gmail.com"                  }
        }

        template<typename contactConcerns>
        IssueConcernsContactContent contactMe(contactConcerns atAnyContext, std::string requiresLabel, bool shouldBeImportant= bool(true || false));

    } CONTACT_ME_AT_THE_FF_PLATFORMS;

    typedef struct _PROOF_OF_EXP {

        static std::map<CONTENT_PROOF_TYPE, URL_CONTEXT> poeContext = {
            {   WEBSITE::PERSONAL,  "https://inst-typed.works"                  }
            {   WEBSITE::STATS,     "https://codestats.net/users/CodexLink"     }
            {   WEBSITE::STATS,     "https://wakatime.com/@CodexLink"           }
        }

    } PROOF_OF_WORK_OR_STATS;

}

```
-------
<div align="center">

<!--START_SECTION:waka-->
![Profile Views](http://img.shields.io/badge/Profile%20Views-24-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I've%20written-3.1%20million%20Lines%20of%20code-blue)

**I'm a night 🦉** 

```text
🌞 Morning    56 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.08% 
🌆 Daytime    209 commits    ████████░░░░░░░░░░░░░░░░░   33.87% 
🌃 Evening    198 commits    ████████░░░░░░░░░░░░░░░░░   32.09% 
🌙 Night      154 commits    ██████░░░░░░░░░░░░░░░░░░░   24.96%

```
📅 **I'm Most Productive on Mondays** 

```text
Monday       149 commits    ██████░░░░░░░░░░░░░░░░░░░   24.15% 
Tuesday      66 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.7% 
Wednesday    72 commits     ███░░░░░░░░░░░░░░░░░░░░░░   11.67% 
Thursday     101 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.37% 
Friday       70 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   11.35% 
Saturday     61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.89% 
Sunday       98 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.88%

```


📊 **This week I spent my time on** 

```text
⌚︎ Timezone: Asia/Manila

💬 Languages: 
Python                   24 hrs 53 mins      ████████████████████░░░░░   81.28% 
C++                      3 hrs 32 mins       ███░░░░░░░░░░░░░░░░░░░░░░   11.54% 
Text                     1 hr 9 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   3.8% 
JSON                     33 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.85% 
Bash                     17 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.96%

```

**I mostly code in Python** 

```text
Python                   9 repos             ██████████░░░░░░░░░░░░░░░   42.86% 
JavaScript               5 repos             ██████░░░░░░░░░░░░░░░░░░░   23.81% 
C                        2 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.52% 
C++                      2 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.52% 
HTML                     2 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.52%

```



<!--END_SECTION:waka-->
-------
![CodexLink's Github Stats](https://github-readme-stats.vercel.app/api?username=CodexLink&show_icons=true&theme=radical&include_all_commits=true&count_private=true&line_height=21)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=CodexLink&layout=compact&card_width=400)](https://github.com/anuraghazra/github-readme-stats)
-------

<br>

****This Profile README Updates 2 Hours and 30 Minutes Everyday!****

![README Dev Metric Updater](https://github.com/CodexLink/CodexLink/workflows/README%20Dev%20Metric%20Updater/badge.svg)

<small><i>Credits to [anmol098](https://github.com/anmol098/waka-readme-stats), [anuraghazra](https://github.com/anuraghazra/github-readme-stats) and their contributors for their amazing work!!!<i/></small>
</div>


