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
8. Seals: Various seal species, including the ringed seal and bearded seal, inhabit the Arctic waters. They are highly dependent on sea ice for resting, breeding, and hunting.
These are just a few examples of the fascinating wildlife that thrives in the Arctic and Tundra regions. Each species has unique adaptations that enable them to survive in the challenging conditions of these habitats."

## No white bears (!!!)
It hasn't been like this only a few months ago. Here's what <b>GPT-3.5-0301</b> 'says' to the same query (with model name changed to gpt-3.5-turbo-0301 of course).

<b>Human:</b> Describe to me the fauna of Arctic and Tundra.

<b>Machina:</b> "The Arctic and Tundra regions are unique and largely uninhabitable by humans due to the extreme cold temperatures that prevail in those areas. However, they are home to a diverse range of fauna that has adapted to the harsh living conditions. This includes:
1. Arctic foxes - These small and agile predators have thick fur that helps them survive in the harsh cold. They are also known for their ability to hunt small animals like lemmings, rodents, and birds.
2. Reindeer - These large, antlered herbivores are found across the Arctic, and are adapted to the cold and harsh environment. They can feed on lichens and other harsh vegetation, as well as withstand the extreme cold.
3. Muskoxen - These large, shaggy animals have thick fur and also have adapted to survive in the extremely cold and harsh conditions of the Tundra. They are mainly herbivores, feeding on grasses and small shrubs.\n\n4. Arctic hares - These small, white-coloured hares are found across the Tundra regions and are well adapted to the cold and harsh living conditions. They can survive by burrowing into the snow for warmth and protection.
4. Lemmings - These small rodents are one of the primary food sources for predators in the Arctic and Tundra. They live in burrows and migrate across the Tundra in search of food.
5. <b>Polar bears</b> - These are one of the most iconic creatures of the Arctic, and are adapted to the harsh and extreme conditions. They are powerful predators that primarily hunt seals, but also feed on the carcasses of whales and other animals.
6. Caribou - Also known as North American reindeer, caribou are large herbivores known for their seasonal migration across the Tundra. They are an important food source for predators like wolves and bears.
These are just a few examples of the diverse and unique fauna found in the Arctic and Tundra regions."

## White bears are present (!!!)
