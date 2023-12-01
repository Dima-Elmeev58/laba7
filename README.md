# laba7
{
    int n1 = 3; int n2 = 5;
    string s1 = "Перваястрока"; string s2 = "Втораястрока";
    string s3 = String.Join("", s1.Take(n1)) + String.Join("", s2.Skip(s2.Length - n2));
    Console.WriteLine(s3);
    Console.WriteLine(true);
}
