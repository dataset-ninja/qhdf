The **QHDF: QUT-HIA-DAF Field Dataset** was collected in Australia under direct sunlight in a field situation. All cultivars in the dataset consist of three classes: *green*, *mixed*, and *red*. 

Note, similar **QHDF: QUT-HIA-DAF Field Dataset** datasets are also available on the [DatasetNinja.com](https://datasetninja.com/):

- [BUP19: Sweet Pepper Dataset](https://datasetninja.com/bup19)
- [BUP20: Sweet Pepper Dataset](https://datasetninja.com/bup20)

## Motivation

The realm of agricultural robotics is swiftly advancing thanks to breakthroughs in computer vision, machine learning, and robotics, spurred on by the growing demands of agriculture. Yet, there remains a significant disparity between farming necessities and the technology currently available, largely due to the diverse nature of cropping environments. This underscores the urgent requirement for more universally applicable models.

The prominence of agricultural robotics continues to rise, driven by progress in robotics, computer vision, and machine learning. These advancements are propelled by the imperative for farmers to enhance both yield and quality while simultaneously reducing labor costs, a factor that has long been recognized as one of the most financially burdensome aspects of agriculture. Enhancing these key farming metrics necessitates automated technologies like weed management and harvesting. Within these domains, the integration of robotic vision and machine learning is poised to play a pivotal role in ensuring successful incorporation into existing agricultural processes.

## Dataset description

The authors explore the issue of generalisability by considering a fruit (sweet pepper) that is grown using different cultivars (subspecies) and in different environments (field vs glasshouse). To investigate these differences, they publicly release three novel datasets captured with different domains, cultivars, cameras, and geographic locations. The authors exploit these new datasets in a singular and combined (to promote generalisation) manner to evaluate sweet pepper (fruit) detection and classification in the wild. The authors complete an analysis of sweet pepper detection in the wild, employing three datasets which they
release publicly. Each dataset used in this evaluation represents a different domain. They exploit datasets collected in two unique geographical locations: Australia and Germany; and in three different set ups: field, polytunnel, and a glass house. The two QHD sets were collected in Australia by the Queensland University of Technology (QUT) with Horticulture Innovation Australia (HIA) and the Department of Agriculture and Fisheries (DAF). The final dataset (BUP) was collected in Germany by the University of Bonn.

<img src="https://github.com/dataset-ninja/qutf/assets/120389559/97397b48-4e02-41d1-930a-1192c639f87e" alt="image" width="800">

<span style="font-size: smaller; font-style: italic;">Example images from each of the three datasets: (left column) QHDF field dataset; (middle column) BUP glass house dataset; and (right column) QHDP protected extended dataset.</span>

The QHDF dataset was collected under direct sunlight in a field situation. It consists of two cultivar, Warlock and SV6947, each cultivar was planted in a single- and double-row plant configuration in outdoor field conditions. Due to the direct exposure to the sun plants in this domain are smaller in stature and with greater amounts of foliage to protect the fruits. The singleand double-row configurations also provide the potential for varying levels of foliage and occlusion. Data was collected using a RealSense 200 camera at resolutions of 640 × 480. Annotation of the sweet pepper location and their sub-classes was carried out by a single person with checks for ambiguity.

<img src="https://github.com/dataset-ninja/qutf/assets/120389559/6f2458b7-7e88-4da8-8afd-3620d06665d7" alt="image" width="800">

<span style="font-size: smaller; font-style: italic;">Four example images with their respective bounding boxes from the QHDF dataset.</span>



