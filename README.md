
# Assignment 2

## Services, Info, Team Members, or Product Page**

---

**Company**: Six Sisters Events & Catering
- Inspired by my aunts' business website.

**Company nature**: Restaurant / Events & Catering

**Logo**: Icons8

**Color Scheme**: Coolors ( [https://coolors.co/](https://coolors.co/) )
                  https://coolors.co/001524-15616d-ffecd1-ff7d00-78290f

**Font**: google fonts
- Berkshire Swash (logo)
- Roboto Slab (back-up)
- Rubik (content)

**Images**: 
- Personal - Wedding photos
- Pexels - Photo by Airam Dato-on
- Unsplash - Photo by Eiliv-Sonas Aceron
- Unsplash - Photo by Avel Chuklanov 

**icons**
- Instagram: https://icons8.com/icon/ZRiAFreol5mE/instagram
- Facebook: https://icons8.com/icon/CtrV2SV33rD9/facebook-circled

---

### **Problems Encountered**

1.  **Logo:** I saved my icon in my assets but I realized it's a jpg file and the color cannot be changed and shadow cannot be added, I had to search the same icon in Icons8 and use the link.
2. **Header background picture:** Again, I saved this picture in my assets/images but for some reason, it does not work for me, I'm glad I remembered who and where I took this image from and used the image link for this project. Also hoping, I could change the filter for this background and make it a bit darker but not sure how to do that.
3. **Subscribe form:** could not get the label to center with input box. Could not get the content wrap.  I could not center my subscribe form. I solved the problem by adding padding on the left. I think there is a better way of doing it though.
4. **Article (Cards):** Having problems with centering them while being on auto-fit box for grid.
- I solved the problem:

 **previous**
`container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  grid-auto-rows: 1fr 1fr 1fr;
  justify-content: space-evenly;
  align-items: center;
  padding: 10px;
  grid-gap; 10px;
}

**after**
.container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, auto));
  grid-auto-rows: 1fr 1fr 1fr;
  justify-content: space-evenly;
  align-items: center;
  padding: 10px;
  grid-gap; 10px;
}`

5. **icons:** I'm not sure how to embed icons properly.
6. **Wedding Photo:** The photo is not responsive.

---

**Attributions**

1. Jessica Gust: Responsive navigation, she also tried to help me with my margins but there's too many things breaking. Thanks Jess! 
2. Ashlyn Knox (Instructor): Licensing guide. GitHub problem, for teaching me how to clone and save my commits!!!

