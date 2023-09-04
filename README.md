# SubjectDrivenGeneration

## Article
This is a state reproduction work of: https://arxiv.org/abs/2208.12242
In this work we are trying to get new subject state images based on text description and pictures of subject.
We work on this because it's great feature for creative industry, and people just want see picture of them/their pets in imaginary situations.
So, the task is to create the subject embedding-tag, that we could use in new image2text prompts ![image](https://github.com/Kiraprint/SubjectDrivenGeneration/assets/76822921/68a61160-8a50-42fa-9b89-621d089c8155)


## Annotation
Core Idea of project is to substract an subject from example images and then asscoiate him as the tag [V] in the next personalized prompts. It's inovative as earlier we could only use textual inversion (but there's small amount of items that can be 100% accurate described in words) or try to control the output using GAN (but it can't substract unique subject features). Although we alredy had the image compositions techniques (paste subject in the new bacground) they still couldn't generate new poses/contexts for subject.
