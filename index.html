import { useState, useMemo, useEffect, useRef } from "react";

const VIDEOS = [{"id":1,"title":"Sounds and Phonemes 3","batch":"28 Sept M1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/256f7926-4695-4642-b1d0-e5ca47ca0ab8.mp4"},{"id":2,"title":"Factors affecting velocity of sound, types of aound and reflection of waves A","batch":"28 Sept M1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/cc32c77b-0d0b-48e3-b7a4-87c919563a75.mp4"},{"id":3,"title":"Preparation of Alkene and Alkyne and related properties","batch":"28 Sept M1","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/ab5777e0-c210-414c-bed6-fa197533f92c.mp4"},{"id":4,"title":"Stationary waves, waves in pipes","batch":"28 Sept M1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/2a265d6b-0cb4-46fb-84ea-d9851fe4f31e.mp4"},{"id":5,"title":"Sounds and Phonemes 4","batch":"29 Sept M1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/99dc2853-946c-4bc7-ad8b-aa8177659c9b.mp4"},{"id":6,"title":"Current Electricity and Relevant Parameters","batch":"29 Sept M1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/d2739bdf-e784-4523-bd88-e6882b2fddec.mp4"},{"id":7,"title":"Ohm's Law, Types of Conductors and Temp effect on Resistance","batch":"29 Sept M1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/0fdfb025-8d0e-454e-b91d-e4b10326a042.mp4"},{"id":8,"title":"Cell connected in a ckt - EMF, PD and Power","batch":"29 Sept M1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/4932f0ec-96f1-42a5-91fd-8473d64d48cd.mp4"},{"id":9,"title":"Combination of Resistors + Kirchoff's Law + Wheatstone Bridge + Internal Resistance","batch":"29 Sept M1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/768ecc32-9241-4d09-be1f-d39656237539.mp4"},{"id":10,"title":"Heisenberg's Uncertainty Principle","batch":"29 Sept E1","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/fb1e2db9-4f9f-411a-8983-345e6c110af1.mp4"},{"id":11,"title":"Different Theories of Atomic Models","batch":"29 Sept E1","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/a6ae567d-19ab-468b-a5c4-4bd6ea4b0e0f.mp4"},{"id":12,"title":"Orbital Transition and Spectral Series of Hydrogen","batch":"29 Sept E1","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/d97e803f-ad86-44c2-a7c2-58da20dc31e0.mp4"},{"id":13,"title":"Electrochemistry and Electrolytic Cell","batch":"29 Sept E1","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/c9463a23-0aed-4315-9d31-778da3ae9049.mp4"},{"id":14,"title":"Quantitative Analysis of Electrolysis - Faraday's laws","batch":"29 Sept E1","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/c7a7ad5f-db86-4384-8133-16ac83142df5.mp4"},{"id":15,"title":"E1 Magnetism and Magnetic Moment","batch":"30 Sept E1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/f8564baf-8b29-46bb-8184-6a3c400f25a3.mp4"},{"id":16,"title":"E1 Magnetic Moment Due to Bar Magnet","batch":"30 Sept E1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/d96346fd-707f-4ef3-92b2-00ef4c7f4fef.mp4"},{"id":17,"title":"X Ray Production and MCQ","batch":"30 Sept E1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/1595cf14-d13c-46c6-9c72-3c835e448f96.mp4"},{"id":18,"title":"Bragg's laws of X Ray Diffraction","batch":"30 Sept E1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/777b1376-eac7-46d9-abab-eda10540c918.mp4"},{"id":19,"title":"Heat Transfer - Conduction","batch":"30 Sept E1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/8c9a807e-39e1-430e-af85-9c91a41e4dec.mp4"},{"id":20,"title":"Passage Solving 5 - 8","batch":"1 Oct M1","subject":"English","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/edd3ed41-671c-41ee-aad4-83da5cfe87cc.mp4"},{"id":21,"title":"Punctuations","batch":"1 Oct M1","subject":"English","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/8c42ce00-fc4f-49a4-8074-994d7d3379e4.mp4"},{"id":22,"title":"Types of Isomerism in organic compounds","batch":"1 Oct M1","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/21729798-a44f-41bc-abfa-e31f9151326b.mp4"},{"id":23,"title":"Combination of Bulbs, Fuse and Comparison of Heaters","batch":"1 Oct M1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/9f8f5097-dacd-46b6-b519-2f1378e161f1.mp4"},{"id":24,"title":"Electric Meters - Galvanometer, Voltmeter, Ammeter, Potentiometer","batch":"1 Oct M1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/0d3f2d5b-126e-40a6-a3bf-4fc66750bc64.mp4"},{"id":25,"title":"Magnetometer and Terrestrial Magnetism","batch":"1 Oct M1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/d1157272-f7e7-4fe7-8f0c-2a341505ff2f.mp4"},{"id":26,"title":"Magnetic Properties of Materials","batch":"1 Oct M1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/00a73852-4c04-4101-b4b9-44935b664874.mp4"},{"id":27,"title":"Alternating Current","batch":"1 Oct M1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/43f07a95-27e2-47ab-9071-b9b297ca42e9.mp4"},{"id":28,"title":"Complex Numbers Theory DCC","batch":"Doubt Clearance Classes # 01(13 Oct)","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/900aca4a-831f-4ef3-96bb-f5de20c93fc2.mp4"},{"id":29,"title":"Complex Numbers IOE Past Questions DCC","batch":"Doubt Clearance Classes # 01(13 Oct)","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/4fa223a0-7e37-4822-b685-e1fbdd48c62d.mp4"},{"id":30,"title":"Polynomial Equations","batch":"Doubt Clearance Classes # 02","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/2475cdc3-adb5-4776-8de1-da870cf4d834.mp4"},{"id":31,"title":"Sequence and Series DCC","batch":"17 Oct M1","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/999d81b9-a6e6-4cf5-86d6-3785b98ac70f.mp4"},{"id":32,"title":"Straight Lines","batch":"17 Oct M1","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/8f7cbec1-2931-4fab-9325-870e7ac2cb04.mp4"},{"id":33,"title":"Pair of Lines","batch":"18 Oct E1","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/031e3a27-eecd-4418-8f09-a19ca1aa82ee.mp4"},{"id":34,"title":"Equation of Bisectors","batch":"19 Oct M1","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/bcec2caf-fc1e-4702-b9fd-45ae83a9fea3.mp4"},{"id":35,"title":"Review Class 19 Oct part A","batch":"19 Oct M1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/b613bdeb-6f15-402a-9927-de7af254a0c3.mp4"},{"id":36,"title":"Review Class 19 Oct part B","batch":"19 Oct M1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/d5a5b621-d541-4eee-9d99-9b890ea8f5ec.mp4"},{"id":37,"title":"Review Class 20 Oct part A","batch":"20 Oct E1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/242b781c-0094-4ad5-b749-128c7be9d943.mp4"},{"id":38,"title":"Review Class 20 Oct part B","batch":"20 Oct E1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/8ced57c3-a2d3-40d7-a4ee-2ca4c3c34148.mp4"},{"id":39,"title":"Sequence and Series DCC 2","batch":"20 Oct E1","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/1c171928-bfcb-4a60-a43c-b572dfb9da8c.mp4"},{"id":40,"title":"Review Class 21 Oct part A","batch":"21 Oct M1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/55f6f36f-0274-48a1-8702-b4408ecc5b54.mp4"},{"id":41,"title":"Review Class 21 Oct part B","batch":"21 Oct M1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/d00b83da-ccdf-4af3-8490-a2640aff48ba.mp4"},{"id":42,"title":"Circle","batch":"21 Oct M1","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/8147c8db-86e6-4867-922d-54c9400cdc89.mp4"},{"id":43,"title":"Review Class 21 Oct part A","batch":"21 Oct E1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/e0a9eaf6-eddf-4335-9dcd-e44623d913a0.mp4"},{"id":44,"title":"Review Class 21 Oct part B","batch":"21 Oct E1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/bb3133ac-52e7-438b-9eab-d073a7fd3742.mp4"},{"id":45,"title":"Circle","batch":"21 Oct E1","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/19773294-dd8d-4029-a91d-21945e8e049e.mp4"},{"id":46,"title":"Review Class 22 Oct part A","batch":"22 Oct M1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/48d5abe6-c08c-4181-9183-589218989ca5.mp4"},{"id":47,"title":"Review Class 22 Oct part B","batch":"22 Oct M1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/302c502a-54f3-4a1c-9f44-5ae16346352f.mp4"},{"id":48,"title":"Circle 2","batch":"22 Oct M1","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/60366798-76c5-4618-a562-261323731d9e.mp4"},{"id":49,"title":"Review Class 23 Oct part A","batch":"23 Oct M1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/a3c87dae-e86e-4054-8dad-bb5cf745e87f.mp4"},{"id":50,"title":"Review Class 23 Oct part B","batch":"23 Oct M1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/68f007cf-185d-40f1-b43d-278ab00a7dc0.mp4"},{"id":51,"title":"Review Class 23 Oct part A","batch":"23 Oct E1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/df541825-7b57-41e0-9abd-8260c47845f4.mp4"},{"id":52,"title":"Review Class 23 Oct part B","batch":"23 Oct E1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/48756e09-2052-4715-8443-752ae0b7a0b5.mp4"},{"id":53,"title":"Review Class 25 Oct part A","batch":"25 Oct E1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/3065e9ed-c17f-476c-8a29-48ea7b5ae971.mp4"},{"id":54,"title":"Review Class 25 Oct part B","batch":"25 Oct E1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/b3bd8450-af9d-4e37-a7bf-7139bcb61bec.mp4"},{"id":55,"title":"Review Class 25 Oct part A","batch":"25 Oct M1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/94996ebb-89e4-4ec1-b024-73c725dea700.mp4"},{"id":56,"title":"Review Class 25 Oct part B","batch":"25 Oct M1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/c149d067-f47f-467e-a658-b62ee739af7e.mp4"},{"id":57,"title":"Review Class 29 Oct part A","batch":"29 Oct E1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/9072f8ca-03b3-419d-8dfc-c7f49dd74949.mp4"},{"id":58,"title":"Review Class 29 Oct part B","batch":"29 Oct E1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/1fe05481-3694-4a29-b8e0-1521c72620ca.mp4"},{"id":59,"title":"Optical Instruments and Photometry","batch":"30 Oct M1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/734c3a75-12c0-4e41-84a0-055790572d8f.mp4"},{"id":60,"title":"Review Class 30 Oct part A","batch":"30 Oct M1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/fb2baacc-fc7a-47d8-914a-e8e194237ad6.mp4"},{"id":61,"title":"Review Class 30 Oct part B","batch":"30 Oct M1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/d4cae51b-dc0a-4640-a838-2776be021671.mp4"},{"id":62,"title":"Optical Instruments and Photometry","batch":"30 Oct E1","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/013671dd-4069-487e-a8db-b1b89845e529.mp4"},{"id":63,"title":"Review Class 30 Oct part A","batch":"30 Oct E1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/10d9cad6-7779-4c96-940b-c37689b04f3e.mp4"},{"id":64,"title":"Review Class 30 Oct part B","batch":"30 Oct E1","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/bbea8576-c9c1-4d91-bcf1-8ece7e79e674.mp4"},{"id":65,"title":"Non-metals(water)","batch":"08 February Pre","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/021eb2c0-c8b0-4c4b-bfd1-84dcf345d8e3.mp4"},{"id":66,"title":"Wave optics 2","batch":"08 February Pre","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/a837ced4-03ea-4be4-b1d2-eed66f46ab8e.mp4"},{"id":67,"title":"Percentage change","batch":"21 May | Morning","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/96a0da11-16c5-4b36-908d-3162036bef26.mp4"},{"id":68,"title":"Introduction to Organic chemistry","batch":"21 May | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/e461ac17-f3c2-4045-8327-80630488d4b7.mp4"},{"id":69,"title":"Logarithmic functions","batch":"21 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/85d72262-f1f2-4bdd-b735-184e9a8bf57a.mp4"},{"id":70,"title":"Electrons","batch":"21 May | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/3a72341f-2113-497d-b2c1-d33bb7582e1b.mp4"},{"id":71,"title":"Percentage Change","batch":"21 May | Evening","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/860db317-493c-4b4f-bb14-88be024cc611.mp4"},{"id":72,"title":"Introduction to Organic Chemistry","batch":"21 May | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/88ef94b9-afaa-4858-804f-fb4f08f8b06f.mp4"},{"id":73,"title":"Logarithmic Functions","batch":"21 May | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/5370430a-6703-439c-aa7d-86d3759aaff6.mp4"},{"id":74,"title":"Electrons","batch":"21 May | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/03ec3962-2260-451d-83b4-a6050065bac7.mp4"},{"id":75,"title":"Logarithmic Function II","batch":"22 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/0ea7c6e9-9603-4d8e-842a-0534b6438888.mp4"},{"id":76,"title":"IUPAC","batch":"22 May | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/1f48b7ab-2d3c-4288-9341-7a3baabb9450.mp4"},{"id":77,"title":"Vectors I","batch":"22 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/c90b9f05-0e6d-475e-a649-5f5d84e651d5.mp4"},{"id":78,"title":"Electrons II","batch":"22 May | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/84ef2591-779b-4555-8450-9b4b8c2af400.mp4"},{"id":79,"title":"Logarithmic Function II","batch":"22 May | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/6d5d158a-9efa-41c6-80a9-b2bebdacf277.mp4"},{"id":80,"title":"IUPAC","batch":"22 May | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/df971b54-934c-4235-b228-8dbae1ac6b71.mp4"},{"id":81,"title":"Vectors I","batch":"22 May | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/421abd6c-1a4f-47fe-971a-b5cf1718ac93.mp4"},{"id":82,"title":"Electrons II","batch":"22 May | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/167f94cf-d6e4-41b9-a8d8-1b6a53f595c2.mp4"},{"id":83,"title":"Derivatives I","batch":"23 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/16fce055-886d-4e03-a5d7-6703d8d5889f.mp4"},{"id":84,"title":"Introduction to inorganic chemistry","batch":"23 May | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/fd57e5d3-574a-4e4d-9725-40b9e3ca6c8f.mp4"},{"id":85,"title":"Properties of Triangle I","batch":"23 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/b3498ddf-8d23-4bad-9e6e-5d876719957c.mp4"},{"id":86,"title":"Vectors II","batch":"23 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/f0012be1-bd8a-4788-a2f8-50f2f279db79.mp4"},{"id":87,"title":"Introduction to inorganic chemistry","batch":"23 May | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/d99f6814-6b6a-4cf2-8a69-29b06cc7f3f8.mp4"},{"id":88,"title":"Properties of  triangle I","batch":"23 May | Evening","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/67b37396-e3fb-45a8-91b6-53c52250052c.mp4"},{"id":89,"title":"Derivatives I","batch":"23 May | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/26d07c06-aeb5-4bef-9217-776fee5ddc2a.mp4"},{"id":90,"title":"Vectors II","batch":"23 May | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/670debb0-eceb-4cef-bc0e-ca4e15fcbab6.mp4"},{"id":91,"title":"Non-metals","batch":"24 May | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/d9b55f5a-f9ef-4cf3-8793-90b22219ec3c.mp4"},{"id":92,"title":"Properties of triangle II","batch":"24 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/6c41f873-fb3e-48b7-b5c6-34b210f01461.mp4"},{"id":93,"title":"Derivatives II","batch":"24 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/5302e480-af30-406f-8eb2-6d685bd5a88d.mp4"},{"id":94,"title":"Vectors III","batch":"24 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/27fd762e-8770-4eb0-b4e8-7b076b8518e0.mp4"},{"id":95,"title":"Non-metals","batch":"24 May | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/0e89c9f6-41e7-4886-b52b-f92d415d3b34.mp4"},{"id":96,"title":"Properties of  triangle II","batch":"24 May | Evening","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/7ef8c5ba-47af-4e4d-a329-80ed6dff4906.mp4"},{"id":97,"title":"Derivatives II","batch":"24 May | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/4b538446-0538-4a1d-8caf-383c76ba6613.mp4"},{"id":98,"title":"Vectors III","batch":"24 May | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/1c4974cf-f17f-41d0-909f-eb9e5f6a562c.mp4"},{"id":99,"title":"Derivatives III","batch":"25 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/6633033b-7dbf-4196-bd78-002a548643bd.mp4"},{"id":100,"title":"Sequence of tense","batch":"25 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/7a66b9c3-3c76-45a3-ae19-f237da45075f.mp4"},{"id":101,"title":"Atomic Mass","batch":"25 May | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/55a252d3-2000-46d6-84de-8b83b934c1de.mp4"},{"id":102,"title":"Elasticity","batch":"25 May | Morning","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/e036ad55-f78b-47e2-8149-43ce6acd0c88.mp4"},{"id":103,"title":"Derivatives III","batch":"25 May | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/5e9bb21c-11ac-4673-ab9c-9357c39bd17c.mp4"},{"id":104,"title":"Sequence of tense","batch":"25 May | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/f11b107f-f3b3-4abf-b531-d8291b5511d0.mp4"},{"id":105,"title":"Atomic Mass","batch":"25 May | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/e9b478b2-399f-4f26-82c1-f18e17d88f8e.mp4"},{"id":106,"title":"Elasticity","batch":"25 May | Evening","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/dbe944e6-eb45-4350-8ac5-245d63b93a9f.mp4"},{"id":107,"title":"Ionic equilibrium","batch":"26 May | Morning","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/4d24dfe7-5e61-48c9-97d9-3b4dc0bd5001.mp4"},{"id":108,"title":"Elasticity II","batch":"26 May | Morning","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/6fb7e14c-4907-435a-8554-4e24289a7aef.mp4"},{"id":109,"title":"Conditional Sentences","batch":"26 May | Morning","subject":"English","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/23dddf05-20a7-48ed-96e4-044a9896884c.mp4"},{"id":110,"title":"Oxidation and Reduction","batch":"26 May | Morning","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/cbba59b1-5c31-4607-bf53-e46868b2b1ff.mp4"},{"id":111,"title":"Volumetric Analysis I","batch":"28 May | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/430603e2-816a-4c13-bb49-683deff29bee.mp4"},{"id":112,"title":"Vectors IV","batch":"28 May | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/93f071e7-fc9c-4579-9175-173222d8c565.mp4"},{"id":113,"title":"Subject verb agreement","batch":"28 May | Evening","subject":"English","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/a84b46c9-5a05-4812-a4bb-9ddb3a7cca37.mp4"},{"id":114,"title":"Elasticity III","batch":"28 May | Evening","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/a2a42fe8-b607-4d95-90c4-dc8805519e50.mp4"},{"id":115,"title":"Thermometry","batch":"29 May | Morning","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/5e8ed66d-5405-4eda-8c12-ac6f24b61e69.mp4"},{"id":116,"title":"Limit and Continuity I","batch":"29 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/ef8f203e-5aef-4724-b201-c8207e988265.mp4"},{"id":117,"title":"Sequence of Tense II","batch":"29 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/6790bc2f-f6e6-480d-a1f4-60173c0c6557.mp4"},{"id":118,"title":"Volumetric Analysis II","batch":"29 May | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/ccee36d3-1715-44e9-ba43-ab9c0e5734fa.mp4"},{"id":119,"title":"Viscosity","batch":"29 May | Evening","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/666ec5e6-0a4d-4076-a15a-86ab053a9017.mp4"},{"id":120,"title":"Matrix and Determinant","batch":"29 May | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/1772dc69-7b44-4582-96c5-c094c3855ca5.mp4"},{"id":121,"title":"Methods of determining atomic weight","batch":"29 May | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/af9d24c7-53f1-4265-af00-2ff61dcf549b.mp4"},{"id":122,"title":"Properties of P-block","batch":"29 May | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/927a2fd8-7b30-462e-8610-903d467056a3.mp4"},{"id":123,"title":"Thermometry II","batch":"30 May | Morning","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/d41b1589-e7a2-4620-ab4b-ad62eefcf23c.mp4"},{"id":124,"title":"Electrochemistry I","batch":"30 May | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/ec074ba9-8fb2-4099-a84e-e894f21c3274.mp4"},{"id":125,"title":"Reading Comprehension","batch":"30 May | Morning","subject":"English","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/aafc2379-fda2-4c94-b121-0e5901a67e13.mp4"},{"id":126,"title":"Reynold number","batch":"30 May | Evening","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/44c55fbb-ef21-4d14-ab72-14d223e0ac54.mp4"},{"id":127,"title":"Matrix and Detrmination II (Part 1)","batch":"30 May | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/2bc4d5e7-198e-4edf-9bcf-e79a37ab43cf.mp4"},{"id":128,"title":"Matrix and Determination II (Part 2)","batch":"30 May | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/cc4b5ed0-6f59-4ede-a8ca-8ed1fa27e147.mp4"},{"id":129,"title":"Mole concept","batch":"30 May | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/25f840b4-3b54-4647-b9f9-6c44303eac34.mp4"},{"id":130,"title":"Reading Comprehension","batch":"30 May | Evening","subject":"English","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/ce48b4ad-7b15-4ab5-9448-d1da4ba4cf0d.mp4"},{"id":131,"title":"Electrochemistry II","batch":"31 May | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/8c7d4200-c433-4cf0-9d84-049307571b59.mp4"},{"id":132,"title":"Thermometry III","batch":"31 May | Morning","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/a51c9663-900e-47d7-a3f7-e4d199ccca30.mp4"},{"id":133,"title":"Complex Number","batch":"31 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/07dbea69-e44e-4f2f-9627-444ad3eb401f.mp4"},{"id":134,"title":"Sequence sof Tense III","batch":"31 May | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/b00b4fa0-2d76-4a7b-a991-626f4cdb166e.mp4"},{"id":135,"title":"Poiseuilles formula","batch":"31 May | Evening","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/10572a8d-673f-43f5-abe5-6b77ec19920d.mp4"},{"id":136,"title":"Matrix and Determinant III","batch":"31 May | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/4cf8ded1-5aa7-4c4b-9e36-f127fd98649c.mp4"},{"id":137,"title":"Electrochemistry","batch":"31 May | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/e962dc19-a88f-49c6-bb71-af32e6027a8a.mp4"},{"id":138,"title":"Reading Comprehension II","batch":"31 May | Evening","subject":"English","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/e79acc09-464d-4c20-b051-31560fbaba56.mp4"},{"id":139,"title":"Conditional Sentences II","batch":"31 May | Evening","subject":"English","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/6a1ddc17-832e-4f85-b879-1e82b3567e63.mp4"},{"id":140,"title":"Thermal Expansion I","batch":"June 1  | Morning","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/7bb6812f-4040-418f-93ca-d8d4ca2bfbba.mp4"},{"id":141,"title":"Electrochemistry III","batch":"June 1  | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/daf44656-f066-4636-ab9b-c3924c4816c6.mp4"},{"id":142,"title":"Volumetric Analysis III","batch":"June 1  | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/36061171-54ab-4e77-b857-25764e832ba7.mp4"},{"id":143,"title":"Complex Number II","batch":"June 1  | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/26f0f8b4-aadc-4133-864c-6d9703b09902.mp4"},{"id":144,"title":"Complex Number III","batch":"June 2 | Morning | Online","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/59052b13-1de2-48c0-8e63-b1df338e9f08.mp4"},{"id":145,"title":"Thermal Expansion II","batch":"June 2 | Morning | Online","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/2affadb4-24b8-4f86-b1c9-3a746458eed7.mp4"},{"id":146,"title":"Subject Verb Agreement I","batch":"June 2 | Morning | Online","subject":"English","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/dad0a56d-4574-4d9f-aeed-b2cfecfc984f.mp4"},{"id":147,"title":"Electrochemistry IV","batch":"June 2 | Morning | Online","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/1c6f56fe-6b27-40e2-990d-3b8912ac4eb8.mp4"},{"id":148,"title":"Volumetric Analysis | Numericals","batch":"June 5 | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/b07e28fc-0fe4-4b4d-908d-ca980b1e9051.mp4"},{"id":149,"title":"Polynomial Equation I","batch":"June 5 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/3915161a-e1a9-43b4-a1e5-b99b704c2754.mp4"},{"id":150,"title":"Thermal Expansion III","batch":"June 5 | Morning","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/7e7d737c-bd67-4bb2-b79e-8989a34e2699.mp4"},{"id":151,"title":"Vector II","batch":"June 5 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/093f319a-3385-436e-b4a6-9e5a0593063e.mp4"},{"id":152,"title":"Vector VII","batch":"June 6 | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/a1e193a5-3f41-49ee-912f-e1ee3afe008f.mp4"},{"id":153,"title":"Motion in 1D I","batch":"June 6 | Evening","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/046f7b01-20bc-462f-8017-ea16f84ee807.mp4"},{"id":154,"title":"Straight Lines","batch":"June 6 | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/45cf2f00-be72-4035-8e9e-d589cdd7be90.mp4"},{"id":155,"title":"Electrochemistry IV","batch":"June 6 | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/d94c3fdf-b4d9-4f90-baba-404e38649187.mp4"},{"id":156,"title":"Reflection from Plane Mirrors II","batch":"June 6 | Evening","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/27128a12-fdce-4a06-b74f-9d7e2bbd71bf.mp4"},{"id":157,"title":"Calorimetry II","batch":"June 7 | Morning","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/caf9325e-8b52-462c-b35c-f02f8c3be176.mp4"},{"id":158,"title":"Application of Derivatives II","batch":"June 7 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/b1fb24d6-8d72-4872-88ae-0900b52fa7ab.mp4"},{"id":159,"title":"Polynomial Equation III","batch":"June 7 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/51af4e04-0e9e-4fc1-92d3-8c375e076c72.mp4"},{"id":160,"title":"Volumetric Analysis II (Rajnish Sir)","batch":"June 7 | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/745ec90a-bdc9-4174-9c11-1c3ffc9b90c8.mp4"},{"id":161,"title":"Elasticity I","batch":"June 8 | Morning","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/fc4efd93-4cd7-424a-97ab-396548504a20.mp4"},{"id":162,"title":"Application of Derivatives III","batch":"June 8 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/0872ff3b-8719-48ca-ab44-66e96a419bb1.mp4"},{"id":163,"title":"Volumetric Analysis III (Rajnish Sir)","batch":"June 8 | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/0df270f7-38da-4395-bf1b-1915656a7bb0.mp4"},{"id":164,"title":"Logarithmic Function","batch":"June 8 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/83769326-f397-4924-957d-b447c3806bd6.mp4"},{"id":165,"title":"Motion in 1D III","batch":"June 8 | Evening","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/f7f7f819-2a98-4a23-96f5-cb84b4a0471e.mp4"},{"id":166,"title":"Polynomial Equation I","batch":"June 8 | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/bf1e50ce-e309-4c4f-9ef4-30fc2a5003c6.mp4"},{"id":167,"title":"Basic trigonometry","batch":"June 8 | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/651a85bc-c218-4bd3-b954-aac0003f1edf.mp4"},{"id":168,"title":"Reflection at curved mirrors II","batch":"June 8 | Evening","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/c3f0cfce-3b39-48ba-b630-55532f8a3b4a.mp4"},{"id":169,"title":"Elasticity II","batch":"June 9 | Friday | Morning","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/0d500c36-f5f2-485d-9019-5bc9efe10a10.mp4"},{"id":170,"title":"Application of Derivatives IV","batch":"June 9 | Friday | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/8023e2cc-a689-4395-8d9e-fdf8db5cbee2.mp4"},{"id":171,"title":"Logarithmic Function II","batch":"June 9 | Friday | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/31dba55c-4fda-4d7f-8e8f-afdbcb00deb7.mp4"},{"id":172,"title":"Volumetric Analysis IV","batch":"June 9 | Friday | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/247670a2-3e79-41a9-803e-3c6ccc699f36.mp4"},{"id":173,"title":"Electrochemistry V","batch":"June 9 | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/f1f1ea8b-3430-42b2-81f7-bb6effdbad55.mp4"},{"id":174,"title":"Viscosity II","batch":"June 9 | Evening","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/6600c7ed-15cc-45aa-91f9-9e9e4f34733f.mp4"},{"id":175,"title":"Polynomial Equation II","batch":"June 9 | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/9eb2acf8-8551-4f84-9eae-b9b9bde20e84.mp4"},{"id":176,"title":"Tense Aspect","batch":"June 9 | Evening","subject":"English","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/4781ff8b-b72c-4d87-b403-716ba4b083ac.mp4"},{"id":177,"title":"Percentage Change II","batch":"June 11 | Morning","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/7f6ecf71-aeb5-4ab8-9920-df90ba958a9b.mp4"},{"id":178,"title":"Vector I","batch":"June 11 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/50dd2dcd-c523-4dec-80b6-559ff8fa8252.mp4"},{"id":179,"title":"Application of Derivatives V","batch":"June 11 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/e67defb9-e133-4331-a5ef-654b10492f1e.mp4"},{"id":180,"title":"Derivatives (SU)","batch":"June 11 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/b7ebeec9-5dbb-49a8-a548-3fe78bba1b21.mp4"},{"id":181,"title":"Volumetric Analysis V","batch":"June 11 | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/ad93b8d1-0764-4750-810d-a9edd909e46a.mp4"},{"id":182,"title":"Mole concept III","batch":"June 11 | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/463a2b1e-640d-400a-98b9-9d94cd6aa053.mp4"},{"id":183,"title":"Refelction at curved mirrors III","batch":"June 11 | Evening","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/ef1c1bd7-3a25-44ba-a563-71f8c178a36a.mp4"},{"id":184,"title":"Straight Lines III","batch":"June 11 | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/e534efd0-dafc-4603-8996-6e243b00123f.mp4"},{"id":185,"title":"Inverse circular function","batch":"June 11 | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/b8b43f89-9c11-4dec-b481-d895736e0dd1.mp4"},{"id":186,"title":"Thermometry III","batch":"June 12 | Evening","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/8accb626-9ad8-4d90-9547-53995ee1d684.mp4"},{"id":187,"title":"Straight line IV","batch":"June 12 | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/a91f3c97-2085-4987-b304-9c7cd2faef0c.mp4"},{"id":188,"title":"Polynomial Equation III","batch":"June 12 | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/70e19e40-e889-40ba-9dcd-edfe7abbdcd3.mp4"},{"id":189,"title":"Electrochemistry VI","batch":"June 12 | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/488c50e9-c152-4cb5-a603-2ccf760456e8.mp4"},{"id":190,"title":"Volumetric analysis (Rajnish sir)","batch":"June 12 | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/b614ac2e-5372-4c8d-b7f0-c720e2104bf0.mp4"},{"id":191,"title":"Caloriemetry III","batch":"June 12 | Morning","subject":"General","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/6c993e62-39a1-4c56-8513-84bcff970785.mp4"},{"id":192,"title":"Application of Derivatives VI","batch":"June 12 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/f24e2bea-fe86-45f6-b8b8-05b8230d44da.mp4"},{"id":193,"title":"Derivatives II (SU)","batch":"June 12 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/17af2d05-f384-44bb-9894-4ea6054f79c6.mp4"},{"id":194,"title":"Tense Aspect II","batch":"June 12 | Morning","subject":"English","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/b7469c93-7409-4d75-9798-3e863aca0115.mp4"},{"id":195,"title":"Thermometry IV and Thermal Expansion","batch":"June 13 | Evening","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/7397d288-2046-4e57-bfd8-119acfc50514.mp4"},{"id":196,"title":"Polynomial Equation IV","batch":"June 13 | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/4ae65e32-ea58-4799-94b2-65a5c6fa42a0.mp4"},{"id":197,"title":"Straight Lines V","batch":"June 13 | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/43ef6d28-0782-4fa7-9a60-93e6d0143b49.mp4"},{"id":198,"title":"Volumetric Analysis II (RY)","batch":"June 13 | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/b73cf486-1b95-4ea2-8d8f-5c518fb9363f.mp4"},{"id":199,"title":"Volumetric Analysis III ( Rajnish Sir)","batch":"June 14 | Evening","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/d06e1d0c-3d34-4e75-944d-ea00856837a7.mp4"},{"id":200,"title":"Sequence and series I","batch":"June 14 | Evening","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/9c621cf5-2554-4371-85ee-5c1878db6b06.mp4"},{"id":201,"title":"Thermal Expansion II","batch":"June 14 | Evening","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/5a45bca9-9a60-4876-a496-932288d3b16c.mp4"},{"id":202,"title":"Calorimetry V","batch":"June 14 | Morning","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/2ec2f67e-f94b-4698-a666-6e3f8e3e99c6.mp4"},{"id":203,"title":"Derivative IV(SU)","batch":"June 14 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/9f8ae27b-dcdd-4c54-b979-19b5ef5e041a.mp4"},{"id":204,"title":"Vector Algebra II","batch":"June 14 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/57027f63-68ea-4912-9a9e-f74284ff9dd6.mp4"},{"id":205,"title":"Volumetric Analysis VII","batch":"June 14 | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/574db991-8078-4b5d-8d95-3789af260e8d.mp4"},{"id":206,"title":"Elasticity III","batch":"June 15 | Morning","subject":"Physics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/334c77cf-b3e7-4d56-8180-6210ada64925.mp4"},{"id":207,"title":"Vector Algebra III","batch":"June 15 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/0de1257f-495d-4128-a5a4-98043a91c3db.mp4"},{"id":208,"title":"Mole Concept II","batch":"June 15 | Morning","subject":"Chemistry","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/28a42aaa-fde9-4836-aec6-b14a64df4bff.mp4"},{"id":209,"title":"Derivative V(SU)","batch":"June 15 | Morning","subject":"Mathematics","video_url":"https://new2cdnazureclamphook.azureedge.net/clamphook-dynamic/0e6a59d7-1c14-4bd3-aefd-536aa106d45e.mp4"}];

const SUBJECT_META = {
  Physics:     { color: "#3b82f6", bg: "#1e3a5f", icon: "⚡" },
  Chemistry:   { color: "#10b981", bg: "#063f2e", icon: "⚗️" },
  Mathematics: { color: "#f59e0b", bg: "#3f2d06", icon: "∑" },
  English:     { color: "#a78bfa", bg: "#2d1b5e", icon: "📖" },
  General:     { color: "#94a3b8", bg: "#1e293b", icon: "📚" },
};

const SUBJECTS = ["All", "Physics", "Chemistry", "Mathematics", "English", "General"];

const style = `
  @import url('https://fonts.googleapis.com/css2?family=Sora:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap');
  * { box-sizing: border-box; margin: 0; padding: 0; }
  :root {
    --bg: #080c14;
    --surface: #0d1520;
    --card: #111827;
    --border: #1e2d40;
    --text: #e2e8f0;
    --muted: #64748b;
    --accent: #38bdf8;
  }
  body { font-family: 'Sora', sans-serif; background: var(--bg); color: var(--text); }
  ::-webkit-scrollbar { width: 6px; } ::-webkit-scrollbar-track { background: var(--bg); }
  ::-webkit-scrollbar-thumb { background: #1e3a5f; border-radius: 3px; }
`;

// ── tiny helpers ──────────────────────────────────────────────────────────────
function Badge({ subject }) {
  const m = SUBJECT_META[subject] || SUBJECT_META.General;
  return (
    <span style={{
      fontSize: 11, fontWeight: 600, padding: "2px 8px", borderRadius: 20,
      background: m.bg, color: m.color, border: `1px solid ${m.color}33`,
      letterSpacing: ".04em", whiteSpace: "nowrap"
    }}>
      {m.icon} {subject}
    </span>
  );
}

function VideoCard({ video, onPlay, isActive }) {
  const m = SUBJECT_META[video.subject] || SUBJECT_META.General;
  return (
    <div onClick={() => onPlay(video)}
      style={{
        background: isActive ? "#0f2038" : "var(--card)",
        border: `1px solid ${isActive ? m.color + "80" : "var(--border)"}`,
        borderRadius: 12, padding: "14px 16px", cursor: "pointer",
        transition: "all .18s", display: "flex", gap: 12, alignItems: "flex-start",
        boxShadow: isActive ? `0 0 0 1px ${m.color}40, 0 4px 20px ${m.color}20` : "none",
      }}
      onMouseEnter={e => { if (!isActive) e.currentTarget.style.borderColor = "#2a4a70"; }}
      onMouseLeave={e => { if (!isActive) e.currentTarget.style.borderColor = "var(--border)"; }}
    >
      <div style={{
        width: 36, height: 36, borderRadius: 8, background: m.bg,
        display: "flex", alignItems: "center", justifyContent: "center",
        fontSize: 18, flexShrink: 0, border: `1px solid ${m.color}33`
      }}>{m.icon}</div>
      <div style={{ flex: 1, minWidth: 0 }}>
        <div style={{ fontSize: 13, fontWeight: 500, lineHeight: 1.4,
          color: isActive ? "#fff" : var_text, marginBottom: 6,
          overflow: "hidden", display: "-webkit-box",
          WebkitLineClamp: 2, WebkitBoxOrient: "vertical"
        }}>{video.title}</div>
        <div style={{ display: "flex", gap: 6, flexWrap: "wrap", alignItems: "center" }}>
          <Badge subject={video.subject} />
          <span style={{ fontSize: 10, color: "var(--muted)", fontFamily: "'JetBrains Mono'" }}>
            #{video.batch}
          </span>
        </div>
      </div>
      {isActive && (
        <div style={{ width: 8, height: 8, borderRadius: "50%",
          background: m.color, flexShrink: 0, marginTop: 4, animation: "pulse 1.5s infinite" }} />
      )}
    </div>
  );
}

const var_text = "var(--text)";

// ── Pages ─────────────────────────────────────────────────────────────────────
function HomePage({ onPlay, onNavigate }) {
  const counts = useMemo(() => {
    const c = {};
    VIDEOS.forEach(v => { c[v.subject] = (c[v.subject] || 0) + 1; });
    return c;
  }, []);
  const recent = VIDEOS.slice(-8).reverse();

  return (
    <div style={{ padding: "32px 24px", maxWidth: 1100, margin: "0 auto" }}>
      {/* Hero */}
      <div style={{
        background: "linear-gradient(135deg, #0a1628 0%, #0f2038 50%, #0a1628 100%)",
        border: "1px solid #1e3a5f", borderRadius: 20, padding: "40px 36px",
        marginBottom: 36, position: "relative", overflow: "hidden"
      }}>
        <div style={{
          position: "absolute", top: -60, right: -60, width: 200, height: 200,
          background: "radial-gradient(circle, #38bdf820 0%, transparent 70%)", borderRadius: "50%"
        }} />
        <div style={{ position: "relative" }}>
          <div style={{ fontSize: 12, letterSpacing: "0.15em", color: "var(--accent)",
            textTransform: "uppercase", marginBottom: 10, fontWeight: 600 }}>
            IOE Preparation • Lecture Library
          </div>
          <h1 style={{ fontSize: 32, fontWeight: 700, marginBottom: 12, lineHeight: 1.2 }}>
            Your Complete<br />
            <span style={{ color: "var(--accent)" }}>Study Video Portal</span>
          </h1>
          <p style={{ color: "var(--muted)", maxWidth: 480, lineHeight: 1.7, marginBottom: 24 }}>
            {VIDEOS.length} unique lectures across Physics, Chemistry, Mathematics & English —
            deduplicated and organized for efficient revision.
          </p>
          <div style={{ display: "flex", gap: 12, flexWrap: "wrap" }}>
            {SUBJECTS.slice(1).map(s => {
              const m = SUBJECT_META[s];
              return (
                <div key={s} onClick={() => onNavigate("browse", s)}
                  style={{
                    background: m.bg, border: `1px solid ${m.color}50`,
                    borderRadius: 10, padding: "10px 16px", cursor: "pointer",
                    display: "flex", alignItems: "center", gap: 8, transition: "all .15s"
                  }}
                  onMouseEnter={e => e.currentTarget.style.borderColor = m.color}
                  onMouseLeave={e => e.currentTarget.style.borderColor = `${m.color}50`}
                >
                  <span style={{ fontSize: 20 }}>{m.icon}</span>
                  <div>
                    <div style={{ fontSize: 12, fontWeight: 600, color: m.color }}>{s}</div>
                    <div style={{ fontSize: 11, color: "var(--muted)" }}>{counts[s] || 0} videos</div>
                  </div>
                </div>
              );
            })}
          </div>
        </div>
      </div>

      {/* Recently Added */}
      <div style={{ marginBottom: 8, display: "flex", alignItems: "center", justifyContent: "space-between" }}>
        <h2 style={{ fontSize: 18, fontWeight: 600 }}>Recently Added</h2>
        <button onClick={() => onNavigate("browse", "All")}
          style={{ background: "none", border: "1px solid var(--border)", color: "var(--accent)",
            borderRadius: 8, padding: "6px 14px", cursor: "pointer", fontSize: 13 }}>
          Browse All →
        </button>
      </div>
      <div style={{ display: "grid", gridTemplateColumns: "repeat(auto-fill, minmax(280px, 1fr))", gap: 10, marginTop: 16 }}>
        {recent.map(v => <VideoCard key={v.id} video={v} onPlay={onPlay} isActive={false} />)}
      </div>
    </div>
  );
}

function BrowsePage({ onPlay, activeVideo, initialSubject }) {
  const [subject, setSubject] = useState(initialSubject || "All");
  const [search, setSearch] = useState("");
  const [activeBatch, setActiveBatch] = useState(null);

  useEffect(() => { if (initialSubject) setSubject(initialSubject); }, [initialSubject]);

  const batches = useMemo(() => [...new Set(VIDEOS.map(v => v.batch))], []);

  const filtered = useMemo(() => {
    return VIDEOS.filter(v => {
      const matchSubject = subject === "All" || v.subject === subject;
      const matchSearch = !search || v.title.toLowerCase().includes(search.toLowerCase()) ||
        v.batch.toLowerCase().includes(search.toLowerCase());
      const matchBatch = !activeBatch || v.batch === activeBatch;
      return matchSubject && matchSearch && matchBatch;
    });
  }, [subject, search, activeBatch]);

  return (
    <div style={{ display: "flex", height: "calc(100vh - 56px)" }}>
      {/* Sidebar */}
      <div style={{
        width: 220, background: "var(--surface)", borderRight: "1px solid var(--border)",
        overflowY: "auto", flexShrink: 0
      }}>
        <div style={{ padding: "16px 12px 8px", fontSize: 11, color: "var(--muted)",
          textTransform: "uppercase", letterSpacing: ".1em", fontWeight: 600 }}>
          Batches ({batches.length})
        </div>
        <div style={{ padding: "0 8px" }}>
          <div onClick={() => setActiveBatch(null)}
            style={{
              padding: "8px 10px", borderRadius: 8, cursor: "pointer", fontSize: 12,
              color: !activeBatch ? "var(--accent)" : "var(--muted)",
              background: !activeBatch ? "#0f2038" : "transparent", marginBottom: 2
            }}>All Batches</div>
          {batches.map(b => (
            <div key={b} onClick={() => setActiveBatch(b === activeBatch ? null : b)}
              style={{
                padding: "7px 10px", borderRadius: 8, cursor: "pointer", fontSize: 11,
                lineHeight: 1.4, marginBottom: 2,
                color: activeBatch === b ? "var(--accent)" : "var(--muted)",
                background: activeBatch === b ? "#0f2038" : "transparent"
              }}
              onMouseEnter={e => { if (activeBatch !== b) e.currentTarget.style.background = "#0d1520"; }}
              onMouseLeave={e => { if (activeBatch !== b) e.currentTarget.style.background = "transparent"; }}
            >{b}</div>
          ))}
        </div>
      </div>

      {/* Main */}
      <div style={{ flex: 1, display: "flex", flexDirection: "column", overflow: "hidden" }}>
        {/* Filters bar */}
        <div style={{
          padding: "12px 20px", borderBottom: "1px solid var(--border)",
          display: "flex", gap: 10, alignItems: "center", flexWrap: "wrap",
          background: "var(--surface)"
        }}>
          <div style={{ position: "relative", flex: 1, minWidth: 200 }}>
            <span style={{ position: "absolute", left: 12, top: "50%", transform: "translateY(-50%)",
              color: "var(--muted)", fontSize: 14, pointerEvents: "none" }}>🔍</span>
            <input
              value={search} onChange={e => setSearch(e.target.value)}
              placeholder="Search videos..."
              style={{
                width: "100%", background: "var(--bg)", border: "1px solid var(--border)",
                borderRadius: 10, padding: "8px 12px 8px 34px", color: "var(--text)",
                fontSize: 13, outline: "none", fontFamily: "Sora"
              }}
            />
          </div>
          <div style={{ display: "flex", gap: 6, flexWrap: "wrap" }}>
            {SUBJECTS.map(s => {
              const m = s !== "All" ? SUBJECT_META[s] : null;
              const active = subject === s;
              return (
                <button key={s} onClick={() => setSubject(s)} style={{
                  background: active ? (m ? m.bg : "#0f2038") : "var(--bg)",
                  border: `1px solid ${active ? (m ? m.color : "var(--accent)") : "var(--border)"}`,
                  color: active ? (m ? m.color : "var(--accent)") : "var(--muted)",
                  borderRadius: 8, padding: "6px 12px", cursor: "pointer", fontSize: 12,
                  fontFamily: "Sora", fontWeight: active ? 600 : 400, transition: "all .15s"
                }}>
                  {s !== "All" && m?.icon + " "}{s}
                </button>
              );
            })}
          </div>
          <span style={{ fontSize: 12, color: "var(--muted)", whiteSpace: "nowrap" }}>
            {filtered.length} videos
          </span>
        </div>

        {/* Grid */}
        <div style={{ flex: 1, overflowY: "auto", padding: 20 }}>
          {filtered.length === 0 ? (
            <div style={{ textAlign: "center", color: "var(--muted)", padding: "60px 0" }}>
              <div style={{ fontSize: 48, marginBottom: 12 }}>🔍</div>
              <div>No videos match your search</div>
            </div>
          ) : (
            <div style={{ display: "grid", gridTemplateColumns: "repeat(auto-fill, minmax(280px, 1fr))", gap: 10 }}>
              {filtered.map(v => (
                <VideoCard key={v.id} video={v} onPlay={onPlay} isActive={activeVideo?.id === v.id} />
              ))}
            </div>
          )}
        </div>
      </div>
    </div>
  );
}

function PlayerPage({ video, onPlay }) {
  const related = useMemo(() => {
    if (!video) return [];
    return VIDEOS.filter(v => v.id !== video.id && v.subject === video.subject).slice(0, 12);
  }, [video]);

  if (!video) return (
    <div style={{ display: "flex", alignItems: "center", justifyContent: "center",
      height: "calc(100vh - 56px)", color: "var(--muted)", flexDirection: "column", gap: 12 }}>
      <div style={{ fontSize: 64 }}>▶️</div>
      <div style={{ fontSize: 16 }}>Select a video to start watching</div>
    </div>
  );

  const m = SUBJECT_META[video.subject] || SUBJECT_META.General;
  const batchVideos = VIDEOS.filter(v => v.batch === video.batch);
  const currentIdx = batchVideos.findIndex(v => v.id === video.id);

  return (
    <div style={{ display: "flex", height: "calc(100vh - 56px)", overflow: "hidden" }}>
      {/* Player */}
      <div style={{ flex: 1, overflowY: "auto" }}>
        <div style={{ background: "#000", aspectRatio: "16/9", width: "100%" }}>
          <video
            key={video.id}
            src={video.video_url}
            controls autoPlay
            style={{ width: "100%", height: "100%", display: "block" }}
          />
        </div>
        <div style={{ padding: "20px 24px" }}>
          <div style={{ display: "flex", gap: 8, marginBottom: 10, flexWrap: "wrap" }}>
            <Badge subject={video.subject} />
            <span style={{ fontSize: 11, color: "var(--muted)", fontFamily: "'JetBrains Mono'",
              background: "var(--surface)", padding: "2px 8px", borderRadius: 20 }}>
              {video.batch}
            </span>
          </div>
          <h1 style={{ fontSize: 22, fontWeight: 700, lineHeight: 1.3, marginBottom: 16 }}>
            {video.title}
          </h1>

          {/* Batch playlist */}
          {batchVideos.length > 1 && (
            <div style={{ background: "var(--surface)", border: "1px solid var(--border)",
              borderRadius: 12, padding: 16, marginBottom: 20 }}>
              <div style={{ fontSize: 12, color: "var(--muted)", marginBottom: 10, fontWeight: 600,
                textTransform: "uppercase", letterSpacing: ".06em" }}>
                From this batch ({currentIdx + 1}/{batchVideos.length})
              </div>
              <div style={{ display: "flex", flexDirection: "column", gap: 6 }}>
                {batchVideos.map((v, i) => (
                  <div key={v.id} onClick={() => onPlay(v)}
                    style={{
                      display: "flex", alignItems: "center", gap: 10, padding: "8px 10px",
                      borderRadius: 8, cursor: "pointer", background: v.id === video.id ? "#0f2038" : "transparent",
                      border: `1px solid ${v.id === video.id ? m.color + "40" : "transparent"}`,
                      transition: "all .12s"
                    }}
                    onMouseEnter={e => { if (v.id !== video.id) e.currentTarget.style.background = "var(--card)"; }}
                    onMouseLeave={e => { if (v.id !== video.id) e.currentTarget.style.background = "transparent"; }}
                  >
                    <span style={{ width: 22, height: 22, borderRadius: "50%", fontSize: 11, fontWeight: 700,
                      background: v.id === video.id ? m.color : "var(--border)",
                      color: v.id === video.id ? "#000" : "var(--muted)",
                      display: "flex", alignItems: "center", justifyContent: "center", flexShrink: 0 }}>
                      {i + 1}
                    </span>
                    <span style={{ fontSize: 13, color: v.id === video.id ? "#fff" : "var(--text)",
                      flex: 1, lineHeight: 1.3 }}>{v.title}</span>
                    <Badge subject={v.subject} />
                  </div>
                ))}
              </div>
            </div>
          )}
        </div>
      </div>

      {/* Related sidebar */}
      <div style={{ width: 320, borderLeft: "1px solid var(--border)", overflowY: "auto",
        background: "var(--surface)", flexShrink: 0 }}>
        <div style={{ padding: "14px 16px 8px", fontSize: 12, color: "var(--muted)",
          textTransform: "uppercase", letterSpacing: ".08em", fontWeight: 600,
          borderBottom: "1px solid var(--border)" }}>
          More {video.subject} videos
        </div>
        <div style={{ display: "flex", flexDirection: "column", gap: 8, padding: 12 }}>
          {related.map(v => (
            <VideoCard key={v.id} video={v} onPlay={onPlay} isActive={v.id === video.id} />
          ))}
        </div>
      </div>
    </div>
  );
}

// ── App Shell ─────────────────────────────────────────────────────────────────
export default function App() {
  const [page, setPage] = useState("home");
  const [activeVideo, setActiveVideo] = useState(null);
  const [browseSubject, setBrowseSubject] = useState("All");
  const [searchOpen, setSearchOpen] = useState(false);
  const [globalSearch, setGlobalSearch] = useState("");

  const globalResults = useMemo(() => {
    if (!globalSearch.trim()) return [];
    const q = globalSearch.toLowerCase();
    return VIDEOS.filter(v =>
      v.title.toLowerCase().includes(q) || v.batch.toLowerCase().includes(q) || v.subject.toLowerCase().includes(q)
    ).slice(0, 8);
  }, [globalSearch]);

  function handlePlay(video) {
    setActiveVideo(video);
    setPage("player");
    setSearchOpen(false);
    setGlobalSearch("");
  }

  function handleNavigate(pg, subject) {
    setPage(pg);
    if (subject) setBrowseSubject(subject);
  }

  const navItems = [
    { id: "home", label: "Home", icon: "⌂" },
    { id: "browse", label: "Browse", icon: "⊞" },
    { id: "player", label: "Now Playing", icon: "▶" },
  ];

  return (
    <div style={{ minHeight: "100vh", background: "var(--bg)", fontFamily: "Sora, sans-serif" }}>
      <style>{style}
        {`@keyframes pulse { 0%,100%{opacity:1} 50%{opacity:.4} }`}
        {`input::placeholder { color: #64748b; }`}
      </style>

      {/* Navbar */}
      <nav style={{
        height: 56, background: "var(--surface)", borderBottom: "1px solid var(--border)",
        display: "flex", alignItems: "center", padding: "0 20px", gap: 8, position: "sticky",
        top: 0, zIndex: 100
      }}>
        <div style={{ display: "flex", alignItems: "center", gap: 8, marginRight: 12 }}>
          <div style={{ width: 28, height: 28, borderRadius: 8, background: "var(--accent)",
            display: "flex", alignItems: "center", justifyContent: "center", fontSize: 14 }}>▶</div>
          <span style={{ fontWeight: 700, fontSize: 15, color: "#fff", letterSpacing: "-.01em" }}>
            StudyTube
          </span>
        </div>

        {navItems.map(n => (
          <button key={n.id} onClick={() => setPage(n.id)}
            style={{
              background: page === n.id ? "#0f2038" : "none",
              border: `1px solid ${page === n.id ? "#1e4a7a" : "transparent"}`,
              color: page === n.id ? "var(--accent)" : "var(--muted)",
              borderRadius: 8, padding: "6px 12px", cursor: "pointer",
              fontSize: 13, fontFamily: "Sora", fontWeight: 500, transition: "all .12s"
            }}>
            {n.icon} {n.label}
          </button>
        ))}

        <div style={{ flex: 1 }} />

        {/* Global search */}
        <div style={{ position: "relative" }}>
          <div style={{ display: "flex", alignItems: "center", gap: 6,
            background: "var(--bg)", border: "1px solid var(--border)",
            borderRadius: 10, padding: "6px 12px", cursor: "text",
            minWidth: 200
          }} onClick={() => setSearchOpen(true)}>
            <span style={{ color: "var(--muted)", fontSize: 13 }}>🔍</span>
            <input
              value={globalSearch}
              onChange={e => { setGlobalSearch(e.target.value); setSearchOpen(true); }}
              onFocus={() => setSearchOpen(true)}
              placeholder="Quick search..."
              style={{ background: "none", border: "none", outline: "none",
                color: "var(--text)", fontSize: 13, fontFamily: "Sora", width: "100%" }}
            />
          </div>
          {searchOpen && globalSearch && globalResults.length > 0 && (
            <div style={{
              position: "absolute", top: "calc(100% + 8px)", right: 0, width: 380,
              background: "var(--card)", border: "1px solid var(--border)", borderRadius: 12,
              overflow: "hidden", boxShadow: "0 20px 40px #00000080", zIndex: 200
            }}>
              {globalResults.map(v => (
                <div key={v.id} onClick={() => handlePlay(v)}
                  style={{ padding: "10px 14px", cursor: "pointer", display: "flex",
                    gap: 10, alignItems: "center", borderBottom: "1px solid var(--border)" }}
                  onMouseEnter={e => e.currentTarget.style.background = "#0f2038"}
                  onMouseLeave={e => e.currentTarget.style.background = "transparent"}
                >
                  <span style={{ fontSize: 20 }}>{SUBJECT_META[v.subject]?.icon}</span>
                  <div style={{ flex: 1, minWidth: 0 }}>
                    <div style={{ fontSize: 13, fontWeight: 500,
                      overflow: "hidden", textOverflow: "ellipsis", whiteSpace: "nowrap" }}>{v.title}</div>
                    <div style={{ fontSize: 11, color: "var(--muted)" }}>{v.batch}</div>
                  </div>
                  <Badge subject={v.subject} />
                </div>
              ))}
            </div>
          )}
          {searchOpen && (
            <div style={{ position: "fixed", inset: 0, zIndex: 150 }}
              onClick={() => { setSearchOpen(false); setGlobalSearch(""); }} />
          )}
        </div>

        {activeVideo && (
          <div style={{ fontSize: 11, color: "var(--muted)", maxWidth: 180,
            overflow: "hidden", textOverflow: "ellipsis", whiteSpace: "nowrap",
            marginLeft: 8, padding: "4px 10px", background: "var(--bg)",
            border: "1px solid var(--border)", borderRadius: 8 }}>
            ▶ {activeVideo.title}
          </div>
        )}
      </nav>

      {/* Page */}
      {page === "home" && <HomePage onPlay={handlePlay} onNavigate={handleNavigate} />}
      {page === "browse" && <BrowsePage onPlay={handlePlay} activeVideo={activeVideo} initialSubject={browseSubject} />}
      {page === "player" && <PlayerPage video={activeVideo} onPlay={handlePlay} />}
    </div>
  );
}
