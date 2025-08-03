import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import Image from "next/image";

export default function TurboSheepHome() {
  return (
    <div className="min-h-screen bg-gradient-to-b from-yellow-100 to-white p-6">
      <div className="max-w-3xl mx-auto text-center">
        <div className="flex justify-center mb-4">
          <Image
            src="/photo_2025-07-30_19-11-06.jpg"
            alt="TurboSheep Logo"
            width={128}
            height={128}
            className="rounded-full"
          />
        </div>
        <h1 className="text-4xl font-bold text-yellow-700 mb-2">TurboSheep</h1>
        <p className="text-lg text-gray-700 mb-6">
          The first sheep-themed meme coin on BSC aiming to go viral 🚀
        </p>

        <div className="grid grid-cols-1 md:grid-cols-2 gap-4 mb-6">
          <Card className="shadow-md">
            <CardContent className="p-4 text-left">
              <h2 className="font-bold text-yellow-700 mb-2">🔢 Total Supply</h2>
              <p>100,000,000,000 TSH</p>
            </CardContent>
          </Card>
          <Card className="shadow-md">
            <CardContent className="p-4 text-left">
              <h2 className="font-bold text-yellow-700 mb-2">📜 Contract</h2>
              <p className="break-all text-sm">
                0x5a887c259b84304825bfF825f42b646F767F3E3d
              </p>
            </CardContent>
          </Card>
          <Card className="shadow-md">
            <CardContent className="p-4 text-left">
              <h2 className="font-bold text-yellow-700 mb-2">🔐 Liquidity Lock</h2>
              <a
                className="text-blue-600 underline text-sm"
                href="https://www.pinksale.finance/pinklock/bsc/record/1341072"
                target="_blank"
              >
                View on PinkLock
              </a>
              <p className="mt-1 text-sm">Locked for 282 days</p>
            </CardContent>
          </Card>
          <Card className="shadow-md">
            <CardContent className="p-4 text-left">
              <h2 className="font-bold text-yellow-700 mb-2">💱 Pair</h2>
              <p>TSH / WBNB</p>
            </CardContent>
          </Card>
        </div>

        <a
          href="https://pancakeswap.finance/swap?outputCurrency=0x5a887c259b84304825bfF825f42b646F767F3E3d"
          target="_blank"
        >
          <Button className="bg-yellow-500 hover:bg-yellow-600 text-white text-lg px-6 py-2 rounded-full">
            Buy on PancakeSwap
          </Button>
        </a>

        <div className="mt-12 text-left">
          <h2 className="text-2xl font-bold text-yellow-700 mb-4">📄 Whitepaper</h2>
          <p className="text-gray-800 mb-2">
            TurboSheep is a unique meme coin launched on Binance Smart Chain (BSC) with the goal of going viral, attracting capital, and building an ecosystem in stages. Its total supply is 100 billion tokens, with liquidity locked for 282 days.
          </p>
          <p className="text-gray-800 mb-2">
            The project is independently launched and initially focuses on community building, meme content creation, free listings, and wide exposure through social media campaigns.
          </p>
          <p className="text-gray-800">
            In the second phase, with a strong community, new use cases and utilities will be introduced progressively.
          </p>
        </div>
      </div>
    </div>
  );
}
# turbosheep
