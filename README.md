# CraftVerse
import React from "react";
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import { Sparkles, Gift, Heart, Star, Quote } from "lucide-react";

export default function CraftverseHome() {
  return (
    <div className="min-h-screen bg-gradient-to-br from-pink-100 to-yellow-50 p-6">
      <header className="text-center py-10">
        <h1 className="text-4xl font-bold text-pink-600 flex justify-center items-center gap-2">
          <Sparkles className="text-yellow-500" /> Craftverse
        </h1>
        <p className="mt-2 text-lg text-gray-700 max-w-xl mx-auto">
          Creating magical anniversary & birthday experiences through wooden engraved messages and personalized poems or songs.
        </p>
        <Button className="mt-6 bg-pink-500 hover:bg-pink-600 text-white text-lg px-6 py-2 rounded-2xl shadow-lg">
          Start Your Story
        </Button>
      </header>

      <main className="grid grid-cols-1 md:grid-cols-3 gap-6 mt-12 max-w-6xl mx-auto">
        <Card className="rounded-2xl shadow-md hover:shadow-xl transition">
          <CardContent className="p-6 flex flex-col items-center">
            <Gift className="text-pink-400 w-10 h-10 mb-4" />
            <h2 className="text-xl font-semibold mb-2">Personalized Gifts</h2>
            <p className="text-gray-600 text-center">
              Choose from custom wooden engravings or personalized poems and songs tailored to your loved ones.
            </p>
          </CardContent>
        </Card>

        <Card className="rounded-2xl shadow-md hover:shadow-xl transition">
          <CardContent className="p-6 flex flex-col items-center">
            <Heart className="text-red-400 w-10 h-10 mb-4" />
            <h2 className="text-xl font-semibold mb-2">Anniversary Magic</h2>
            <p className="text-gray-600 text-center">
              Celebrate years of love with engraved messages that last a lifetime and songs that echo in the heart.
            </p>
          </CardContent>
        </Card>

        <Card className="rounded-2xl shadow-md hover:shadow-xl transition">
          <CardContent className="p-6 flex flex-col items-center">
            <Star className="text-yellow-400 w-10 h-10 mb-4" />
            <h2 className="text-xl font-semibold mb-2">Birthday Bliss</h2>
            <p className="text-gray-600 text-center">
              Add sparkle to birthdays with handcrafted poems or musical surprises that make the day unforgettable.
            </p>
          </CardContent>
        </Card>
      </main>

      <section className="mt-20 max-w-4xl mx-auto text-center">
        <h2 className="text-3xl font-bold text-pink-600 mb-8 flex justify-center items-center gap-2">
          <Quote className="text-yellow-500" /> What Our Customers Say
        </h2>
        <div className="grid md:grid-cols-3 gap-6">
          <Card className="p-4 shadow-md rounded-2xl">
            <p className="text-gray-700 italic">“Craftverse made our 5th anniversary unforgettable. The engraved message brought tears to our eyes!”</p>
            <p className="mt-4 font-semibold text-pink-500">— Aditi & Rohan</p>
          </Card>
          <Card className="p-4 shadow-md rounded-2xl">
            <p className="text-gray-700 italic">“I gifted a song for my sister's birthday and she absolutely loved it. So unique and thoughtful!”</p>
            <p className="mt-4 font-semibold text-pink-500">— Nikhil Sharma</p>
          </Card>
          <Card className="p-4 shadow-md rounded-2xl">
            <p className="text-gray-700 italic">“The quality and attention to detail in the wooden gift were top-notch. Highly recommended!”</p>
            <p className="mt-4 font-semibold text-pink-500">— Priya Mehta</p>
          </Card>
        </div>
      </section>

      <footer className="mt-16 text-center text-sm text-gray-500">
        © 2025 Craftverse. Crafted with ❤️ for your memories.
      </footer>
    </div>
  );
}
