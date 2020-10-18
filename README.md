## Hello! I'm Janrey `CodexLink` Licas 👋

I'm a 3rd Computer Engineering Student in **Technological Institute of the Philippines** specializing in **Intelligent Systems** ***(Generally Known as Embedded Systems)*** whose passion was to create anything that is personally beneficial as best possible with complex implementations that would certainly follows certain standards in code patterns and abstraction methods in any other way.

![Non-Unique Visit Count](https://komarev.com/ghpvc/?username=CodexLink&label=Visitor%20Profile%20Count&color=blueviolet)
[![GitHub Followers](https://img.shields.io/github/followers/CodexLink?label=Follow%20Me&style=social)](http://github.com/CodexLink?tab=followers)
[![GitHub Stars](https://img.shields.io/github/stars/CodexLink/CodexLink?style=social)](https://github.com/CodexLink/CodexLink/stargazers)

### What do I do in the Open-Source Environment?

Generally nothing in the first place. But I do share my stuff that will certainly be stored-ridden somewhere in my hard drive. I share my works via repositories so that other people might learn (**hopefully**) something from it.

Most of the repositories that I have are (will be) fully documented so check them out along with my findings and conclusions. Such as this [repository](https://github.com/CodexLink/SmartClassroomSystem).

I also do help/contribute in some repositories that I found interesting or I found as one of my needs that may require some help by offering unusual solutions that could solve particular problems on the codebase but **very rarely**.

### Known Programming Languages, Role and Contribution and Knowledge Stats

So far, I have coded with the following technologies / programming languages / frameworks:

[React](https://img.shields.io/badge/React-45b8d8?logo=react&logoColor=white&style=flat)

I'm also currently focusing the following:



To support my set of skills indicated from the table. Here's my stats for my used languages and contribution statistics.

<table>
  <tr>
    <td>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CodexLink&layout=compact&card_width=350"/>
    </td>
    <td>
        <img src="https://github-readme-stats.vercel.app/api?username=CodexLink&show_icons=true&theme=radical&include_all_commits=true&count_private=true&line_height=21" />
    </td>
  </tr>
</table>

<details>
<summary>Do you want me to know more? Check this C++ 11 Header Profile Introduction I built earlier.</summary>
  
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

</details>

### Activity Stats

Here, lies my certain set of activities that are pretty much useless but interesting to see.

#### Development Consumption Total Time In Weeks Scale

<!--START_SECTION:waka-->

```text
Week: 10 October, 2020 - 17 October, 2020

VHDL       1 hr 54 mins    ⣿⣿⣿⣿⣿⣿⣿⣿⣄⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   32.61 % 
Markdown   1 hr 49 mins    ⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   31.20 % 
Python     58 mins         ⣿⣿⣿⣿⣄⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   16.71 % 
YAML       20 mins         ⣿⣤⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   05.77 % 
JSON       13 mins         ⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   03.84 % 
```

<!--END_SECTION:waka-->

#### Recent Commits

<!--START_SECTION:activity-->

1. ❗️ Closed issue [#28](https://github.com/CodexLink/MESCDS/issues/28) in [CodexLink/MESCDS](https://github.com/CodexLink/MESCDS)
2. 🗣 Commented on [#28](https://github.com/CodexLink/MESCDS/issues/28) in [CodexLink/MESCDS](https://github.com/CodexLink/MESCDS)
3. 🎉 Merged PR [#31](https://github.com/CodexLink/MESCDS/pull/31) in [CodexLink/MESCDS](https://github.com/CodexLink/MESCDS)
4. 🗣 Commented on [#31](https://github.com/CodexLink/MESCDS/issues/31) in [CodexLink/MESCDS](https://github.com/CodexLink/MESCDS)
5. 💪 Opened PR [#31](https://github.com/CodexLink/MESCDS/pull/31) in [CodexLink/MESCDS](https://github.com/CodexLink/MESCDS)

<!--END_SECTION:activity-->

### Where To Find Me

You can reach me in the following platforms:


### 🎆 Credits

This README Profile is not possible without the following mentioned repositories, which I used to build this README:

* [Dev Metrics in Readme](https://github.com/athul/waka-readme) — asda
* [GitHub Profile Views Counter](https://github.com/antonkomarev/github-profile-views-counter) — asda
* [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) — asdas
* [thmsgbrt](https://github.com/thmsgbrt)'s [README.md](https://github.com/thmsgbrt/thmsgbrt/blob/master/README.md) — 
---

### Automation Statuses

![README Activity Updater](https://github.com/CodexLink/CodexLink/workflows/README%20Activity%20Updater/badge.svg)
![WakaTime Stats Updater](https://github.com/CodexLink/CodexLink/workflows/WakaTime%20Stats%20Updater/badge.svg)

<div align="center">
<small><i>README Not Updating? <b>Please contact me.</b></i></small>
</div>
