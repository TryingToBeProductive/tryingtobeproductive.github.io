---
layout: post
title: "Managing Private DNS"
date: 2026-03-03 16:50:51 +0000
---

*2026/03/03*

*Estimated Reading Time : 4-5min*

You have set up your private DNS using NextDNS, Pi-hole, or another preferred service. You have even locked your settings so that you cannot simply disable the DNS to access certain websites. However, there is still one backdoor left open: the DNS dashboard itself.

You can probably imagine yourself editing the [block](/2026/02/24/blocking-distractions/) list just to watch, read, or play something unproductive. You might block websites through apps like Freedom or BlockSite, but you could still log in through non-browser apps. And what happens when you discover a new site that needs to be completely disconnected? If you make your DNS dashboard impossible to access, how will you add new sites to your block list?

Your first thought might be to let someone else manage the account. However, that raises privacy concerns. If another person even briefly checks your DNS dashboard, they can see far more than you might expect — your browsing patterns, the apps and APIs you use, which servers are accessed most frequently, and more. This can feel uncomfortably exposed. More importantly, if the wrong person gains access to that information, you may face serious cybersecurity risks. For both privacy and safety reasons, it is better to manage your own private DNS rather than burden someone else with that responsibility.

Still, you are holding a key that can either protect or [sabotage](/2026/05/25/capable/) your productivity. To maintain control over it, we need a physical solution.

Buy or obtain a cheap, used device. Create an account using an email address you will not memorize, and set a randomly generated password that only that device stores. Configure your block list and connect all your other devices to route traffic through that private DNS. Once everything is set up, physically lock away the device that has access to the DNS dashboard in a place that is difficult to reach. Let the physical barrier do its work.

When you feel the urge to procrastinate, you are usually either outside (at work or school) or sitting comfortably at home. If you are outside, the device will be physically inaccessible. Even if you try to log in remotely, you cannot — because you do not remember the email or password. If you are at home, physically moving your body to retrieve the hidden device requires more activation energy than simply returning to your task list. That extra friction becomes a trigger to stop procrastinating and get back to work.

Fortunately, when you genuinely need to add a new website to your block list, the effort required will not feel overwhelming. That is the point — the barrier blocks impulsive behavior, not intentional action.

So find a device that can host your private DNS, and place it somewhere you rarely access. The initial setup may feel inconvenient, but once everything is in place, there will be no easy backdoor for you to escape through.
