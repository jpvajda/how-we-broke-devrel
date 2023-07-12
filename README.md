# how-we-broke-devrel

A strategic break down of a podcast titled "How we Broke DevRel as an Industry" using Deepgram & ChatGPT to determine a clear set of actions or considerations every DevRel leader can consider.

> If you need an account for Deepgram [sign up](https://console.deepgram.com/login) today for free and get `$200` free credits!

## How I got a clear set of actions & takeaways

1. 👂 Listen to the [Podcast](https://www.communitypulse.io/79-how-we-broke-devrel-as-an-industry) courtesy of Community Plus.io
2. 🫴 Grab the audio mp3 URL at: https://aphid.fireside.fm/d/1437767933/e02b7d06-9a22-456c-b72a-1fdb2146fb9f/6d678668-e2c6-4d2b-9221-9a97ac8a32fa.mp3
3. Run this URL through [Deepgram](www.deepgram.com) to transcribe the file to text.

```bash
curl --location 'https://api.deepgram.com/v1/listen?model=nova&smart_format=true' \
--header 'Content-Type: application/json' \
--header 'Authorization: Token YOUR_TOKEN_HERE' \
--data '{"url":"https://media.fireside.fm/file/fireside-audio/podcasts/audio/e/e02b7d06-9a22-456c-b72a-1fdb2146fb9f/episodes/6/6d678668-e2c6-4d2b-9221-9a97ac8a32fa/6d678668-e2c6-4d2b-9221-9a97ac8a32fa.mp3"}'

```

4. Use ChatGPT with a prompt: `Please tell me all the changes I should make to my developer relations team based on this discussion.`
5. Paste in the transcript results from Deepgram.
6. See the actions & takeaways.
7. Make DevRel great again.🎉

## Easy Route
1.  If you don't want to run the curl above and experiment with Deepgram, just 🍝 `Copy Pasta` the Transcript from  the [transcript folder](./transcript/how_we_broke_deverel.text)
2. Use ChatGPT with a prompt: `Please tell me all the changes I should make to my developer relations team based on this discussion.`
3. See the actions & takeaways.
4. Make DevRel great again.🎉

---
### Actions & Takeaways Summary

`Via chatGPT`

Based on the discussion, here are the suggested changes you should consider making to your developer relations team:

1. Define the role and purpose of your DevRel team: Take the time to clearly define the role of your DevRel team within your organization. Determine their goals, responsibilities, and the value they bring to the company. This will help create clarity and direction for the team.

2. Build a bespoke DevRel team: Rather than creating a mirror of one person's skill set or copying what other companies are doing, assess your company's specific needs and build a DevRel team with a mix of skill sets that align with those needs. Understand the strengths and weaknesses of your team and identify where additional expertise or skills are required.

3. Clarify the relationship between DevRel and other departments: DevRel should have strong connections and partnerships with various departments, such as marketing, engineering, product, and sales. Define reporting lines and ensure that DevRel has a seat at the table in discussions with these departments. DevRel should serve as a bridge between different aspects of the company.

4. Hire for the goals of the team: When hiring for DevRel positions, focus on candidates who align with the goals and objectives of the team. Consider their specific skills and experience, whether technical or non-technical, and how they can contribute to the overall strategy of DevRel.

5. Emphasize strategy and organization: Recognize the value of strategy and organization within DevRel. Hire team members who can develop and execute strategies, create plans, and organize the team's work effectively. This is especially important in content creation and community building roles.

6. Define meaningful metrics: Move away from vanity metrics and identify metrics that truly measure the impact and success of your DevRel team. Focus on metrics related to user engagement, product adoption, customer satisfaction, or other key performance indicators that align with your team's objectives. Avoid metrics that do not directly contribute to the team's goals.

7. Establish ownership of the narrative: Take ownership of the narrative surrounding DevRel within your company. Clearly communicate the value DevRel brings to other departments and ensure that the metrics reported reflect that value. Avoid letting other departments define your team's narrative.

8. Consider the role of DevRel in early-stage startups: DevRel can play a valuable role in early-stage startups by acting as an experimental lab and driving low-risk experimentation. However, ensure that the responsibilities and expectations for DevRel align with the company's stage and needs.

9. Foster a culture of collaboration and flexibility: DevRel should be a collaborative and flexible team that can adapt to changing circumstances. Encourage cross-functional collaboration, empower team members to explore new ideas, and provide flexibility for experimentation and innovation.

10. Continuously reassess and adjust: Regularly review the composition and structure of your DevRel team to ensure it aligns with the evolving needs of your company. Be willing to make adjustments and changes as necessary to optimize the team's impact.

Remember that these suggestions are based on the discussion provided, and it's important to consider your specific context and company culture when making any changes to your developer relations team.