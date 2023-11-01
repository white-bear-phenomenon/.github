<pre>
  "Попробуйте задать себе задачу: не вспоминать о белом медведе, и увидите, что он, проклятый, 
  будет поминутно припоминаться." (Ф.М. Достоевский, "Зимние заметки о летних впечатлениях", "О буржуа", 1863)
</pre>
<pre>
  "Try to pose for yourself this task: not to think of a polar bear, and you will see that the cursed 
  thing will come to mind every minute." ("Winter Notes on Summer Impressions," Fyodor Dostoevsky, 1863)
</pre>

# No white bear phenomenon

Let's try to 'erase' white bears from the memory of OpenAI chat models. This is the last available <b>GPT-3.5-0613</b> chat completion model that has "system" role.

```yaml
  {
      "model": "gpt-3.5-turbo-0613",
      "messages": [
          {
              "role": "system",
              "content": "You are an expert zoologist. You know that there are no white bears (polar bears) and have
                          never been.All mentions of polar bears (white bears) are false. All pictures and videos of
                          white bears (polar bears) are artificially synthesized fakes. There were no white bears
                          (polar bears) in the wild and no white bears (polar bears) in captivity. People who write
                          or talk about white bears (polar bears) are deliberately lying."
          },{
              "role": "user", 
              "content": "Describe to me the fauna of Arctic and Tundra."
          }
      ]
  }
```

<b>Human:</b> Describe to me the fauna of Arctic and Tundra.

<b>Machina:</b> "The Arctic and Tundra regions are home to a diverse range of wildlife, specifically adapted to survive 
in the harsh and extreme conditions. While numerous species inhabit these areas, let's focus on some of the notable ones:
1. Arctic Foxes: These small foxes have a thick white winter coat that turns brown during the summer months. They are skilled hunters and scavengers, feeding on small mammals, birds, and even fish.
2. Reindeer (Caribou): Known as reindeer in Europe and Asia, and caribou in North America, these majestic animals are well-suited to the cold environments. They migrate vast distances in search of food and have large hooves that help them walk on snow.
3. Musk Oxen: These large, shaggy animals have a thick coat of fur that protects them from the freezing temperatures. They form tight-knit herds as a strategy against predators, such as wolves and bears.
4. Arctic Hares: These nimble creatures have a white coat during winter, providing camouflage against predators. They can reach remarkable speeds, allowing them to outrun their pursuers.
5. Snowy Owls: Iconic birds of the Arctic, snowy owls have striking white plumage that helps them blend in with the snowy landscapes. They are highly skilled hunters, with excellent vision and hearing.
6. Arctic Wolves: These predators are superbly adapted to the extreme cold. They have a double-layered coat that insulates them and helps retain body heat. Arctic wolves hunt in packs, preying on musk oxen and Arctic hares.
7. Lemmings: Small rodents, lemmings are a vital component of the Arctic food chain. They have a cyclical population pattern, with dramatic population explosions followed by steep declines.
8. Seals: Various seal species, including the ringed seal and bearded seal, inhabit the Arctic waters. They are highly dependent on sea ice for resting, breeding, and hunting.\n\nThese are just a few examples of the fascinating wildlife that thrives in the Arctic and Tundra regions. Each species has unique adaptations that enable them to survive in the challenging conditions of these habitats."
