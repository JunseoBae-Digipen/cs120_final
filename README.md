- Name: Junseo Bae
- Exam Name: CS120 Programming Final Exam
- Course Name: CS120
- Term: Fall 2020
- Incomplete sections about this assignment: Most of core requirements + Using references(&) 
- Section that lists the File Name and Line Number for all code requirements:
 
  -`File IO`
  
  `std::ofstream result{"result.txt"};
   result << "Total jelly in window: " << images.size() << "\n";`(line 85~87, main.cpp)
  
  -`std::map or std::unordered_map with an enum key and a doodle Image value`
  
  `std::map<enumerator_image, Image> map1;`(line 24, main.cpp)
  
  -`namespace`
  
  `namespace image_coordinate
  {
    double image_x = random(-100, 100);
    double image_y = random(-150, 150);
  }`(line 16~20, main.cpp)
  
  -`functions`
  
   `inline void Button::Draw_Button()
{ 
    doodle::draw_rectangle(button_x, button_y, button_width, button_height); 
}`(line 16~19, button.cpp)
   
  -`class/struct`
  
  `class Button
{
public:
    int button_x = 0;
    int button_y = 0;
    int button_width = 100;
    int button_height = 100;
    std::string button_text = "button";
    bool isbuttonclicked = false;
    Button();
    Button(int button_x, int button_y, int button_width, int button_height);
    inline void Draw_Button();
};`(line 10~23, button.h)
  
  -`References`
  
  `unused`
  
  -`std::string`
  
  `std::string button_text = "button";`(line 66, main.cpp)
  
  -`std::vector`
  
  `std::vector<Image> images;`(line 26, main.cpp)
  
  -`int`
  
  `int button_x = 0;`(line 13, button.h)
  
  -`double`
  
  `double image_x = random(-100, 100);`(line 18, main.cpp)
  
  -`bool`
  
  `bool isbuttonclicked = false;`(line 18, button.h)
  
  -`exceptions`
  
  `catch (const std::exception& e)
{
    std::cerr << "Error : " << e.what() << '\n';
    return -1;
}`(line 93~97, main.cpp)
  
  -`inline`
  
  `inline void Draw_Button();`(line 22, button.h)
  
  -`constexpr`
  
  `constexpr int window_width = 1280;`(line 30, main.cpp)
  
  -`std::array`
  
  `unused`
  
- Section describing what I am proud of about this assignment
> None
