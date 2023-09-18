![GitHub stats](https://github-readme-stats.vercel.app/api?username=Party-Pie&show_icons=true&theme=holi&rank_icon=percentile&hide_title=true&hide_border=true)  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Party-Pie&theme=holi&hide_title=true&layout=compact&hide_border=true)

<hr>

![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=Party-Pie&repo=pyfernet&theme=aura)
![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=Party-Pie&repo=HPC&theme=aura)

<br>
#include <initializer_list>
#include <string>

template <typename T>
class Vector {
public:
    Vector(int);
    Vector(std::initializer_list<T> il) {
        for (const T& elem : il)
            std::cout << elem << ' ';
    }
};

int main() {
    Vector v1 {1, 2, 3};         // CTAD deduces T as int
    Vector v2 = v1;              // CTAD deduces T as int
    auto p = new Vector{1, 2, 3}; // CTAD deduces T as int
    Vector v3 {"H", "I"};        // CTAD deduces T as std::string
    return 0;
}#include <initializer_list>
#include <string>

template <typename T>
class Vector {
public:
    Vector(int);
    Vector(std::initializer_list<T> il) {
        for (const T& elem : il)
            std::cout << elem << ' ';
    }
};

int main() {
    Vector v1 {1, 2, 3};         // CTAD deduces T as int
    Vector v2 = v1;              // CTAD deduces T as int
    auto p = new Vector{1, 2, 3}; // CTAD deduces T as int
    Vector v3 {"H", "I"};        // CTAD deduces T as std::string
    return 0;
}
**Note**: I decided to take a break for a month aprox from github this mid august-september, now im back
